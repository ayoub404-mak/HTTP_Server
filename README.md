# HTTP Server 🖥️

A simple Python HTTP server built using **sockets**.  
This project demonstrates how to handle basic HTTP requests (`GET`) and serve static files such as `index.html` and `book.json`.

---

## 🚀 Features
- Listens on **port 8080** by default.
- Handles basic **HTTP GET requests**.
- Serves:
  - `/` → returns `index.html`
  - `/book` → returns `book.json`
- Returns **405 Method Not Allowed** for unsupported HTTP methods.

---

## 📂 Project Structure
HTTP_Server/ 
│── server.py # Main server code 
│── index.html # Example HTML page 
│── book.json # Example JSON file 
│── README.md # Project documentation


---

## ⚙️ Requirements
- Python 3.x installed on your machine.

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ayoub404-mak/HTTP_Server.git
   cd HTTP_Server
