# Java Password-manager

A simple but secure **password manager** written in Java.  
It uses a **master password** to derive an encryption key (PBKDF2) and stores all credentials encrypted with **AES-GCM**.  
Passwords are stored in an encrypted JSON file on disk, with support for creating, listing, retrieving, and deleting entries.

⚠️ **Disclaimer**: This is a learning project and should not be used as a production-ready password manager.  

---

## 🛠️ Technologies
- **Java 17+**
- **Maven**
- **Gson** (for JSON serialization)

---

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/java-password-manager.git
cd java-password-manager 
```

```bash
mvn clean compile
```




