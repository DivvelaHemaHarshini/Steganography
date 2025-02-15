<h1>SECURE DATA HIDING IN IMAGES USING STEGANOGRAPHY</h1>
This project implements a simple image-based text encryption and decryption technique using OpenCV in Python. The program hides a secret message within an image by modifying pixel values and allows retrieval using a passcode.

<h2>Features:</h2>
1.Encrypts a secret message into an image by embedding ASCII values into pixel data.
2.Uses a passcode-based authentication system for decryption.
3.Saves the encrypted image for later retrieval.
4.Extracts and decrypts the hidden message from the image.

<h2>Prerequisites:</h2>
1.Python 3.x
2.OpenCV (cv2)

<h2>Procedure:</h2>
1.Run the python file
2.Enter the secret message and passcode for encryption.
3.The encrypted image (encryptedImage.jpg) will be generated.
4.Enter the correct passcode to retrieve the hidden message.

<h2>Note</h2>
1.Ensure that the image used has enough pixel data to store the message.
2.If the wrong passcode is entered, access to the message is denied.
