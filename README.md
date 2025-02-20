# steneography
Introduction

Steganography is the practice of concealing information within digital media to ensure secure communication. This project implements Least Significant Bit (LSB) Steganography to embed secret messages within images while maintaining visual integrity.

Features

Secure Data Hiding: Uses LSB technique to hide information in images.

Encryption Support: Encrypts the message before embedding for added security.

User-Friendly Interface: Simple CLI/GUI for encoding and decoding messages.

Supports Multiple Image Formats: Works with PNG, JPEG, and BMP files.

Technologies Used

Programming Language: Python

Libraries: OpenCV, NumPy, PIL (Pillow), Cryptography

Algorithm: Least Significant Bit (LSB) Steganography

Installation

Clone the repository:

git clone https://github.com/shivam95072/steganography-project.git
cd steganography-project

Install dependencies:

pip install -r requirements.txt

Usage

Encoding a Message into an Image

python encode.py --image input.png --message "Secret Message" --output stego_image.png

Decoding a Message from an Image

python decode.py --image stego_image.png

Example Output (Terminal)

[+] Loading image: input.png
[+] Encoding secret message...
[✓] Data successfully embedded!

[+] Loading stego image: stego_image.png
[+] Extracting hidden data...
[✓] Extracted Message: "Hello, this is a secret!"

Future Scope

Implement AI-based steganalysis resistance techniques.

Extend support to audio and video steganography.

Improve embedding efficiency for larger data capacity.

Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome!

License

This project is licensed under the MIT License.

Contact

For any questions or suggestions, feel free to reach out!

