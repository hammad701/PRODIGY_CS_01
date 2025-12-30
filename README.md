# Caesar Cipher Python Program

This is a simple Python program that implements the Caesar Cipher encryption and decryption algorithm. Users can encrypt or decrypt messages by providing a text and a shift value.

## Features

- Encrypt a message using a Caesar Cipher with a custom shift value.
- Decrypt a message using the same shift value.
- Preserves uppercase and lowercase letters.
- Non-alphabetic characters (numbers, spaces, punctuation) remain unchanged.
- Interactive menu that allows multiple encryptions/decryptions until the user chooses to quit.

## How to Use

1. Clone this repository or download the Python file.
2. Run the program using Python 3:

```bash
python caesar_cipher.py

    Follow the interactive prompts:

    Choose (E)ncrypt to encrypt a message.

    Choose (D)ecrypt to decrypt a message.

    Choose (Q)uit to exit the program.

    Enter your message and shift value when prompted.

Example

Do you want to (E)ncrypt, (D)ecrypt, or (Q)uit? E
Enter your message: Hello World!
Enter shift value (number): 3
Encrypted message: Khoor Zruog!

Notes

    Decrypting a message is simply encrypting it with the negative of the shift value.

    Shift values larger than 26 or negative numbers are supported, and the program correctly wraps around the alphabet.

License

This project is licensed under the MIT License.
