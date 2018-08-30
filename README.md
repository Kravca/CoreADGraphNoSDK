# CoreADGraphNoSDK
This project demonstrates:
1. How to acquire access token for calling Azure AD Graph as an Application
2. How to call Azure AD Graph without using SDK (direct API)
3. How to ask Admin Consent for Application


# Setup Process
1. Create new Azure AD Application
  * Set it to be multi-tenant
  * Make a note of Application ID
  * Create and make a note of Secret
  * Adjust Application Permissions at "Required permissions -> Windows Azure Active Directory"
  * You might need 2 ReplyUrls set, one as a homepage, f.e., "https://localhost:44360/" and other "https://localhost:44360/signin-oidc"
2. Download this project and adjust settings with your values
3. Let the user from external Azure Directory login to app (reason it's multi-tenant)
4. User can provide consent with admin account
5. Your app can do calls to user's Azure AD through AD Graph 
