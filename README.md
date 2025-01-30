# Secure-Image-Steganography-with-Cryptography  
This project implements a **secure image steganography** system combined with **AES encryption** to hide and extract messages within images. The **F5 algorithm** is used for efficient steganographic embedding, ensuring minimal visual distortion while maintaining security.  

## Features  
- **AES Encryption & Decryption** for secure message protection  
- **F5 Algorithm** for embedding encrypted messages into images  
- **User Authentication** to manage access control  
- **Image Upload & Processing** with multiple formats supported  
- **Steganographic Extraction** to retrieve hidden messages  

## Tech Stack  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js  
- **Database:** MySQL  
- **Security:** AES Encryption, Diffie-Hellman Key Exchange  
- **Steganography:** F5 Algorithm  

## Screenshots  

### Home Page  
The home page provides two main options: **Encrypt Image** and **Decrypt Image** to process steganographic data securely.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/4709513d-d658-4895-8311-a45546bd88ae" alt="Home Page - Encrypt & Decrypt Options" width="800">
</p>  

### 🔒 Encryption Process  
In the encryption section, the user uploads an image and a message. The system **encrypts** the message and **embeds** it within the image using the F5 algorithm.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/44072412-599c-44f3-966c-0913cb49ac73" alt="Encryption - Upload Image & Message" width="800">
</p>  

### 🔓 Decryption Process  
In the decryption section, the user provides a **stego-image** (image with hidden data). The system extracts the hidden data and **decrypts** the message for the user.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/dcc869e9-cca3-4581-add3-2b37d6626eb1" alt="Decryption - Extract & Decrypt Message" width="800">
</p>  

<p align="center">
  <img src="https://github.com/user-attachments/assets/97d14a17-9a9b-4962-a1fa-5b566ca2a836" alt="Decryption - Extract & Decrypt Message" width="800">
</p>  
