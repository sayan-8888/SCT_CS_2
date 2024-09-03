AUTHOR - SAYAN CHAKRABORTY.
Description
A Python script that encrypts and decrypts images using a basic XOR operation on pixel color values.
Explanation
This script allows users to encrypt an image by applying an XOR operation on each pixel's RGB values using a specified key. The encrypted image can then be saved and later decrypted by reversing the XOR operation with the same key. The program utilizes the Python Imaging Library (PIL) to manipulate image data and supports optional pixel swapping to add further obfuscation.

EXAMPLE CODE INPUT & OUTPUT 
1)Install the required library using pip 
pip install pillow 
2)Place your input image (Fruits.jpg) in the same directory. 
3)Run the script:python image_encryption.py The script will generate an encrypted_image.png and a decrypted_image.png. 
The encrypted image will look different from the original due to pixel manipulation, but the decrypted image should be visually identical to the original.
