# 💻 Know Your IP — Windows XP Desktop Edition

A retro-styled **IP lookup web application** inspired by **Windows XP desktop aesthetics** and interactive fake operating system websites.

This project displays the visitor’s public IP address and network metadata in a nostalgic **desktop-like interface**, combining classic UI design with modern public APIs.

---

## ✨ Features

* 🌐 Public IP address lookup
* 📍 Country, city, coordinates, timezone
* 🛰️ ASN, ISP and organization details
* 💻 Windows XP **Bliss wallpaper**
* 🪟 Retro desktop window interface
* ✨ Smooth opening animations
* 🖱️ Custom desktop-style cursor
* 📱 Responsive layout for mobile devices
* ⚖️ Legal disclaimer section
* 📬 Contact button with email support

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (Fetch API)**
* **ipapi.co API**

---

## 📁 Project Structure

```text
Know-Your-IP/
├── index.html
├── style.css
└── README.md
```

---

## 🚀 How It Works

The application uses the public endpoint:

```javascript
fetch("https://ipapi.co/json/")
```

to retrieve:

* IP address
* country
* city
* latitude / longitude
* timezone
* ASN
* ISP
* organization

The data is then dynamically rendered inside the desktop window interface.

---

## ⚖️ Privacy Notice

This website does **not store, log, or share user data**.

The information is fetched directly from **ipapi.co** and displayed only during the current browser session.

No cookies or internal tracking systems are used.

---

## 📄 License

This project is released for **educational and portfolio purposes**.

© 2026 Know Your IP
