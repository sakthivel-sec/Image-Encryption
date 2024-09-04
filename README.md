# Image Encryption Tool

This Python program implements a simple image encryption and decryption tool using pixel manipulation. The tool allows users to encrypt images by altering pixel values using a specified key and then decrypt those images using the same key.

## Features
- Encrypts images by applying a mathematical operation to each pixel value.
- Decrypt images by reversing the operation using the same key.
- Supports images in PNG format.

## Usage

1. Clone the repository
   git clone https://github.com/your-username/Image-Encryption.git
2. Navigate to the project directory
   cd Image-Encryption
3. Install required dependencies
   pip install Pillow numpy
4. Run the program
   python image_encryption.py
5. Follow the on-screen prompts to encrypt or decrypt an image.

## Example

Encrypt an image:
  Choose mode ('encrypt' or 'decrypt'): encrypt Enter the path to the image file: path/to/image.png Enter an integer key for 
  encryption/decryption: 123 Image encrypted and saved as encrypted_image.png
Decrypt an image:
  Choose mode ('encrypt' or 'decrypt'): decrypt Enter the path to the image file: path/to/encrypted_image.png Enter an integer key for 
  encryption/decryption: 123 Image decrypted and saved as decrypted_image.png

