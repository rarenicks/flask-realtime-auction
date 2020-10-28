# Auction 

Features:
- `Flask-WTF` for form creation and validation
- `Flask-SQLAlchemy` for database access
- `Flask-Admin` for easy control panel over actions on platform
- `Flask-SocketIO` for real time update of values
- `TinyPNG` for compression of profile and article images
- Hashing passwords with **PBKDF2**  to reduce vulnerabilities to brute force attacks

## Preview

Check at [http://auction-app-rwpd.herokuapp.com/](https://auction-app-rwpd.herokuapp.com/). 

You can use username `test` and password `dummy123` for testing

## Install and run locally

1. Create virtual environment 
2. With virtual env activated, install dependencies using pip as `pip install -r requirements.txt`
3. Export `FLASK_APP` environment variable to be equal to **auction** (e.g. `export FLASK_APP=auction`)
4. (*OPTIONAL*) Export `RECAPTCHA_PUBLIC_KEY` and `RECAPTCHA_PRIVATE_KEY` to use *reCaptcha* on registration form. You can generate keys at https://www.google.com/recaptcha/intro/v3.html
5. With `flask run`, you will run and expose application on port *5000*

