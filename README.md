# Pixel-Manipulation-For-Image-Encryption
Image Encryption Tool

Description :-

This Python application is a simple image encryption and decryption tool, built using the tkinter library for the graphical user interface and the PIL (Python Imaging Library) along with numpy for image manipulation. The tool allows users to securely encrypt and decrypt images using a key-based method, making it useful for protecting sensitive visual data.


Features :-

- User-Friendly Interface: An intuitive GUI for selecting images, entering keys, and performing encryption and decryption operations.

- Image Encryption: Encrypts images using a key-based XOR operation and a simple pixel swapping algorithm.

- Image Decryption: Decrypts images by reversing the encryption process.

- File Dialogs: Easy selection of input images and saving of output images through file dialogs.

- Key Validation: Ensures the key entered by the user is a valid number within the range of 0-255.


How It Works:-


Encryption:-

-Converts the image to an RGB format.

-Applies an XOR operation with the provided key to each pixel.

-Swaps pixel values in a simple pattern to add an additional layer of security.


Decryption:-

-Swaps pixel values back to their original positions.

-Applies an XOR operation with the same key to retrieve the original image.


Contributing:- Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


License:-This project is licensed under the MIT License. See the LICENSE file for more details.


