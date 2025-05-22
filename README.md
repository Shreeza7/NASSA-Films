# 🎬 NASSA-Films – A Full-Stack Theatre Booking Experience
NASSA-Films is a comprehensive movie theatre booking system designed to simplify and enhance the movie-watching experience for users. From personalized recommendations and exclusive offers to real-time seat selection and admin-level theatre management — NASSA-Films brings everything under one digital roof.

Think of it as your own version of AMC’s booking experience built by developers, for movie lovers.

## ✨ Features
✅ User Authentication – Secure JWT-based login & registration

✅ Browse & Book Movies – Explore listings, view showtimes, and reserve your favorite seats

✅ Admin Dashboard – Manage movies, theaters, and showtimes

✅ Payment Integration – Simulated checkout system for ticket purchasing

✅ Search & Filters – Filter by genre, language, and time for easy discovery

✅ Personalized Experience – Recommendations and offers tailored for users

✅ Cinematic Community – Platform designed to connect movie lovers

## 🛠 Tech Stack
🔹 Frontend
- React.js (TypeScript)

- Mantine UI & Bootstrap

- Axios for API communication

🔹 Backend
- .NET 7 (ASP.NET Core REST API)

- Entity Framework Core

- Microsoft SQL Server

## 🚀 Getting Started
1️⃣ Clone the Repository
```bash
git clone https://github.com/Shreeza7/NASSA-Films
cd Nasa-Films
```

2️⃣ Setup Backend
- Update the database connection string in appsettings.json
- Apply database migrations:

```bash
dotnet ef database update
```
- Run the backend:
```bash
dotnet run
```
The API will be available at: http://localhost:5000

3️⃣ Setup Frontend
```bash
cd frontend
yarn install
yarn start
```
The app will run at: http://localhost:3000
