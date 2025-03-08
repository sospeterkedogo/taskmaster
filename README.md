# Task Master - Flask API

Task Master is a simple **Flask CRUD API** for managing tasks. It allows users to **create, read, update, and delete tasks**. The API is hosted on **Render** for easy deployment and access.

## 🚀 Live Demo
🔗 **Base URL:** [`https://taskmaster-ct6d.onrender.com/`](https://taskmaster-ct6d.onrender.com/)

## 📌 Features
✅ **Create, Read, Update, and Delete (CRUD) tasks**
✅ **RESTful API design**
✅ **Flask and SQLite support**
✅ **Deployed on Render**

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/sospeterkedogo/taskmaster.git
cd taskmaster
```

### 2️⃣ Create a Virtual Environment (Optional)
```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Run the Flask App Locally
```sh
python app.py
```
The API will be available at: `http://127.0.0.1:5000/`

## 🔥 API Endpoints

| Method | Endpoint         | Description          |
|--------|----------------|----------------------|
| GET    | `/tasks`        | Get all tasks       |
| GET    | `/tasks/<id>`  | Get a specific task |
| POST   | `/tasks`        | Create a new task   |
| PUT    | `/tasks/<id>`  | Update a task       |
| DELETE | `/tasks/<id>`  | Delete a task       |

### Example Task Object (JSON)
```json
{
  "id": 1,
  "title": "Finish the project",
  "description": "Complete the Flask API deployment"
}
```

## 🚀 Deployment on Render
### 1️⃣ Push to GitHub
```sh
git add .
git commit -m "Deploying Task Master API"
git push origin main
```

### 2️⃣ Deploy on Render
- Go to [Render](https://dashboard.render.com/) and create a **new Web Service**.
- Connect your GitHub repo.
- Use the following settings:
  - **Build Command:** `pip install -r requirements.txt`
  - **Start Command:** `gunicorn app:app`

### 3️⃣ Get Your Live API URL
Once deployed, you will receive a live URL like:
```
https://your-flask-api.onrender.com/
```

## 💡 Future Improvements
- ✅ Add user authentication
- ✅ Implement task categories
- ✅ Improve error handling

## 🤝 Contributing
Pull requests are welcome! Feel free to fork the repo and submit a PR. 🎉

## 📜 License
This project is licensed under the **MIT License**.

---
### 🎯 Made with ❤️ using Flask & Render

