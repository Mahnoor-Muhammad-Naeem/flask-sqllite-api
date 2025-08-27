# Flask SQLite REST API

A simple **Flask RESTful API** that uses **SQLite** as its database.  
It supports full CRUD operations (Create, Read, Update, Delete) for managing users with proper error handling.

---

## 🚀 Features
- ➕ Create new users with name and email  
- 📖 Retrieve all users or a single user by ID  
- ✏️ Update existing user details  
- ❌ Delete a user  
- 🗄️ SQLite database auto-initialization  
- ⚠️ Error handling for 400, 404, and 500 status codes  

---

## 🛠️ Installation & Setup
```bash
# 1. Clone the repository
git clone https://github.com/your-username/flask-sqlite-api.git
cd flask-sqlite-api

# 2. Create virtual environment (optional but recommended)
python -m venv venv

# 3. Activate virtual environment
# Mac/Linux
source venv/bin/activate
# Windows
venv\Scripts\activate

# 4. Install dependencies
pip install flask

# 5. Run the application
python app.py



# Flask SQLite REST API

A simple **Flask RESTful API** that uses **SQLite** as its database.  
It supports full CRUD operations (Create, Read, Update, Delete) for managing users with proper error handling.

---

## 📌 API Endpoints

### 🔹 Endpoint Overview
| Method | Endpoint      | Description                 |
|--------|--------------|-----------------------------|
| POST   | `/users`     | Create a new user           |
| GET    | `/users`     | Get all users               |
| GET    | `/users/<id>`| Get a single user by ID     |
| PUT    | `/users/<id>`| Update a user (name, email) |
| DELETE | `/users/<id>`| Delete a user               |

---
