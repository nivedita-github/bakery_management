🍞 Bakery Management System

A Dockerized full-stack application designed to streamline daily operations in a bakery—handling everything from inventory to order tracking using modern container-based architecture.

🚀 Project Overview

This system simulates a real-world bakery environment where multiple services work together:

A frontend web dashboard for managing products and orders.
A backend API service handling business logic and database operations.
A PostgreSQL container for reliable data storage.
RabbitMQ for queuing and asynchronous communication between services.
Optional Redis caching and background worker services for enhanced performance.

All services are orchestrated using Docker Compose, making it easy to set up and scale.

🧩 Key Features

Add, update, and delete bakery products.
Real-time inventory management.
Order processing and queue management using RabbitMQ.
Clean and responsive UI with integrated charts and analytics.
Modular containers for frontend, backend, database, and messaging.

🛠 Technologies Used

Frontend: HTML, CSS, JavaScript (optionally Bootstrap)
Backend: Python (Flask / FastAPI)
Database: PostgreSQL
Message Queue: RabbitMQ
Containerization: Docker, Docker Compose

📦 Getting Started
Clone the repository: git clone https://github.com/nivedita-github/bakery-management.git cd bakery-management

Run the system with Docker Compose: docker-compose up --build

Access the application in your browser: http://localhost:3000
