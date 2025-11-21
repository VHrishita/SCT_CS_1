# Caesar Cipher — Encrypt & Decrypt Tool

A simple, clean, and fully client-side Caesar Cipher encryption/decryption tool built using **HTML, CSS, and JavaScript**.  
This project allows users to enter any message, choose a shift value, and instantly encrypt or decrypt text using the classic Caesar Cipher algorithm.

All processing happens **completely inside the browser**, no data is sent, stored, or collected.

---

## 🔐 Features

- Encrypt and decrypt text using the Caesar Cipher
- Choose custom shift values (positive or negative)
- Option to preserve case (Upper/Lower)
- Option to preserve non-alphabet characters
- Instant output — no page reloads
- Copy result with one click
- Keyboard shortcuts:
  - **Ctrl + Enter** → Encrypt
  - **Ctrl + Shift + Enter** → Decrypt
- Clean, modern dark-mode UI
- Fully client-side and secure

---

## 🚀 How It Works

The Caesar Cipher shifts each alphabet letter forward or backward by *n* positions.

Example:  
Shift = 3 → A → D  
Shift = -3 → D → A

The algorithm:

1. Reads each character of the message
2. Checks if it is a letter
3. Converts it to ASCII
4. Applies `(char + shift) % 26`
5. Rebuilds the string with shifted characters

Non-alphabet characters can be:
- preserved (recommended)
- removed (optional)

---

## ✨ Author

**Vempali Hrishita**  
All rights reserved 2025

If you find this project helpful. Please drop a ⭐ :)
