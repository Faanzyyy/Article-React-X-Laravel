# 📜 Article Project

🚀 **Project Name:** Article Management System

This project is a full-stack web application built using **Laravel** for the backend and **React.js** for the frontend, implementing a **RESTful API** system.

---

## 🛠️ Technologies Used

- ⚡ **Laravel** - PHP framework for backend
- ⚛️ **React.js** - JavaScript library for frontend
- 🔥 **RESTful API** - API architecture
- 🎨 **Tailwind CSS** - Styling
- 🛢️ **MySQL** - Database

---

## 📌 Prerequisites

Ensure you have the following installed on your system:

- 🐘 PHP (>= 8.0)
- 🎼 Composer
- 🐬 MySQL
- 📦 Node.js & npm
- 🔥 Laravel Installer

---

## 📥 Installation

### 1️⃣ Clone Repository
```sh
 git clone https://github.com/your-repo/article-project.git
 cd article-project
```

### 2️⃣ Backend Setup (Laravel)
```sh
 cd backend
 composer install
 cp .env.example .env
 php artisan key:generate
 php artisan migrate --seed
 php artisan serve
```

### 3️⃣ Frontend Setup (React.js)
```sh
 cd frontend
 npm install
 npm run dev
```

---

## 🚀 Running the Project

- **Backend:** `php artisan serve`
- **Frontend:** `npm run dev`

Open [http://localhost:3000](http://localhost:3000) in your browser to access the application.

---

## 🔄 API Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/api/articles` | Get all articles |
| POST | `/api/articles` | Create a new article |
| GET | `/api/articles/{id}` | Get single article |
| PUT | `/api/articles/{id}` | Update an article |
| DELETE | `/api/articles/{id}` | Delete an article |

---

## 🛠️ Useful Commands

- Run migrations: `php artisan migrate`
- Seed database: `php artisan db:seed`
- Clear cache: `php artisan cache:clear`
- Start React: `npm start`

---

## 📄 License
This project is licensed under the MIT License.

---

## 🤝 Contributing
Feel free to contribute! Fork the repo, make your changes, and submit a pull request. 🚀

---

### 👨‍💻 Developed By
**Your Name** - [GitHub](https://github.com/your-profile)

Happy coding! 🎉

