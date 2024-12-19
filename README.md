# Inverso Apollo Server
The Apollo Server for Inverso is the middleware used in between the Next.js client and all the microservices related to our domain.

# Configuration
You'll need a `.env` file with the following variables configured:
```
CLOUD_INSTANCE="https://login.microsoftonline.com/" # cloud instance string should end with a trailing slash
TENANT_ID="the tenant id"
CLIENT_ID="the application id"
CLIENT_SECRET="the application secret's value"

REDIRECT_URI="https://example.com/auth/"
POST_LOGOUT_REDIRECT_URI="http://example.com"

# SQL Server
SQL_SERVER=xx.xx.xx.xxx
SQL_SERVER_USR="username"
SQL_SERVER_PWD="password"
```

# Documentation
TODO