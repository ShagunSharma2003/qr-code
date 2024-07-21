
# QR Code Generator 

## Overview

This project is a simple web-based QR code generator. It allows users to input text or a URL and generates a corresponding QR code. The generated QR code is then displayed on the page for the user to scan.
![image](https://github.com/user-attachments/assets/44b5334b-5e29-4715-8031-35b39c4b0ac9)

## Features

- **Text/URL Input:** Users can enter any text or URL to generate a QR code.
- **QR Code Generation:** The application uses an external API to create the QR code based on the user's input.
- **Error Handling:** If the input field is empty, the input box will briefly shake to indicate an error.

## Technologies Used

- **HTML5:** For the basic structure of the web page.
- **CSS3:** For styling the web page and making it visually appealing.
- **JavaScript:** For handling the QR code generation logic.
- **QR Code API:** The application utilizes the `api.qrserver.com` API to generate QR codes.

## Installation and Usage

1. **Download or Clone the Repository:**
   ```sh
   git clone https://github.com/ShagunSharma2003/qrcode-generator.git
   ```

2. **Navigate to the Project Directory:**
   ```sh
   cd qrcode-generator
   ```

3. **Open `index.html` in a Web Browser:**
   You can simply double-click on the `index.html` file or open it using your preferred web browser.

## How to Use

1. **Enter Text or URL:**
   - In the input field labeled "Enter your text or url", type the text or URL you wish to convert into a QR code.

2. **Generate QR Code:**
   - Click the "Generate QR code" button. If the input field is empty, it will shake to indicate that you need to enter some text or a URL.

3. **View QR Code:**
   - The generated QR code will be displayed below the input field.

## File Structure

- `index.html`: The main HTML file that structures the web page.
- `style.css`: The CSS file for styling the web page.
- `script.js`: The JavaScript file containing the logic for generating the QR code.

## Acknowledgements

- This project uses the [QR Code API](https://api.qrserver.com/) for generating QR codes.

**Contact Information:**

- **Author:** Shagun Sharma
- **Email:** sharma.diva193@gmail.com
---

Thank you for using the QR Code Generator Web Application!
