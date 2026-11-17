# NÉHARA ✦
### A Luxury E-commerce Experience
**Elegance in Every Choice.**

<p align="center">
  A modern luxury e-commerce platform combining timeless aesthetics,
  effortless shopping, and modern web technology.
</p>

---

## ✨ About NÉHARA

NÉHARA is a luxury lifestyle e-commerce platform designed to provide an elegant, intuitive, and convenient online shopping experience.

Inspired by Parisian aesthetics and modern minimalism, NÉHARA brings together sophisticated visual design and practical shopping functionality.

The project is being developed as a full-stack web application with a customer shopping interface and an administrative management system.

**Our Vision:** To create a digital shopping experience where simplicity meets sophistication.

---

## 🎯 Problem Statement

Small and emerging lifestyle brands need an effective digital platform to showcase their products and connect with customers.

Traditional shopping experiences can lack convenient product discovery, organized catalogues, and efficient order management.

NÉHARA aims to address these challenges through a centralized e-commerce platform featuring elegant design, secure authentication, convenient shopping, and efficient store management.

---

## 💎 Key Features

### Customer Features
- Premium and responsive homepage.
- Elegant product catalogue.
- Product categories and collections.
- Individual product detail pages.
- Product search and filtering.
- Shopping cart.
- Wishlist.
- User registration and login.
- Checkout and order management.

### Administrator Features
- Admin authentication.
- Product management.
- Category management.
- Inventory management.
- Customer management.
- Order management.
- Administrative dashboard.

*Note: These are planned platform capabilities. Features will be marked as implemented as development progresses.*

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React | Frontend development |
| Vite | Development environment |
| Tailwind CSS | Styling and responsive design |
| Python | Backend development |
| FastAPI | REST API development |
| PostgreSQL | Database |
| SQLAlchemy | Database ORM |
| JWT | Authentication |
| Razorpay | Planned payment integration |
| Git & GitHub | Version control |

---

## 🏗️ System Architecture

NÉHARA follows a client-server architecture.

```text
             CUSTOMER / ADMIN
                    |
                    v
             REACT FRONTEND
                    |
                    v
                REST APIs
                    |
                    v
              FASTAPI BACKEND
                    |
          +---------+---------+
          |         |         |
          v         v         v
       DATABASE   AUTH    PAYMENTS
          |
          v
       POSTGRESQL
```

The frontend communicates with the backend through REST APIs.

The backend will handle authentication, product information, shopping carts, orders, and payment verification.

---

## 👥 User Roles

| Role | Responsibilities |
|---|---|
| Customer | Browse products, manage wishlist, add items to cart, and place orders |
| Administrator | Manage products, categories, inventory, and orders |
| Guest | Browse publicly available products without an account |

---

## 🗄️ Planned Database Design

The initial database is expected to contain the following tables:

| Table | Purpose |
|---|---|
| users | Customer and administrator information |
| categories | Product categories |
| products | Product details and inventory |
| cart_items | Shopping cart records |
| orders | Customer orders |
| order_items | Products associated with orders |
| payments | Payment transaction records |

---

## 📁 Planned Project Structure

```text
NEHARA/
│
├── README.md
├── FEATURES.md
├── docs/
│
└── frontend/
    ├── README.md
    ├── package.json
    ├── public/
    └── src/
```

*This is the proposed documentation and frontend structure. It will be updated as the backend is added.*

---

## 🚀 Development Roadmap

The project follows 15 development milestones.

| No. | Milestone | Description |
|---|---|---|
| 01 | Project Planning | Problem statement and feature list |
| 02 | Database Design | Schema and wireframes |
| 03 | Backend Setup | Server and database connection |
| 04 | Signup API | Registration and password hashing |
| 05 | Login API | JWT authentication |
| 06 | Product CRUD | Create, read, update and delete products |
| 07 | Search & Relations | Categories, search and pagination |
| 08 | Frontend Integration | Routing and authentication screens |
| 09 | Product Screens | Listing and detail pages |
| 10 | Admin CRUD | Product management from the UI |
| 11 | Heavy Feature Part 1 | Shopping cart and order backend |
| 12 | Heavy Feature Part 2 | Checkout and payment integration |
| 13 | Testing | API tests and bug fixes |
| 14 | Deployment | Frontend,
