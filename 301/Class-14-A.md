# What is OAuth

## What is OAuth?
OAuth is an open-standard authorization protocol or framework that describes how different unrelated servers can allow authenticated to access assets without sharing the credentials.
## Give an example of what using OAuth would look like.
When a user try to login to a website. The website shows the user options of websites to log in from.when the user click on one of the websites offered by the original website the user will then authenticated from the that website he cliked on and directly the original website will login the user to itself.  
## How does OAuth work? What are the steps that it takes to authenticate the user?
* The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

* The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
  
* The first site gives this token and secret to the initiating user’s client software (browser).
  
* The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
* If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
* The user approves (or their software silently approves) a particular transaction type at the first website.
* The user is given an approved access token (notice it’s no longer a request token).
* The user gives the approved access token to the first website.
* The first website gives the access token to the second website as proof of authentication on behalf of the user.
* The second website lets the first website access their site on behalf of the user.
The user sees a successfully completed transaction occurring.
## What is OpenID?
OpenID is about authentication (ie. proving who you are), OAuth is about authorisation (ie. to grant access to functionality/data/etc.. without having to deal with the original authentication).


# Authorization and Authentication flows

## What is the difference between authorization and authentication?

* Authentication confirms that users are who they say they are.
* Authorization gives those users permission to access a resource.
## What is Authorization Code Flow?
Authorization code flow is exchanging an Authorization Code for a token in case your app is a server side app.
## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
Authorization Code Flow with Proof Key for Code Exchange is an enhanced version of Authorization Code Flow used in Single-page apps and native apps. in the case of single-page app it can not securely store a Client Secret because their entire source is available to the browser.

* calling app creates a secret called Code Verifier.
* calling app creates a transformed value of Code Verifier called Code challenge .
* calling app sends Code challenge over Https.
* in this case even the attacker can capture the authorization code ,he will not be able to exchange it without the Code Verifier.

## What is Implicit Flow with Form Post?
As an alternative to the Authorization Code Flow which is intended for Public Clients, or applications which are unable to securely store Client Secrets and in some cases where the the application just need sign in and it do not care about managing secrets.

## What is Client Credentials Flow?

When Machine app connects with other machine app the traditional authentication using credentials like username and password do not make sence. in this case the system uses Client Credentials Flow to authenticates and authorizes the apps rather than users.
## What is Device Authorization Flow? 
It is an authorization process to authorize the connected device rather than authenticate the user.

## What is Resource Owner Password Flow?
Resource Owner Password Flow is an a process which requests that users provide credentials (username and password), typically using an interactive form.These credentials are stored on a server for future uses and.
Even if the app is trusted with these credentials, the Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.

## Things I want to know more about

I want to know more about the vulnerabilities that exists in OAuth.

### References

[What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
[Authorization and Authentication flows](https://auth0.com/docs/flows)