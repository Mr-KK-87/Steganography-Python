# Steganography-python

# Stego.py - Secure Data Hiding in Image Using Steganography

## Overview
Stego.py is a Python script that implements a simple form of image steganography. It allows users to hide a secret message within an image and retrieve it later using a passcode.

## Problem Statement
With the growing need for secure communication, traditional encryption methods are sometimes not sufficient in protecting sensitive information. This project aims to implement a simple yet effective steganographic technique to hide messages within images, providing an additional layer of security. The challenge is to ensure that the hidden message is difficult to detect while maintaining the quality of the original image.

## Features
- Encrypts a text message into an image by modifying pixel values.
- Uses a simple dictionary-based mapping for encoding characters.
- Requires a passcode to decrypt and retrieve the hidden message.
- Works with OpenCV for image processing.

## Prerequisites
Make sure you have the following dependencies installed:

```bash
pip install opencv-python

Usage

Encryption

Replace Snapchat-948582984.jpg in the script with the path to your desired image.

Run the script:

1.python Stego.py
2.Enter the secret message when prompted.
3.Set a passcode for encryption.

The script generates an encryptedImage.jpg containing the hidden message.

Decryption

Run the script again:

1.python Stego.py
2.Enter the passcode used during encryption.
3.If the passcode matches, the hidden message is displayed.

Notes

1.The script modifies pixel values based on character ASCII values.
2.The encoding method is basic and not suitable for secure cryptographic applications.
3.Works best with uncompressed image formats like PNG.

Limitations

1.The encoding scheme is basic and can be improved.
2.The message length should not exceed the number of available pixels.
3.Color distortions may occur in images with complex structures.

Future Enhancements

1.Improve encryption using a more robust encoding technique.
2.Support larger messages with better pixel distribution.
3.Implement a graphical user interface (GUI).

License

This project is open-source and available for modification and enhancement.
