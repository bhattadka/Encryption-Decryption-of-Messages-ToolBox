# Encryption-Decryption-of-Messages-ToolBox

## Overview

Encryption-Decryption of Messages ToolBox is a simple encryption and decryption tool built using Python and Tkinter. It allows users to securely encrypt and decrypt messages using a secret key. This project uses base64 encoding for encryption and decryption of messages.

## Files

### 1. `main.py`

This is the main file that contains the entire code for the application.

#### Functionality
- **Encrypt:** Encodes the input message using base64 encoding.
- **Decrypt:** Decodes the encrypted message back to its original form.
- **Reset:** Clears the input fields for a new message.

#### Algorithm
- **Encryption:**
  1. Retrieve the input message.
  2. Convert the message to ASCII.
  3. Encode the ASCII message using base64 encoding.
  4. Display the encrypted message in a new window.

- **Decryption:**
  1. Retrieve the encrypted message.
  2. Convert the encrypted message to ASCII.
  3. Decode the base64 encoded message.
  4. Display the decrypted message in a new window.

#### Extreme Cases
- If the input message is empty, the application will still perform the encryption/decryption but the result will be an empty string.
- If the secret key is incorrect, an error message will be displayed.

### 2. Images Folder

This folder contains the images used in the application:
- `key.png`: Used as the icon for the main window.
- `encrypt.png`: Encrypted message output image
- `decrypt.png`: Decrypted message output image

### 3. Interface Image

An image showing the interface of the application.


