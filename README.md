# Secure Password Generator

This project is a Python-based secure password generator. It generates random passwords using a combination of uppercase and lowercase letters, numbers, and special characters.

## Features

- Generate secure random passwords with customizable length.
- Use alphanumeric characters and symbols for enhanced security.

## Prerequisites

This project requires Python 3.x and the `string` library, which is included by default in Python. There are no external dependencies to install.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/kyuremww/secure-password-generator.git
    ```

2. Navigate to the project folder:
    ```bash
    cd secure-password-generator
    ```

3. Run the Python script to generate a password:
    ```bash
    python generate_password.py
    ```

## Usage

You can customize the password length by modifying the `length` argument in the `generate_password()` function.

Example usage to generate a 16-character password:
```python
password = generate_password(16)
print(f"Generated password: {password}")
