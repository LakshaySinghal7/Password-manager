# Password-manager
This Python script enables users to securely manage their passwords using encryption provided by the Fernet library from the cryptography module.

#Features
Add Passwords: Users can add new account names and passwords securely.

View Passwords: Existing account names and passwords can be viewed after decryption.

#Usage
Setup: Ensure dependencies are installed by running pip install cryptography.

Key Generation: Execute the write_key function within the script to generate a key file (key.key) for encryption and decryption.

Adding Passwords: Run the script and select the "add" option to input account names and passwords.

Viewing Passwords: Choose the "view" option to display existing account names and their decrypted passwords.

#Security Note

Safeguard the key.key file as it is essential for encryption and decryption. Losing this file may result in data loss or compromise.
