# Text Encryption/Decryption Tool

This is a simple web-based tool that allows you to encrypt and decrypt text using the AES (Advanced Encryption Standard) algorithm. AES is a widely used and secure encryption method. This tool adds an extra layer of security by performing AES encryption and Base64 encoding.

![Tool Preview]([tool-preview.png](https://github.com/swerce/AES-encrypt-and-decrypt/blob/main/Screenshot%202023-08-24%20234908.png))

## Table of Contents

- [Getting Started](#getting-started)
- [How It Works](#how-it-works)
- [How to Use](#how-to-use)
- [License](#license)

## Getting Started

To use the Text Encryption/Decryption Tool, simply open the provided HTML file in your web browser. Here's how:

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your web browser.

## How It Works

The tool uses the AES algorithm for both encryption and decryption. It also employs Base64 encoding to enhance security. Here's a breakdown of the process:

1. **Encryption:** Enter the text you want to protect and provide a strong encryption key. Click the "Encrypt" button, and the tool will perform AES encryption followed by Base64 encoding.

2. **Decryption:** To decrypt the text, enter the encrypted result along with the same encryption key used for encryption. Click the "Decrypt" button, and the tool will reverse the encryption process to reveal the original text.

Please note that the security of the encryption relies on keeping the encryption key secure.

## How to Use

1. Enter the text you want to encrypt in the "Enter your text" field.
2. Provide a strong encryption key in the "Encryption Key" field. Keep this key secure.
3. Click the "Encrypt" button to encrypt the text. The encrypted result will appear in the "Result" textarea.
4. To decrypt, paste the encrypted result into the "Result" textarea and provide the encryption key.
5. Click the "Decrypt" button to reveal the original text.

Remember that losing the encryption key could lead to data loss, so keep it safe.

## License

This project is licensed under the [MIT License](LICENSE).
