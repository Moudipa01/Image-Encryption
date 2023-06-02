# Image Encryption using Secret Sharing

Image Encryption using Secret Sharing is a project that aims to secure images by encrypting them using secret sharing techniques. This readme file provides an overview of the project, including its features, installation instructions, and usage guidelines.

## Features

The Image Encryption using Secret Sharing project offers the following features:

1. **Image Encryption:** The system utilizes secret sharing techniques to encrypt images securely. It divides the image into multiple shares, ensuring that the original image cannot be reconstructed without the required threshold of shares.

2. **Secret Sharing:** The project employs secret sharing algorithms to distribute the shares among different entities or participants. This approach ensures that no single entity has access to the complete image, enhancing security and privacy.

3. **Threshold Decryption:** To decrypt the encrypted image and obtain the original image, a minimum threshold of shares is required. This mechanism adds an extra layer of security, as multiple entities must collaborate to decrypt the image successfully.

4. **User-Friendly Interface:** The system provides a user-friendly interface for encrypting and decrypting images. Users can easily select an image, set the encryption parameters, and perform the encryption process. Similarly, the decryption process allows users to input the required shares and reconstruct the original image.

## System Requirements

To run the Image Encryption using Secret Sharing project, ensure that you have the following software and libraries installed:

1. [Python](https://www.python.org/downloads/) (Version 3.x or above)
2. [OpenCV](https://pypi.org/project/opencv-python/) (Python library for image processing)
3. [NumPy](https://pypi.org/project/numpy/) (Python library for numerical operations)

## Installation and Setup

Follow these steps to install and set up the Image Encryption using Secret Sharing project:

1. Clone or download the project files from the repository.
2. Install Python on your system by downloading it from the official Python website and following the installation instructions.
3. Install the required libraries by running the following command:
   ```
   pip install opencv-python numpy
   ```
4. Once the dependencies are installed, you are ready to use the project.

## Usage

To encrypt an image using secret sharing:

1. Place the image file in the project directory or provide the complete path to the image file.
2. Open the terminal or command prompt and navigate to the project directory.
3. Run the encryption script using the following command:
   ```
   python encrypt.py
   ```
4. Follow the instructions on the terminal to set the encryption parameters, such as the number of shares and the threshold for decryption.
5. After the encryption process is complete, the shares will be generated and saved in the project directory.

To decrypt the encrypted shares and obtain the original image:

1. Open the terminal or command prompt and navigate to the project directory.
2. Run the decryption script using the following command:
   ```
   python decrypt.py
   ```
3. Follow the instructions on the terminal to input the required shares for decryption.
4. After providing the shares, the system will reconstruct the original image and save it in the project directory.

Note: Ensure that the number of shares provided during decryption meets the threshold requirement set during encryption.

## Contributors

The Image Encryption using Secret Sharing project was developed by [Moudipa Jana].I welcome any feedback, suggestions, or contributions to enhance the project. You can reach me at [moudipa.jana2020@vitstudent.ac.in].
