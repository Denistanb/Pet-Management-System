# 🐾 Pet Management System

The **Pet Management System** is a web application designed for managing pet records efficiently. It allows users to register, login, and manage pet profiles with ease. This system is ideal for pet owners, veterinary clinics, and animal shelters to keep track of pets' details using a simple and intuitive interface.

---

## 🌟 Features

- 👤 User registration and login with secure password hashing
- 🐶 Add, view, update, and delete pet records
- 🔍 View individual pet details by custom Pet ID
- 💡 Automatically generates unique Pet IDs based on species, breed, gender, and random digits
- 📄 Serve multiple frontend HTML pages
- 🧩 MongoDB integration for storing user and pet data
- 🌐 CORS-enabled API for cross-origin frontend-backend interaction

---

## 🛠️ Tech Stack

| Layer       | Technology                           |
|------------|---------------------------------------|
| Frontend   | HTML, CSS, JavaScript                 |
| Backend    | Python (Flask)                        |
| Database   | MongoDB                               |
| Security   | werkzeug.security (Hashing passwords) |
| Others     | Flask-CORS, pymongo                   |

---

## 📂 Project Structure
Pet-Management-System/
├── public/
│ ├── login.html
│ ├── register.html
│ ├── entry.html
│ ├── petlist.html
│ ├── update.html
│ └── home.html
├── server.py
└── README.md

- **public/**: Contains frontend HTML pages.
- **server.py**: Core backend logic for API and server routing.

---

## ⚙️ Setup Instructions

### 🔧 Prerequisites
- Python 3.x
- MongoDB installed and running on `localhost:27017`

### 🧪 Installation & Run

To set up and run the Pet Management System locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Denistanb/Pet-Management-System.git
   cd Pet-Management-System

2. **Install Dependencies:**:
   ```bash
   pip install flask pymongo flask-cors werkzeug
3. **Run the Application**:
   ```bash
   python server.py
4. **Access the Application**:
   Open your web browser and navigate to http://localhost:5000
