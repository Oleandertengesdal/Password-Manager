# 📌 MVP – Java Password Manager

## 🎯 Purpose
This project is created as a **learning experience in cryptography and cybersecurity**.  
The main objective is to design and implement a **secure password manager in Java** that follows best practices for handling sensitive data.

The MVP will serve as a foundation for understanding:
- Encryption and decryption (AES-GCM, PBKDF2 key derivation).
- Secure password handling and file storage.
- Applying cryptography principles in real-world software.

---

## ✅ Minimum Viable Product (MVP)

### Core Goals
1. **Master Password Protection**  
   - User chooses a master password.  
   - The master password is never stored. It is used to derive an encryption key with **PBKDF2WithHmacSHA256**.

2. **Secure Storage**  
   - All credentials (service, username, password, notes) are encrypted using **AES-GCM**.  
   - Encrypted data is stored in a JSON file.

3. **Basic CLI Interface**  
   - Create a new password store.  
   - Open an existing password store.  
   - Add new credentials.  
   - List stored credentials.  
   - Retrieve a credential by ID.  
   - Delete a credential.  
   - Change master password (re-encrypts the store).  
   - Save and exit.

---

## 🚀 Future Goals (Beyond MVP)
- **Graphical User Interface (GUI)**  
  - Build a JavaFX-based GUI for easier and more intuitive use.  
  - Clear design so it can be understood by non-technical users.

- **Password Generator**  
  - Generate secure random passwords.  
  - Ensure generated passwords are **completely random, non-guessable, and highly entropic**.  
  - Options for password length, symbols, and complexity.

- **Additional Usability & Security Features**  
  - Search for entries by service name.  
  - Auto-lock after inactivity.  
  - Clipboard auto-clear after copy.  
  - Cloud synchronization of encrypted store for multi-device use.

---

## 📌 Summary
The **MVP** is a working password manager with a secure command-line interface, created to explore cryptography fundamentals.  
The **future vision** is to extend it with a GUI, password generator, and advanced usability/security features to make it a more complete tool.

