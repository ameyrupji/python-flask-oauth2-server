# OAuth 2.0 Server

Sample OAuth 2.0 Server using Flask.

### Commands
```
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt

# Disable SSL (only for development)
export AUTHLIB_INSECURE_TRANSPORT=1

export FLASK_APP=website/run.py
flask run


# to exit from venv
deactivate
```


http://127.0.0.1:5000/

## Useful Links

- Sample Client using Authorization Code Grant Flow - https://github.com/ameyrupji/python-flask-oauth2-client
- https://github.com/authlib/example-oauth2-server
- https://docs.authlib.org/en/latest/specs/rfc6749.html
