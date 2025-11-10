Image Encryption Tool
A Python-based GUI application for encrypting and decrypting images using simple techniques like XOR and pixel swapping. This tool is designed for educational and experimental purposes, offering a hands-on way to explore basic image obfuscation methods.
Features
 XOR encryption with a user-defined numeric key
 Pixel swapping for visual scrambling
 Reversible transformations for both encryption and decryption
 Simple and intuitive graphical user interface (GUI)
 Supports common image formats: JPG, PNG, BMP
Requirements
 Python 3.x
 Required libraries:
pip install pillow numpy


How to Use
 Run the script:
python image_encryption_tool.py
 Use the "Browse" button to select an image file.
 Choose an encryption method:
 xor: Requires a numeric key input.
 swap: No key required.
 Enter a key if using the XOR method.
 Click "Encrypt" or "Decrypt" to process the image.
 The output image will be saved in the same directory with a suffix _encrypt.png or _decrypt.png.
