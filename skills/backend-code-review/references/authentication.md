# Authentication and validation code review

In the routes file where the controllers are called, check for the following:

- The route is secured and requires user authentication and validation before being reached
- The validation method is secure and does not allow for security flaws
- Validation tokens have refresh token option to keep the user securely logged in
- Token blacklisting for any expired tokens