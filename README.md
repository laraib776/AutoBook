```
╔═══════════════════════════════════════════════════════════════════╗
║                                                                   ║
║   █████╗ ██╗   ██╗████████╗ ██████╗                              ║
║  ██╔══██╗██║   ██║╚══██╔══╝██╔═══██╗                             ║
║  ███████║██║   ██║   ██║   ██║   ██║                             ║
║  ██╔══██║██║   ██║   ██║   ██║   ██║                             ║
║  ██║  ██║╚██████╔╝   ██║   ╚██████╔╝                             ║
║  ╚═╝  ╚═╝ ╚═════╝    ╚═╝    ╚═════╝                              ║
║                                                                   ║
║  ██████╗  ██████╗  ██████╗ ██╗  ██╗                              ║
║  ██╔══██╗██╔═══██╗██╔═══██╗██║ ██╔╝                              ║
║  ██████╔╝██║   ██║██║   ██║█████╔╝                               ║
║  ██╔══██╗██║   ██║██║   ██║██╔═██╗                               ║
║  ██████╔╝╚██████╔╝╚██████╔╝██║  ██╗                              ║
║  ╚═════╝  ╚═════╝  ╚═════╝ ╚═╝  ╚═╝                              ║
║                                                                   ║
║       🚗  Your next ride is just one booking away.  🗓️            ║
╚═══════════════════════════════════════════════════════════════════╝
```

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-FF6B6B?style=for-the-badge&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![pyttsx3](https://img.shields.io/badge/pyttsx3-Voice%20Output-FFE66D?style=for-the-badge)
![Multi User](https://img.shields.io/badge/Users-Multi--User-A8E6CF?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-C3B1E1?style=for-the-badge)

**[⭐ Star this repo](https://github.com/laraib776/AutoBook)** · **[🐛 Report a Bug](https://github.com/laraib776/AutoBook/issues)** · **[🤝 Contribute](#-contributing)**

</div>

---

## 🚗 Tired of Booking Cars the Complicated Way?

> **No long forms. No back-and-forth calls. No confusion.**
> AutoBook puts the entire car booking experience into a clean, intuitive desktop app — pick your car, enter your details, and you're done.
>
> ### 👉 **Book it. Track it. Manage it. All in one place.** 👈
>
> *Built for multiple users, powered by a real database, and designed to just work.*

> [!NOTE]
> AutoBook is a fully **offline desktop application** — no internet required. Everything runs locally using Python, Tkinter, and a SQLite database stored right in your project folder.

---

## ✦ About AutoBook

> **AutoBook** is a comprehensive car booking system built with **Python**, **Tkinter**, and **SQLite**. It allows users to book cars, manage their appointments, view booking logs, and customize their experience — all through a user-friendly GUI that supports multiple users simultaneously.
>
> From booking to confirmation to history — AutoBook handles it all.

---

## ┌─── ✨ Key Features

| 🌟 Feature | Details |
|---|---|
| 🚗 **Easy Car Booking** | Book a car in just a few clicks with a clean input form |
| 📋 **View & Manage Bookings** | Browse all bookings and manage upcoming appointments |
| 👥 **Multi-User Support** | Multiple users can book and manage independently |
| 🎨 **Customizable Experience** | Personalize booking preferences to suit each user |
| 🔊 **Voice Feedback** | Audio confirmations via `pyttsx3` for a richer experience |
| 💾 **Persistent Storage** | All bookings saved in a local SQLite database |

---

## ┌─── 🛠️ Technology Stack

```
  ╭──────────────────┬──────────────────────────────────────────────╮
  │  Layer           │  Technology                                  │
  ├──────────────────┼──────────────────────────────────────────────┤
  │  🐍  Language     │  Python 3.x                                 │
  │  🖥️  GUI          │  Tkinter  (desktop interface)               │
  │  💾  Database     │  SQLite  via  database.db                   │
  │  🔊  Audio        │  pyttsx3  (text-to-speech feedback)         │
  ╰──────────────────┴──────────────────────────────────────────────╯
```

---

## ┌─── 🚀 Installation & Setup

### Step 1 — Install Python

Download Python 3.x from the official site:
```
🔗  https://www.python.org/downloads/
```

### Step 2 — Install Required Libraries

```bash
pip install pyttsx3
```

> 💡 `tkinter` and `sqlite3` come **pre-bundled** with Python — no extra install needed!

### Step 3 — Clone the Repository

```bash
git clone https://github.com/laraib776/AutoBook.git
cd AutoBook
```

### Step 4 — Set Up the Database

```
📥  Ensure  database.db  is placed in the same directory as the Python scripts
```

### Step 5 — Run the Application

```bash
python appointment.py
```

> 🎉 The AutoBook GUI will launch and you're ready to start booking!

---

## ┌─── 🎮 Usage Guide

Once the application is running:

```
  👤  Step 1  →  Enter your user details
  🚗  Step 2  →  Select your preferred car
  🗓️  Step 3  →  Choose your appointment date and time
  ✅  Step 4  →  Confirm your booking
  📋  Step 5  →  View or manage bookings anytime from the dashboard
```

---

## ┌─── 📁 Project Structure

```
📦 AutoBook/
 │
 ├── 📄 appointment.py       ← Main application entry point
 ├── 📄 booking.py           ← Handles booking display logic
 ├── 📄 display.py           ← Manages booking information views
 ├── 💾 database.db          ← SQLite database (place in root dir)
 └── 📄 README.md            ← You are here 👋
```

---

## ┌─── ⚠️ Database Notes

> [!IMPORTANT]
> The `database.db` file **must be placed in the same directory** as the Python scripts for the application to run correctly. This file stores all booking records and user data locally on your machine.

> [!TIP]
> To reset all bookings, simply delete `database.db` and restart the app — a fresh database will be created automatically on next launch.

---

## ┌─── 🤝 Contributing

Contributions are always welcome and appreciated! 💖

```
  1. 🍴  Fork the repository
  2. 🌿  Create your feature branch
  3. 💾  Commit your changes
  4. 📬  Open a Pull Request
```

Ideas we'd love to see: online booking sync, email confirmation, car availability filtering, or an admin dashboard — all PRs are warmly welcome!

---

## ┌─── 📜 License

AutoBook is licensed under the **MIT License** — free to use, modify, and share.
See the `LICENSE` file for full details.

---

<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║                                                          ║
║    No phone calls.  No waiting.  No paperwork.           ║
║                                                          ║
║        Just open AutoBook and hit confirm.  🚗 ✅        ║
║                                                          ║
║               Made with ❤️  by  Laraib Khalid            ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

*⭐ Drop a star if AutoBook got you where you needed to go!*

</div>
