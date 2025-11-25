📌 Introduction

Advanced Encryption Standard (AES) is a widely used symmetric key encryption algorithm that protects data using the same key for both encryption and decryption. It is recognized for its speed, security, and efficiency, and is globally used in systems such as Wi-Fi security (WPA2/WPA3), SSL/TLS, cloud storage, and government data protection.

AES is a block cipher that operates on fixed-size blocks of 128 bits and supports key sizes of 128, 192, and 256 bits, offering strong protection against brute-force attacks.

📌 Objectives

To understand the working of symmetric key cryptography using AES.

To implement AES encryption and decryption in a programming language (Python/Java/C).

To analyze AES SubBytes, ShiftRows, MixColumns, and AddRoundKey operations.

To demonstrate secure handling of keys, plaintext, and ciphertext.

To understand real-world use cases of AES in data security.

📌 How AES Works

AES encryption is performed in multiple rounds:

✔ AES Encryption Steps

Key Expansion – Generates round keys from the original key.

Initial AddRoundKey – XOR operation with the plaintext.

Nr Rounds (10/12/14)

SubBytes – Non-linear byte substitution using S-Box.

ShiftRows – Circular shift of rows for diffusion.

MixColumns – Column-wise mixing (not used in the final round).

AddRoundKey – XOR with round keys.

Final Round – Same as above but no MixColumns.

✔ AES Decryption Steps

Performed in reverse:

InvSubBytes

InvShiftRows

InvMixColumns

AddRoundKey

📌 Features of AES

Fast and efficient for software/hardware.

Resistant to known cryptographic attacks.

Used internationally as a security standard.

Stronger than DES and other legacy algorithms.

📌 Applications of AES

Secure messaging apps

Banking transactions

Password managers

Disk and file encryption

Cloud data protection

VPNs, SSL/TLS communication.

📌 Conclusion

AES is a powerful and secure encryption standard that forms the backbone of modern cybersecurity. Through this project, you demonstrate how symmetric encryption works and how AES protects data with high efficiency and reliability.
