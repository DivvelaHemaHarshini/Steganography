<h1>SECURE DATA HIDING IN IMAGES USING STEGANOGRAPHY</h1>
This project implements a simple image-based text encryption and decryption technique using OpenCV in Python. The program hides a secret message within an image by modifying pixel values and allows retrieval using a passcode.

<h2>Features:</h2>
1.Encrypts a secret message into an image by embedding ASCII values into pixel data.</br>
2.Uses a passcode-based authentication system for decryption.</br>
3.Saves the encrypted image for later retrieval.</br>
4.Extracts and decrypts the hidden message from the image.</br>

<h2>Prerequisites:</h2></br>
1.Python 3.x</br>
2.OpenCV (cv2)</br>

<h2>Procedure:</h2></br>
1.Run the python file</br>
2.Enter the secret message and passcode for encryption.</br>
3.The encrypted image (encryptedImage.jpg) will be generated.</br>
4.Enter the correct passcode to retrieve the hidden message.</br>

<h2>Note</h2>
1.Ensure that the image used has enough pixel data to store the message.</br>
2.If the wrong passcode is entered, access to the message is denied.
