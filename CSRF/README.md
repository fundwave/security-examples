# Best Practices to prevent CSRF attacks

    - Use CSRF Tokens: Protect all forms and sensitive links with unique CSRF tokens that are verified on the server side.

    - Double Submit Cookies: Send CSRF tokens in a cookie and as a hidden form field to detect potential mismatches.

    - SameSite Cookies: Set cookies with the SameSite attribute to prevent them from being sent along with requests initiated by third-party sites.

    - Require User Authentication: Ensure CSRF tokens are tied to user sessions and require re-authentication for sensitive actions.

    - Limit Sensitive Actions: Limit sensitive operations to HTTP POST requests to reduce susceptibility to CSRF attacks.
