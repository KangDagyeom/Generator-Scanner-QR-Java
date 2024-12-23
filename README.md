# Java QR Code Generator and Scanner
## Overview 💨
![Static Badge](https://img.shields.io/badge/Java-Learn-%23ff6f00)
<a href="https://github.com/KangDagyeom/Generator-Scanner-QR-Java/stargazers"><img src="https://img.shields.io/github/stars/KangDagyeom/Generator-Scanner-QR-Java" alt="Stars Badge"/></a>
<a href="https://github.com/KangDagyeom/Generator-Scanner-QR-Java/network/members"><img src="https://img.shields.io/github/forks/KangDagyeom/Generator-Scanner-QR-Java" alt="Forks Badge"/></a>
<a href="https://github.com/KangDagyeom/Generator-Scanner-QR-Java/pulls"><img src="https://img.shields.io/github/issues-pr/KangDagyeom/Generator-Scanner-QR-Java" alt="Pull Requests Badge"/></a>
<a href="https://github.com/KangDagyeom/Generator-Scanner-QR-Java/issues"><img src="https://img.shields.io/github/issues/KangDagyeom/Generator-Scanner-QR-Java" alt="Issues Badge"/></a>
<a href="https://github.com/KangDagyeom/Generator-Scanner-QR-Java/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/KangDagyeom/Generator-Scanner-QR-Java?color=2b9348"></a>
<a href="https://github.com/KangDagyeom/Generator-Scanner-QR-Java/blob/master/LICENSE"><img src="https://img.shields.io/github/license/KangDagyeom/Generator-Scanner-QR-Java?color=2b9348" alt="License Badge"/></a>

This is a Java-based application that allows users to generate QR codes from custom text and decode (read) QR codes from image files. The application leverages the ZXing library for QR code handling and provides a simple GUI for interaction.

## Features ✨

- Generate QR Codes: Enter any text and create a QR code image file.
- Read QR Codes: Upload a QR code image and decode its content.
- User-Friendly Interface: Simple GUI built using javax.swing.

## Getting Started 🌟
Prerequisites
Ensure you have the following installed on your system:
```
Java Development Kit (JDK) 8 or later
An IDE (e.g., NetBeans, IntelliJ IDEA, Eclipse)
```

## Libraries Used 📚
The project uses the following libraries:
```
ZXing Core (zxing-core-1.7.jar): Provides core functionality for QR code generation and decoding.
ZXing Java SE (zxing-j2se-1.7.jar): Adds utilities for working with images in Java.
QRGen (qrgen-1.0.jar): Simplifies QR code generation.
Barcode (barcode.jar): (Optional) Useful for working with other barcode types.
```
**You can find the libraries in the libs/ folder of the project or download them from their respective sources.**

## Setup and Installation 🔽
Clone the repository:
```
git clone https://github.com/KangDaGyeom/Generator-Scanner-QR-Java.git
```
Import the project into your favorite IDE. 

Add the required libraries (.jar files) to the project's classpath:

In NetBeans: Right-click the project > Properties > Libraries > Add JAR/Folder.
In Eclipse: Right-click the project > Build Path > Add External Archives.

Run the application:
Locate the Main class in the src folder.

Run the Main class.
Usage
1. Generating QR Codes
Enter the text you want to encode in the text field.
Click the Write button.
The application saves the generated QR code as a PNG file in the specified directory.

![WriteQR](images/writeqr.png)

3. Reading QR Codes
Click the Browse button and select a QR code image file.
Click the Scan button.
The application displays the decoded text from the QR code.

![files](images/file.png)

![Scanqr](images/scanqr.png)

## Directory Structure 🔰
```
Generator-Scanner-QR-Java/
│
├── src/                     # Source code
│   ├── Main.java            # Entry point of the application
│
├── libs/                    # Required libraries
│   ├── zxing-core-1.7.jar
│   ├── zxing-j2se-1.7.jar
│   ├── qrgen-1.0.jar
│   └── barcode.jar
│
└── README.md                # Project documentation
```

## Built With 🧔
Java SE: Core programming language.
ZXing: Library for QR code generation and decoding.
Swing: Used for building the graphical user interface.

## Known Issues 🚩
The application may fail to decode low-resolution or corrupted QR code images.
Ensure the file path for saving QR codes is valid and writable.

## Contributing 🙌
Fork the repository.
Create your feature branch:
```
git checkout -b feature/YourFeature
```
Commit your changes:
```
git commit -m "Add YourFeature"
```
Push to the branch:
```
git push origin feature/YourFeature
```
**Open a pull request.**

## License 🛑
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments 💫
ZXing Team: For providing a robust library for QR code handling.
QRGen: For simplifying QR code generation.
Inspired by various open-source QR code tools.
