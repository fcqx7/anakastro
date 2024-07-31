# JWT Generator

This project is designed to generate JSON Web Tokens (JWTs) using a Python script and GitHub Actions. The script creates a temporary email address, requests an OTP, confirms the OTP, creates a user, and retrieves a JWT which is then saved to a file called `bearer.txt`.

## Features

- Generates a temporary email address.
- Requests and confirms an OTP.
- Creates a user with the temporary email.
- Retrieves and saves a JWT to `bearer.txt`.
- Runs every hour using GitHub Actions.

## Requirements

- Python 3.11
