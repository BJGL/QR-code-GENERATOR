# QR Code Generator

This repository contains a simple Python script to generate QR code images from any text or URL input. It uses the [`qrcode`](https://pypi.org/project/qrcode/) library and includes basic input validation and error handling.

## Features

* Generates QR codes from text or links.
* Customizable QR color and background.
* Validates user input and adds default file extensions if needed.
* Saves the generated image to the current directory.

---

You will be prompted to enter:

1. The text or URL to encode.
2. The file name for the output image (e.g., `my_qr.png`).

Example:

```bash
--- Professional QR Code Generator ---
Enter the link or text to encode: https://www.example.com
What do you want to name the file? (e.g., my_qr.png): website_qr
Adding .png extension. Final name: 'website_qr.png'
Success! Your QR code has been saved as: 'website_qr.png'
├── qr_generator.py
└── README.md
```
