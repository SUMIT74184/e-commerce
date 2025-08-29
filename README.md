🛒 Ecomzy – E-Commerce Application

📌 Repo: Ecomzy

📅 Started: April 2025

✨ Overview

Ecomzy is a full-featured E-Commerce application built with Java, Spring Boot, React.js, Redux, and MySQL.
It delivers a seamless online shopping experience with authentication, product catalog, cart & checkout, and order management.
Optimized database queries ensure sub-200ms response times for fast product searches and browsing.

🚀 Key Features

🔐 Authentication & Authorization

Secure user registration & login

Role-based access (user/admin)

🛍 Product Catalog

Browse products by category, price, or keyword

Optimized queries → sub-200ms search results

🛒 Shopping Cart & Checkout

Add/remove items from cart

Order placement & payment workflow (mock/demo)

📦 Order Management

Track past orders & status updates

Admin dashboard for inventory & orders

⚡ Modern UI/UX

Built with React.js + Redux for smooth state management

Responsive design for desktop & mobile

🧱 Tech Stack

Backend: Java 17, Spring Boot (REST APIs)

Frontend: React.js, Redux

Database: MySQL

Security: JWT-based authentication

Build Tools: Maven/Gradle

⚙️ Environment Variables

Create a .env file (or configure application.properties) with:

# Database
DB_URL=jdbc:mysql://localhost:3306/ecomzy
DB_USERNAME=root
DB_PASSWORD=your_password

# JWT
JWT_SECRET=your_secret_key
JWT_EXPIRATION=3600000


Frontend .env:

REACT_APP_API_URL=http://localhost:8080/api

🐳 Running with Docker

Clone the repo:

git clone https://github.com/SUMIT74184/e-commerce.git
cd e-commerce


Build & start:

docker-compose up --build


Access services:

Frontend (React): http://localhost:3000

Backend (Spring Boot): http://localhost:8080

MySQL: localhost:3306

🔌 API Endpoints (Sample)

Auth

POST /auth/signup → Register new user

POST /auth/login → Authenticate user

Products

GET /products → Fetch all products

GET /products/{id} → Get product details

GET /products/search?q=keyword → Optimized search

Cart & Orders

POST /cart → Add item to cart

GET /cart → View cart

POST /orders → Place order

GET /orders → View user orders

📊 Performance

✅ Database queries optimized with indexes & caching strategies

✅ Product search consistently under 200ms (tested with MySQL + Spring Data JPA)

✅ Efficient Redux state handling → minimal re-renders

🛠 Future Enhancements

💳 Real payment gateway integration (Stripe/Razorpay)

📱 Mobile app version (React Native)

🌐 Internationalization (multi-language support)

📈 Advanced analytics dashboard for admin

🤝 Contributing

Fork the repo

Create a feature branch: git checkout -b feature/amazing-feature

Commit changes: git commit -m 'Add amazing feature'

Push: git push origin feature/amazing-feature

Open a Pull Request 🚀

📜 License

This project is not open-source licensed. All rights reserved © 2025 Sumit
.
