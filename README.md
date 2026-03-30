### Network Security Projects for Phising Data
# Network Security using End-to-End Encryption

## Project Overview
This project is based on network security using End-to-End Encryption (E2EE). The main aim of this project is to provide secure communication between two users so that no third party, including the server, can read the data.

In this system, the message is encrypted at the sender side and decrypted only at the receiver side.

---

## Objectives
- To implement secure communication
- To protect data from unauthorized access
- To ensure confidentiality and integrity of data
- To prevent man-in-the-middle attacks

---

## Features
- End-to-End Encryption
- Public and Private Key Cryptography
- Secure data transmission
- Data integrity using hashing

---

## System Working

1. The sender writes a message.
2. The message is encrypted using the receiver's public key.
3. The encrypted message is sent through the server.
4. The server only forwards the message and cannot read it.
5. The receiver decrypts the message using their private key.

---

## Technologies Used
- Programming Language: Python / Java
- Encryption Algorithms: RSA, AES
- Hashing: SHA-256
- Networking: Socket Programming / HTTP

---

## Project Structure

NETWORK-SECURITY/
- main.py  
- client.py  
- server.py  
- encryption.py  
- decryption.py  
- key_generation.py  

---

## How to Run

1. Clone the repository:
   git clone https://github.com/Manasvi-a11y/NETWORK-SECURITY.git

2. Go to project folder:
   cd NETWORK-SECURITY

3. Install required libraries:
   pip install -r requirements.txt

4. Run server:
   python server.py

5. Run client:
   python client.py

---

## Example

Input:
Hello

Encrypted Output:
Encrypted text (not readable)

Decrypted Output:
Hello

---

## Applications
- Secure messaging systems
- Online transactions
- Secure data sharing

---

## Limitations
- Key management is difficult
- Encryption increases processing time

---

## Future Scope
- Add graphical user interface
- Support multiple users
- Improve performance and security

---

## Author
Manasvi Verma
