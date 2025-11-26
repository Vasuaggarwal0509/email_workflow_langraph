# .env file in root folder
```
MY_EMAIL=v*****l@gmail.com
GMAIL_CREDENTIALS_FILE=credentials.json
GMAIL_TOKEN_FILE=tokens/token.json

GEMINI_API_KEY="AIzaSy*************vaGqw"
GROQ_API_KEY="gsk_QP8fS******************mNDMppIv8VlO"
```

# Credentials.json in root folder
```
{
  "installed": {
    "client_id": "3369121******************uue5p.apps.googleusercontent.com",
    "project_id": "smooth-hu******6",
    "auth_uri": "https://accounts.google.com/o/oauth2/auth",
    "token_uri": "https://oauth2.googleapis.com/token",
    "auth_provider_x509_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
    "client_secret": "GOCSPX-*********ye3dny7eUJ",
    "redirect_uris": ["http://localhost"]
  }
}

```

* console google cloud is where we make GmailAPI key 
* we need to enable gmailapi key 
* make desktop client for making client id ,if you are using Vscode type local system.
* add scopes for the api wisely as sometimes errors occur becoz of limited scope (like .send is restricted so email cannot be sent)
* when you make Oauth screen then copy the credentials.json in safe place (token.json is automatically configured , no need to write by ourselves)


now just all set so write in terminal 
```
python main.py
```
Project CCREDITS : Github(kaymen99)


