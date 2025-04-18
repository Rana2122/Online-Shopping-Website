Online Shopping Application
A full-stack e-commerce platform built with ASP.NET Core, featuring a Web API for product and category management and a responsive MVC front-end with Razor views. Supports user authentication via JWT, product browsing, and category CRUD operations.
Features

API: Manage products and categories (CRUD) with secure JWT authentication.
Front-End: Responsive homepage, user login/registration, and product listings.
Authentication: Role-based access (Admin/User) using JWT.
Design: Bootstrap-powered UI with sliders and promotional sections.

Tech Stack

Backend: ASP.NET Core Web API, Entity Framework Core
Front-End: ASP.NET Core MVC, Razor, Bootstrap
Authentication: JWT
Database: SQL Server (configurable)
Tools: AutoMapper, jQuery, Font Awesome

Setup

Clone the Repository:
git clone https://github.com/Rana2122/Online-Shopping-Website.git
cd Online-Shopping-Website


Install Dependencies:
dotnet restore


Configure Database:

Update appsettings.json with your SQL Server connection string:"ConnectionStrings": {
  "DefaultConnection": "Server=your_server;Database=OnlineShoppingDB;Trusted_Connection=True;"
}


Run migrations:dotnet ef migrations add InitialCreate
dotnet ef database update




Set Up JWT:

Configure appsettings.json:"Jwt": {
  "Key": "your-secret-key",
  "Issuer": "your-issuer",
  "Audience": "your-audience"
}




Run the Application:
dotnet run


Access at https://localhost:5001.
Test API at https://localhost:5001/api.



Usage

API Endpoints:
POST /api/Authenticate/Login: Authenticate users.
GET /api/Categories/GetAllCategories: List categories.
POST /api/Products/Create: Add products (requires JWT).


Front-End:
Homepage: Browse products and promotions.
Login/Registration: User authentication forms.



Contributing
Fork the repo, create a branch, and submit a pull request. See CONTRIBUTING.md for details.
License
MIT License
