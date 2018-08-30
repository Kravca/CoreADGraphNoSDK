# CoreADGraphNoSDK
This project demonstrates:
1. How to acquire access token for calling Azure AD Graph as an Application
2. How to call Azure AD Graph without using SDK (direct API)
3. How to ask Admin Consent for Application


Admin consent URL:

https://login.microsoftonline.com/{TenantID}/oauth2/authorize?client_id={AppClientID}&response_type=code&redirect_uri={AppRedirectURL}&nonce=1234&resource=https://graph.windows.net&prompt=admin_consent
