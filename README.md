# 🔐 SecureVault – Encrypted Data Locker

**SecureVault** is a Streamlit-powered application that allows users to securely **encrypt, store, and retrieve sensitive information** using a private passkey.
It combines `Fernet` encryption and SHA-256 hashing to protect your confidential data.

---

## 🚀 Features

- 🔐 Encrypt and store your personal data securely
- 🔑 Access your data using a private passkey
- 🧠 Passwords hashed using SHA-256 (not stored in plain text)
- 🛡️ Admin login to reset failed access attempts
- 📁 Data stored safely in a local JSON file
- 🚫 Automatically restricts access after 3 failed attempts

---

## 🛠️ Technologies Used

- Python 3
- Streamlit
- cryptography
- hashlib
- JSON

  
## 🧪 Sample Usage

### 🔐 To Save Data:
1. Go to **🛡️ Save Data** page.
2. Enter your secret message in the textarea.
3. Create a private passkey.
4. Click **"Encrypt & Store"**.
5. You’ll receive an encrypted string — save it somewhere safe.

### 🔓 To Access Data:
1. Go to **🔓 Access Data** page.
2. Paste your encrypted string.
3. Enter the same passkey you used earlier.
4. Click **"Decrypt"** to retrieve your original data.

> 🚨 Note: After 3 failed attempts, the app will restrict access.


---
## 🤝 Feel Free to Contribute

If you'd like to improve this project, you're welcome to fork the repo and submit a pull request.

Whether it's:
- Fixing bugs 🐛
- Adding new features ✨
- Improving UI 🎨
- Enhancing security 🔐

Your contributions are greatly appreciated!

> 💬 For major changes, please open an issue first to discuss what you’d like to change.



