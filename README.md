# Image Encryption and Decryption

This project provides a Python script for encrypting and decrypting images using a simple algorithm. You can use this script to modify images by adjusting their pixel values based on a given key.

## Installation

1. Clone the repository:
   
    git clone https://github.com/Nabeelkallan/task2.git
  

2. Change into the project directory:

    cd task2

3. Create and activate a virtual environment:
   
    python -m venv venv
    venv\Scripts\activate
  

4. Install the required packages:
   
    pip install -r requirements.txt


## Usage

1. Run the script:
    
    python main.py
    

2. Follow the prompts to either encrypt or decrypt an image:
     Enter the path of the image you want to process.
     Specify the output path for the processed image.
     Provide an encryption key (a number).

## Example

To encrypt an image:

python main.py
Do you want to (E)ncrypt or (D)ecrypt an image? E
Enter the path of the image: C:\Users\LENOVO\Desktop\New folder\jeep.jpg
Enter the output path for the new image: C:\Users\LENOVO\Desktop\nk\Ejeep.jpg
Enter the encryption key (a number): 50


To decrypt an image:

python main.py
Do you want to (E)ncrypt or (D)ecrypt an image? D
Enter the path of the image: C:\Users\LENOVO\Desktop\nk\Ejeep.jpg
Enter the output path for the new image: C:\Users\LENOVO\Desktop\New folder\Djeep.jpg
Enter the encryption key (a number): 50

Notes

Ensure that the input paths are correct and that you have read/write permissions for the specified directories.
Adjust the encryption key as needed. Ensure the key used for decryption matches the one used for encryption to correctly recover the original image.
