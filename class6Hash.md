# Securing Passwords

## Explain to a non-technical friend how you would safely hash and store a password.

To safely hash and store a password, you would use a strong cryptographic algorithm like bcrypt and store the hashed password along with a randomly generated salt. This ensures that even if the database is compromised, the passwords remain secure.

## What is Bcrypt?

Bcrypt is a cryptographic hashing function designed for password hashing. It's slow and includes a salt and multiple rounds of hashing for added security.

## Why might you use something like Bcrypt?

Bcrypt is used for password hashing because it's slow, making brute-force attacks difficult. It handles salt generation automatically, ensuring unique hashes even for the same passwords.

# Basic Auth

## What is Basic Authentication?

Basic Authentication is an HTTP authentication scheme where the client sends the username and password in the "Authorization" header. The server validates these credentials.

## What properties are necessary in the header of a Basic Auth request?

In the "Authorization" header of a Basic Auth request, these properties are necessary:
- Scheme: "Basic"
- Credentials: Username and password encoded in Base64 format.

## How are username:password in Basic Auth encoded?

To encode the username and password in Basic Auth:
1. Concatenate the username and password with a colon (e.g., "username:password").
2. Convert the resulting string to Base64 encoding.
3. Prepend the encoded string with "Basic" followed by a space.

# [OWASP Authentication Cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

## Define the authentication process to a non-technical recruiter.

The authentication process:
1. User provides credentials (username and password) through a login form.
2. Server compares credentials to the stored, hashed password.
3. If valid, the server generates a session token and sends it back to the client.
4. The client includes the session token in subsequent requests.
5. The server verifies the session token and grants access if valid.

## How should your error messaging respond (both HTTP and HTML)? Why?
For authentication failures:
- HTTP: Respond with status code 401 (Unauthorized).
- HTML: Display an error message indicating incorrect credentials.
Clear error messaging helps users understand the issue and improves security by not revealing too much information.


 ### return to [Main Read Me File](./README.md)