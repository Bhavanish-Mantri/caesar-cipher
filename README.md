# 🟢 Caesar Cipher :: Secure Console

🌐 **Live Demo:** https://bhavanish-mantri.github.io/caesar-cipher/

A browser-based **Caesar Cipher** implementation with a **hacker-style UI**.  
Built using **HTML, CSS, and JavaScript**, this project focuses on clean logic and an engaging cyber-themed interface.

> ⚠️ Note: This project is **educational**. Caesar Cipher is not cryptographically secure and should not be used for real-world encryption.

---

## 🚀 Features

- 🔐 Encrypt text using Caesar Cipher
- 🔓 Decrypt encrypted text with the same key
- 💻 Hacker-style UI
- 🧠 Preserves case sensitivity (A–Z, a–z)
- 🧾 Non-alphabet characters remain unchanged

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript**

---

## 📂 Project Structure

```
Caesar-cipher/
├── index.html 
├── style.css   
├── script.js 
└── README.md  
```
---

## ⚙️ How It Works

### Caesar Cipher Logic

- Each alphabet character is shifted by a fixed number (**key**)
- Encryption shifts characters **forward**
- Decryption shifts characters **backward**
- The key is normalized using `key % 26`

**Example:**

```text
Plaintext : HELLO
Key       : 3
Encrypted : KHOOR
```

---

## 📌 Limitations

❌ Not secure against brute-force attacks  
❌ Not suitable for real encryption needs  
❌ Key space limited to 26 shifts  

This is by design, for learning purposes.

---

## 🔮 Possible Enhancements

- Add Vigenère / AES encryption modes
- Show brute-force attack demo
- Add typing / terminal animations
- Key strength indicator
- Cipher comparison mode

---

## 📜 License

This project is open for learning, experimentation, and academic use.  
Feel free to modify and extend it.
