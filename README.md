# 🚀 Express + MongoDB REST API Boilerplate

![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![Express](https://img.shields.io/badge/Express.js-Framework-black)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)
![License](https://img.shields.io/badge/License-MIT-blue)

A clean, scalable, and production-ready REST API boilerplate built with **Express.js** and **Mongoose**.

🔥 Features:
- Full CRUD operations
- MVC architecture
- Environment-based configuration
- Ready for real-world projects

---


---

## ⚙️ Tech Stack

| Tech        | Purpose              |
|------------|---------------------|
| Node.js     | Runtime             |
| Express.js  | Backend framework   |
| Mongoose    | MongoDB ODM         |
| dotenv      | Env config          |
| Nodemon     | Dev auto-restart    |

---

## 🛠️ Getting Started

### 1️⃣ Clone the repo

```bash
git clone https://github.com/your-username/mongo-api.git
cd mongo-api
```
### 2️⃣ Install dependencies

```bash
npm install
```
### 3️⃣ Setup environment variables

```bash
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/mydb
```

# Dev mode (auto-restart)
```npm run dev```

# Production
```npm start```

### 📥 Example Request
```POST /api/users
Content-Type: application/json
```
JSON
```{
  "name": "John Doe",
  "email": "john@example.com",
  "age": 25
}
```
### 📤 Example Response
```
{
  "_id": "665f1b2c3e4a5b6c7d8e9f00",
  "name": "John Doe",
  "email": "john@example.com",
  "age": 25,
  "createdAt": "2024-06-04T10:30:00.000Z",
  "updatedAt": "2024-06-04T10:30:00.000Z",
  "__v": 0
}
```
### 🧬 User Schema
```
{
  name:  String,  // required
  email: String,  // required, unique
  age:   Number   // optional
}
```
Timestamps (createdAt, updatedAt) are automatically added.

### Environment Variables
| Variable  | Description                 |
| --------- | --------------------------- |
| PORT      | Server port (default: 5000) |
| MONGO_URI | MongoDB connection string   |


### 🤝 Contributing

Pull requests are welcome!

If you’re planning major changes:

Open an issue
Discuss first
Then submit PR 

<p align="center"> Built with ❤️ by <a href="https://github.com/0xekalavya">@ekalavya</a> </p> 
