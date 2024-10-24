# Email Validation Script

This repository, **Email_Validator_project**, contains a Python script that validates an email address based on several criteria, ensuring that the email format adheres to common email standards. This script can be useful in applications where input email validation is necessary.

## Features

- Checks for the presence of exactly one `@` symbol.
- Ensures that the email does not start with `-` or `@`.
- Verifies that there are no consecutive punctuation marks (`!!`).
- Confirms that the domain part contains at least one `.`.
- Ensures the local part of the email is no more than 64 characters long.
- Restricts `_` in the domain part.
- Validates that the local part contains only allowed alphanumeric and special characters.
- Ensures that the domain part contains only alphanumeric characters and dots.
- Checks for a valid top-level domain (TLD) at the end of the domain part.
- Ensures that the total length of the email does not exceed 254 characters.
- Verifies that the `@` symbol is more than 6 characters from the end of the email.
- Disallows spaces in the email address.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/RAKESH-564/Email_Validator_project.git
