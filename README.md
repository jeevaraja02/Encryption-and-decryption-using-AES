# Secure File Encryption and Decryption Using AES

This project implements a secure file encryption and decryption system using Python and symmetric key cryptography.

## Features
- Encrypt files using a secret key
- Decrypt encrypted files using the same key
- Generate and store a secret key
- Protect sensitive file contents from unauthorized access

## Technologies Used
- Python 3
- Cryptography Library
- AES/Fernet Symmetric Encryption

## Installation
pip install cryptography

## Run
python secure_file.py

## Working
1. Select Encrypt File.
2. Enter the file name.
3. The file is encrypted and saved as `.enc`.
4. Select Decrypt File.
5. Enter the encrypted file name.
6. The original file is restored using the secret key.
