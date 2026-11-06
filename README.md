# StoreFlow🛒
# StoreFlow 🛒

**A Full-Stack E-commerce Platform**

StoreFlow is a full-stack e-commerce web application designed to provide customers with a simple and secure online shopping experience. It allows users to browse products, manage shopping carts, place orders, and track their purchase history, while administrators manage products, inventory, and customer orders.

## 🎯 Problem Statement

Small businesses and individual brands often struggle to establish an online presence where customers can conveniently browse products and place orders.

Managing product catalogues, customer orders, inventory, and payments manually can become inefficient and difficult to maintain.

StoreFlow aims to address these challenges by providing a centralized platform for online shopping and store management.

## 💡 Proposed Solution

StoreFlow provides an integrated e-commerce platform with two primary interfaces:

- **Customer Interface:** Allows customers to discover products, manage their shopping carts, place orders, and track purchases.
- **Admin Dashboard:** Allows administrators to manage products, categories, inventory, and customer orders.

The platform will also support secure test-mode payment integration with server-side payment verification.

## 👥 User Roles

| Role | Responsibilities |
|---|---|
| Customer | Browse products, manage cart, place orders, and view order history |
| Administrator | Manage products, categories, inventory, and customer orders |
| Guest | Browse products and access public product information |

## ✨ Key Features

- User registration and login.
- JWT-based authentication.
- Role-based access control.
- Product catalogue and category filtering.
- Product search and detailed product pages.
- Shopping cart with persistent storage.
- Order placement and order history.
- Admin dashboard.
- Product and inventory management.
- Test-mode payment gateway integration.

For detailed functionality, see [FEATURES.md](FEATURES.md).

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming language |
| FastAPI | Backend framework and REST APIs |
| PostgreSQL | Relational database |
| React | Frontend development |
| Tailwind CSS | Responsive UI styling |
| JWT | Authentication |
| SQLAlchemy | Database ORM |
| Razorpay | Test-mode payment integration |
| Git & GitHub | Version control |

## 🏗️ Project Architecture

StoreFlow follows a client-server architecture in which the frontend communicates with the backend through REST APIs.

```text
             CUSTOMER / ADMIN
                    |
                    v
           React + Tailwind CSS
                    |
                    v
               REST APIs
                    |
                    v
             FastAPI Backend
                    |
          +---------+---------+
          |         |         |
          v         v         v
         JWT      Business  Razorpay
                  Logic
                    |
                    v
                PostgreSQL
```

### Architecture Components

**Frontend**
- React handles UI components and application navigation.
- Tailwind CSS provides responsive styling.
- API requests communicate with FastAPI.

**Backend**
- FastAPI handles application requests.
- Authentication and authorization protect restricted endpoints.
- Business logic manages products, carts, orders, and payments.

**Database**
- PostgreSQL stores users, products, categories, cart items, orders, and payment records.
- SQLAlchemy manages database interactions.

**Payment Gateway**
- Razorpay handles test-mode payments.
- The backend verifies payment signatures.
- Confirmed orders are created only after successful payment verification.

## 🗄️ Database Design

The initial database will contain the following tables:

| Table | Purpose |
|---|---|
| users | Stores customer and administrator information |
| categories | Stores product categories |
| products | Stores product information and inventory |
| cart_items | Stores customer shopping cart items |
| orders | Stores customer orders |
| order_items | Stores individual products within orders |
| payments | Stores payment transaction information |

### Main Relationships

- One user can have multiple cart items.
- One user can place multiple orders.
- One category can contain multiple products.
- One order can contain multiple order items.
- Each order can have associated payment records.

## 📁 Project Structure

```text
storeflow/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── layouts/
│       ├── services/
│       ├── context/
│       ├── hooks/
│       ├── App.jsx
│       └── main.jsx
│
├── backend/
│   ├── app/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── schemas/
│   │   ├── services/
│   │   ├── database/
│   │   ├── middleware/
│   │   └── main.py
│   │
│   ├── tests/
│   ├── requirements.txt
│   └── .env.example
│
├── README.md
├── FEATURES.md
└── .gitignore
```

## 📅 Development Roadmap

**Development Duration: 15 Days – ALTA Builder 30**

| Day | Development Task |
|---|---|
| 1 | Planning and environment setup |
| 2 | HTML, CSS and JavaScript fundamentals |
| 3 | React fundamentals |
| 4 | Tailwind CSS and routing |
| 5 | Homepage and product pages |
| 6 | Python and FastAPI fundamentals |
| 7 | PostgreSQL and SQLAlchemy |
| 8 | Registration and JWT authentication |
| 9 | Product and category APIs |
| 10 | Frontend-backend integration |
| 11 | Shopping cart functionality |
| 12 | Order management and checkout |
| 13 | Admin dashboard and payment integration |
| 14 | Testing and bug fixing |
| 15 | Deployment and documentation |

## 🧪 Testing Strategy

The application will be tested across the following areas:

- Authentication and authorization.
- Product creation, editing, and deletion.
- Product search and category filtering.
- Shopping cart operations and persistence.
- Order calculations and order history.
- Payment success, failure, and verification.
- Administrator permissions.
- API validation and error handling.

## 🚀 Deployment Plan

| Component | Planned Platform |
|---|---|
| Frontend | Vercel |
| Backend | Render |
| Database | Neon PostgreSQL |
| Source Code | GitHub |

Deployment will involve configuring environment variables, connecting the frontend and backend, setting up the database, and testing the complete application.

## 📌 Current Status

**Day 1 – Planning**

- [x] Project selected.
- [x] Project name finalized.
- [x] Problem statement defined.
- [x] Proposed solution identified.
- [x] User roles identified.
- [x] MVP features planned.
- [x] Technology stack selected.
- [x] Initial architecture designed.
- [ ] Development environment setup.
- [ ] Frontend development.
- [ ] Backend development.
- [ ] Database integration.
- [ ] Payment integration.
- [ ] Testing and deployment.

## 🎯 Project Goal

The goal of StoreFlow is to build a functional full-stack e-commerce platform within 15 days while gaining practical experience in frontend development, backend programming, database management, API development, authentication, and payment integration.

The final deliverable will be a working e-commerce application with customer shopping functionality, an administrative dashboard, persistent database storage, and test-mode payment integration.

---

*Built as part of ALTA Builder 30.*
