# 🛒 Online Shopping Application

A full-stack e-commerce platform built with **ASP.NET Core**, featuring a **Web API** for product and category management and a responsive **MVC front-end** with Razor Views. The app supports **user authentication via JWT**, product browsing, and complete category CRUD operations.

## ✅ Features

- 🔧 **API:** Manage products and categories (CRUD) with secure JWT authentication  
- 🖥️ **Front-End:** Responsive homepage, user login/registration, and product listings  
- 🔐 **Authentication:** Role-based access (Admin/User) using JWT  
- 🎨 **Design:** Bootstrap-powered UI with sliders and promotional sections  

## 🛠 Tech Stack

- **Backend:** ASP.NET Core Web API, Entity Framework Core  
- **Frontend:** ASP.NET Core MVC, Razor, Bootstrap  
- **Authentication:** JWT (JSON Web Tokens)  
- **Database:** SQL Server (configurable via `appsettings.json`)  
- **Tools & Libraries:** AutoMapper, jQuery, Font Awesome  

### 🔹 Clone the Repository

git clone https://github.com/Rana2122/Online-Shopping-Website.git
cd Online-Shopping-Website

📦 Usage
🔹 API Endpoints
POST /api/Authenticate/Login – Authenticate users
GET /api/Categories/GetAllCategories – List categories
POST /api/Products/Create – Add product (requires JWT token)

🔹 Front-End
🏠 Homepage – Browse products and featured 
👤 Login/Register – Secure user authentication forms
