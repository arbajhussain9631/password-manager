# 🔐 GUI Password Manager (Python + Tkinter)

A beginner-friendly **GUI Password Manager** built with **Python** and **Tkinter**.  
Store your credentials (Site, Username, Password, Note) locally, generate strong passwords, copy to clipboard, search, import/export, and optionally encrypt storage.

> ⚠️ Security note: By default this app stores credentials locally. For real-world use, enable encryption (see below) and keep the `secret.key` safe. Do **not** store extremely sensitive production passwords in plain text.

---

## ✨ Features
- Add new credentials (Site / Username / Password / Note)  
- Generate strong random passwords  
- Copy password to clipboard  
- View all stored credentials in a table  
- Search by site, username, or note  
- Delete selected entries  
- Import / Export CSV  
- Optional local encryption using `cryptography` (Fernet

---

## 🖼 Screenshot
<img width="1905" height="1141" alt="Screenshot 2025-11-19 155851" src="https://github.com/user-attachments/assets/6e82c454-19de-42b8-a9d1-616e40cb20c4"/>

---
## 🛠 Tech Stack
- Python 3.x  
- Tkinter (built-in)  
- CSV (local storage)  
- Optional: `cryptography` (for Fernet-based encryption)

---

## ▶ How to Run

1. Clone repo:
```bash
git clone https://github.com/your-username/password-manager-gui
cd Password Manager
python password_manager.py

