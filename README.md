# Steganography
<h1>SECURE DATA HIDING IN IMAGES USING STEGANOGRAPHY</h1>
This project implements a simple image-based text encryption and decryption technique using OpenCV in Python. The program hides a secret message within an image by modifying pixel values and allows retrieval using a passcode.

<h2>Features:</h2>
Encrypts a secret message into an image by embedding ASCII values into pixel data.
Uses a passcode-based authentication system for decryption.
Saves the encrypted image for later retrieval.
Extracts and decrypts the hidden message from the image.

<h2>Prerequisites:</h2>
Python 3.x
OpenCV (cv2)

<h2>Procedure:</h2>
Run the python file
Enter the secret message and passcode for encryption.
The encrypted image (encryptedImage.jpg) will be generated.
Enter the correct passcode to retrieve the hidden message.

<h2>Note</h2>
Ensure that the image used has enough pixel data to store the message.
If the wrong passcode is entered, access to the message is denied.
