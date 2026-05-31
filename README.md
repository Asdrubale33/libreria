# Home Library Manager

A lightweight, web-based application designed to help you organize and catalog your personal book collection from any device.

## 🚀 Features

*   **Single-File Architecture:** The entire application is contained within a single HTML file for maximum portability and easy hosting.
*   **Digital Catalog:** Keep track of all your books in one centralized place.
*   **Barcode Scanner:** Easily add new books by scanning their barcodes using your smartphone or desktop webcam, powered by `html5-qrcode`.
*   **Responsive Design:** Fully optimized for both desktop and mobile web browsers.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3, JavaScript (All-in-one file)
*   **Libraries:** [html5-qrcode](https://github.com/mebjas/html5-qrcode) (Embedded for barcode scanning)

## 📦 How to Run it Locally

Since this is a fully self-contained client-side application, running it is incredibly simple:

1. Clone or download this repository.
2. Open the `.html` file directly in your desktop browser.

> ⚠️ **Important Note for Mobile Users:** 
> Modern mobile browsers restrict camera access to secure contexts only. To test the barcode scanner on your smartphone, the project must be hosted via **HTTPS** (e.g., using GitHub Pages) or run through a local server tunnel (`localhost`).

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
