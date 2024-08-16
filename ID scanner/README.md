# Encrypted QR Code Scanner

## Overview

The Encrypted QR Code Scanner is a simple web application designed to decrypt encrypted text embedded within QR codes. This application is especially useful for securely transmitting data that can only be accessed by users who have the correct encryption key. The primary purpose of this tool is to safely decode data from QR codes and verify identification details.

## Features

- **Real-Time QR Code Scanning**: The application allows you to scan QR codes in real-time using your device's camera.
- **Decryption Capability**: After scanning, the encrypted data from the QR code can be decrypted using a provided encryption key.
- **User-Friendly Interface**: The application features a simple and intuitive interface, making it easy to scan and decrypt QR codes.

## Usage

1. **Start the Scanner**: Click on the "Start Scanner" button to begin scanning QR codes. The application will use your device's camera to detect and scan QR codes in real-time.
2. **Scan a QR Code**: Position the QR code within the camera's view. The application will automatically detect and scan the code.
3. **Decrypt the Data**: Once a QR code is scanned, enter the encryption key into the provided input field and click "Decrypt" to reveal the decrypted data.
4. **View Decrypted Data**: The decrypted information will be displayed on the screen. Ensure that the correct encryption key is used to successfully decrypt the data.

## Technical Details

- **HTML5 QR Code Library**: The application uses the `html5-qrcode` library for scanning QR codes directly from the web browser.
- **CryptoJS**: The `CryptoJS` library is utilized for decrypting the AES-encrypted text retrieved from the QR codes.
- **Responsive Design**: The interface is designed to be responsive and works well across different devices, including desktops, tablets, and smartphones.

## Installation

This project is a single HTML file that can be run in any modern web browser.

1. Clone or download the repository.
2. Open `id scan.html` in your preferred web browser.
3. Use the application directly from your browser without any additional setup.

## License

This project is licensed under the MIT License with specific conditions. Please refer to the LICENSE file for more details.

## Acknowledgments

- [html5-qrcode](https://github.com/mebjas/html5-qrcode) for providing the QR code scanning functionality.
- [CryptoJS](https://github.com/brix/crypto-js) for enabling AES decryption within the browser.
