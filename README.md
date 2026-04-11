# 🔐 JWT Decoded — Interactive Learning App

An **interactive, visual, and cybersecurity-focused learning application** to understand **JWT (JSON Web Token)** from **beginner to advanced level**.

Designed for **students, trainers, and security enthusiasts**, this tool transforms authentication concepts into **animations, simulations, and attack scenarios**.

---

## 🎯 What This Project Does

Instead of reading boring theory, this app lets you:

* 👀 **Visualize authentication flows**
* 🔄 Understand **Session vs JWT**
* 🧩 Break down **JWT structure (Header, Payload, Signature)**
* 🔐 Learn **how JWT signing works**
* 💥 Explore **real-world attack scenarios**
* 🧪 Practice with an **interactive JWT lab**

---

## 🧠 Learning Flow Covered

### 1️⃣ Authentication Basics

* How websites remember users after login

### 2️⃣ Session-Based Authentication

* Server-side session storage
* Memory dependency
* Scaling problems

### 3️⃣ JWT Authentication

* Stateless authentication
* Token-based identity

### 4️⃣ JWT Structure

* Header
* Payload
* Signature

### 5️⃣ Signature Logic

* How JWT integrity is maintained
* Why tampering fails

### 6️⃣ Real Request Flow

* Authorization: Bearer Token usage

### 7️⃣ Attack Scenarios (🔥 Key Feature)

* Payload tampering
* Token theft (XSS simulation)
* Weak secret brute-force

### 8️⃣ JWT Lifecycle

* Token creation → usage → expiry

### 9️⃣ Advanced Concepts

* HS256 vs RS256

### 🔟 Interactive Lab

* Decode JWT
* Modify payload
* Verify token behavior

---

## 🎬 Key Features

* 🎨 **Dark cyber-themed UI**
* ⚡ Smooth animations for flows
* 🧩 Interactive token breakdown
* 💥 Real attack simulations
* 🧪 Hands-on JWT playground
* 📱 Fully responsive design
* 🚫 No frameworks (Pure HTML, CSS, JS)

---

## 🛠️ Tech Stack

* HTML5
* CSS3 (Animations + UI design)
* Vanilla JavaScript

---

## 📂 Project Structure

```
jwt-learning-app/
│
├── jwt-learning-app.html   # Main application
└── README.md               # Documentation
```

---

## 🚀 How to Run

### Option 1: Direct Open

```bash
Download the file and open in browser
```

### Option 2: Using Local Server (Recommended)

```bash
python3 -m http.server
```

Then open:

```
http://localhost:8000
```

---

## 🎓 Who Is This For?

* Cybersecurity students
* Bug bounty beginners
* Web developers
* Trainers & instructors
* Anyone learning modern authentication

---

## ⚠️ Security Learning Focus

This project intentionally demonstrates **common JWT mistakes**:

* Storing tokens insecurely
* Weak secret keys
* Payload tampering attempts
* Token theft scenarios

👉 Use this to understand **how attacks work and how to prevent them**

---

## 💡 Teaching Use Case

This app is designed for:

* Classroom demonstrations
* Workshops & bootcamps
* Cybersecurity training programs
* Self-learning with visualization

---

## 🔥 Future Improvements (Optional Ideas)

* Backend integration (real JWT generation)
* Vulnerable API endpoints
* CTF-style challenges
* JWT scanner integration
* Token cracking module

---

## 👨‍💻 Author

Created as a **cybersecurity learning tool** to simplify and visualize modern authentication.

---

## ⭐ Support

If you found this useful:

* ⭐ Star the repo
* 🍴 Fork it
* 🧠 Share with learners

---

## 📜 License

This project is open-source and free to use for educational purposes.

---
