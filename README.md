# QR Code Generator 🧾

A simple and elegant web application that allows users to generate QR codes from custom input text and download them as image files.

> 🚀 [Live Demo](https://yateeshapappala.github.io/QR-Code-Generator/)

---

## ✨ Features

- ✅ Generate QR codes for any text or URL
- 🎯 Customizable size input
- 📥 One-click QR code download
- 🎨 Clean, responsive, and dark-themed UI
- ⚡ No backend required – fully client-side

---

## 🛠️ Built With

- **HTML5**
- **CSS3**
- **JavaScript**
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) (via CDN)
- [QR Code API by goqr.me](https://goqr.me/api/)

---

## 📂 How to Use

1. Open the [Live Demo](https://yateeshapappala.github.io/QR-Code-Generator/).
2. Enter the desired text (URL, name, etc.).
3. Enter the size (minimum: 30).
4. Click **Generate** to display the QR code.
5. Click **Download** to save the QR code image.

---

## 📁 Folder Structure

```plaintext
QR-Code-Generator/
├── qr.html           # Main HTML file
├── README.md         # This file
````

---

## 🌐 Deployment

Deployed using **GitHub Pages**
🔗 **Live Project:** [https://yateeshapappala.github.io/QR-Code-Generator/](https://yateeshapappala.github.io/QR-Code-Generator/)

---

## 🧩 API Info

QR Codes are generated using the open API from:

```
https://api.qrserver.com/v1/create-qr-code/?data=YOUR_DATA&size=WIDTHxHEIGHT
```
