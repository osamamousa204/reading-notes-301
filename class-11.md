# Using the API

Authorizing requests and identifying your application
Every request your application sends to the Books API needs to identify your application to Google. There are two ways to identify your application: using an OAuth 2.0 token (which also authorizes the request) and/or using the application's API key. Here's how to determine which of those options to use:

* If the request requires authorization (such as a request for an individual's private data), then the application must provide an OAuth 2.0 token with the request. The application may also provide the API key, but it doesn't have to.
* If the request doesn't require authorization (such as a request for public data), then the application must provide either the API key or an OAuth 2.0 token, or both—whatever option is most convenient for you.

Authorizing requests with OAuth 2.0
Requests to the Books API for non-public user data must be authorized by an authenticated user.

The details of the authorization process, or "flow," for OAuth 2.0 vary somewhat depending on what kind of application you're writing. The following general process applies to all application types:

1. When you create your application, you register it using the Google API Console. Google then provides information you'll need later, such as a client ID and a client secret.
2. Activate the Books API in the Google API Console. (If the API isn't listed in the API Console, then skip this step.)
3. When your application needs access to user data, it asks Google for a particular scope of access.
4. Google displays a consent screen to the user, asking them to authorize your application to request some of their data.
5. If the user approves, then Google gives your application a short-lived access token.
6. Your application requests user data, attaching the access token to the request.
7. If Google determines that your request and the token are valid, it returns the requested data.


[Home Page](https://osamamousa204.github.io/reading-notes-301/)