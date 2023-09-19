# Password Checker

This Flask application lets the user securely check if a password has been pwned or hacked without transmitting the password through theinternet. It uses Troy Hunt’s Have I Been Pwned API to get the passwords that have been leaked in the past using only the first five characters ofthe SHA1‑generated password.

## Usage

Install dependencies

```
pip install -r requirements.txt
```

Run the python script

```
py app.py
```
