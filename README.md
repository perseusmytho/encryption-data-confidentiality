<h1>🔐 Encryption for Data Confidentiality & Integrity</h1>

<h2>📌 Overview</h2>
This project explores **encryption techniques** to enhance **data confidentiality and integrity** using **asymmetric, symmetric, and hybrid cryptography**. It covers **key pair generation, file encryption and decryption, digital signatures, and verification**.

<h2>🛠 Tools & Technologies Used</h2>

- **GPG (GNU Privacy Guard)** – Public-key cryptography for encryption & signing  
- **Kleopatra** – GUI for GPG key management and verification  
- **AES Encryption** – Symmetric encryption for secure file storage  
- **RSA Key Pairs** – Asymmetric cryptography for secure communication  

<h2>🔍 Key Findings & Implementation</h2>

| Encryption Method | Description | Implementation |
|------------------|-------------|----------------|
| **Asymmetric Encryption (RSA)** | Uses public/private key pairs for secure data exchange. | Generated key pairs, encrypted, and decrypted files using GPG. |
| **Symmetric Encryption (AES)** | Encrypts and decrypts files using a shared secret key. | Applied password-based encryption to protect sensitive data. |
| **Hybrid Cryptography** | Combines asymmetric & symmetric encryption for efficiency. | Encrypted a symmetric key using RSA for secure file transfer. |
| **Digital Signatures** | Ensures integrity and authenticity of data. | Signed documents with GPG and verified them with Kleopatra. |

<h2>🚀 Report & Documentation</h2>

📄 **[Download Full Report (PDF)](https://github.com/user-attachments/files/18699922/Using.Encryption.to.Enhance.Confidentiality.and.Integrity.4e.-.Marc.Corona.pdf)
**  
📂 **Encryption Artifacts & Files**:
- `my_public_key.asc` – Generated public key for encryption  
- `secretmessage_ENCRYPTED.txt` – AES-encrypted confidential message  
- `secretmessage_DECRYPTED.txt` – Successfully decrypted message  
- `signed_message.gpg` – Digitally signed document for integrity verification  

<h2>✅ Key Takeaways & Security Best Practices</h2>

🔹 **Asymmetric encryption (RSA)** is ideal for **secure key exchange** but is computationally expensive.  
🔹 **Symmetric encryption (AES)** is efficient for **bulk data encryption** but requires secure key management.  
🔹 **Hybrid cryptography** combines **speed and security** by encrypting files symmetrically and securing the key asymmetrically.  
🔹 **Digital signatures** provide **authenticity and integrity**, ensuring files haven’t been tampered with.  


---
