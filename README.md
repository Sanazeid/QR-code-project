# 📱 QR Code Generator – Node.js Practice Project
This is a simple Node.js command-line tool that takes a user-provided URL, generates a QR code from it, and saves both the QR image and the original URL to files.


## 📌 Features

- Prompts the user to enter a URL (using `inquirer`)
- Generates a QR code as a PNG image (`qr-image`)
- Saves the QR code as `qr_img.png`
- Saves the URL to a file named `message.txt`

## 🧰 Technologies Used

- [Node.js](https://nodejs.org/)
- [`inquirer`](https://www.npmjs.com/package/inquirer)
- [`qr-image`](https://www.npmjs.com/package/qr-image)
- Built-in `fs` module
