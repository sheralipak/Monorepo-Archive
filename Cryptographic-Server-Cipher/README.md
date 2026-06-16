# 🔐 Cryptographic Client-Server Communication Engine (Caesar Cipher)

A network security and data privacy application designed as a Problem-Based Learning (PBL) project. The application demonstrates a secure client-server communication model where sensitive data is encrypted using substitution cryptography before transmission and persistent storage.

## ⚙️ Architecture & Encryption Workflow
The system maps out end-to-end data obfuscation and administrative access control mechanisms:

1. **Client-Side Encryption:** When a user submits data into the client environment, the tool executes a **Caesar Substitution Cipher routine** to shift characters based on a designated key size, protecting plaintext credentials or logs from sniffers prior to transmission.
2. **Key-Value Server Storage:** The server ingests the encrypted cipher payload and binds it securely against a unique structural identification key, ensuring efficient fetching workflows.
3. **Decryption on Retrieval:** Authorized users can request their information back from the server database, applying the symmetric reverse shift key to restore the ciphertext back into readable plaintext.
4. **Administrative Access Boundary:** Establishes a privileged access model where only authenticated system administrators possess the authorization rights to audit all generated cryptographic keys and examine global database tables.

## 🛡️ Cybersecurity & Defensive Relevance
* **Data-in-Transit Protection:** Illustrates fundamental concepts of masking data payloads over communication channels, a core defensive pillar used in Transport Layer Security (TLS) and Virtual Private Networks (VPNs).
* **Cryptographic Vulnerability Analysis:** Serving as a clear proof-of-concept for classic substitution ciphers, this project shows how shift structures operate, laying the foundation for analyzing cryptographic weaknesses, frequency analysis attacks, and modern cryptographic implementation standards.

## 🛠️ Technical Focus
* **Encryption Standard:** Symmetric Substitution Cryptography (Caesar Cipher)
* **Architecture:** Client-Server data exchange
* **Security Principles:** Principle of Least Privilege (Admin vs. User boundaries), Symmetric Key Management, Cryptographic Auditing.
