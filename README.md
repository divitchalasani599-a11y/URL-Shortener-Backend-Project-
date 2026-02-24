# 🔗 URL Shortener (Backend Web Application)

A lightweight URL Shortener built using Flask and SQLite that converts long URLs into short, shareable links with automatic redirection.

---

## 📌 Project Overview

The URL Shortener is a backend web application that generates compact short links for long URLs.

When a user enters a long URL, the system creates a unique short code, stores it in a database, and redirects users to the original link when the short URL is accessed.

This project demonstrates backend development concepts including routing, database integration, and redirection handling.

---

## 🎯 Objective

- To build a REST-based backend application.
- To implement URL mapping and redirection.
- To integrate SQLite database for storage.
- To demonstrate backend web development using Flask.

---

## ✨ Features

- 🔗 Convert long URLs into short links  
- ⚡ Instant redirection  
- 💾 SQLite database storage  
- 🔎 Unique short code generation  
- 🌐 Web-based interface  
- 📊 Basic link management  

---

## 🛠 Technologies Used

- Python  
- Flask  
- SQLite  
- HTML  
- CSS  

---

## ⚙ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/url-shortener.git
cd url-shortener
```

---

### 2️⃣ Install Dependencies

```bash
pip install flask
```

Or using requirements file:

```bash
pip install -r requirements.txt
```

---

## ▶ Usage

### 1️⃣ Run the Application

```bash
python app.py
```

---

### 2️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

---

## 📂 Project Structure

```
url-shortener/
│
├── app.py
├── database.db
├── requirements.txt
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── README.md
```

---

## 🔄 How It Works

1. User enters a long URL.
2. The system generates a unique short code.
3. The mapping (short code → original URL) is stored in SQLite.
4. When the short URL is accessed, Flask redirects to the original link.
5. The redirection happens instantly.

---

## 🧠 Concepts Implemented

- Backend routing  
- Database CRUD operations  
- URL encoding  
- Redirection handling  
- Unique ID generation  

---

## 🚀 Future Enhancements

- User authentication system  
- Link analytics (click tracking)  
- Expiration-based links  
- Custom short URLs  
- REST API support  
- Deployment on cloud (AWS / Render)  

---

## 👨‍💻 Developer

Divit Chalasani  

---

## 📄 License

This project is developed for educational and backend development learning purposes.

---
