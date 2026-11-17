
# NÉHARA ✦
### A Luxury E-commerce Experience
**Elegance in Every Choice.**

<p align="center">
  A modern, minimalist e-commerce platform focused on bringing together
  premium aesthetics, effortless shopping, and a seamless digital experience.
</p>

---

## ✨ About NÉHARA

NÉHARA is a luxury lifestyle e-commerce project designed to deliver an elegant, intuitive, and user-friendly online shopping experience.

Inspired by timeless Parisian aesthetics and modern minimalism, NÉHARA aims to combine sophisticated visual design with practical shopping functionality.

The platform is being developed as a full-stack application, featuring a customer shopping interface and an administrative management system.

**Our vision:** To create an online shopping experience where simplicity meets sophistication.

---

## 🎯 Problem Statement

Small and emerging lifestyle brands need an effective digital platform to showcase their products and connect with customers.

Traditional shopping experiences can lack convenience, organized product discovery, and efficient order management.

NÉHARA aims to address these challenges through a centralized e-commerce platform that combines elegant design, convenient shopping, secure authentication, and efficient store management.

---

## 💎 Key Features

### Customer Experience
- Elegant and responsive homepage.
- Premium product presentation.
- Product catalogue and categories.
- Individual product detail pages.
- Product search and filtering.
- Shopping cart and wishlist.
- Secure user registration and login.
- Online checkout and order management.

### Admin Experience
- Admin authentication.
- Product management.
- Category management.
- Inventory management.
- Customer order management.
- Dashboard with store information.

*Features are being developed progressively. Not all listed functionality is currently implemented.*

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React | Frontend development |
| Vite | Frontend development environment |
| Tailwind CSS | Styling and responsive design |
| Python | Backend development |
| FastAPI | REST API development |
| PostgreSQL | Relational database |
| SQLAlchemy | Database ORM |
| JWT | Authentication |
| Razorpay | Planned test payment integration |
| Git & GitHub | Version control |

---

## 🏗️ Project Architecture

NÉHARA is planned around a client-server architecture.

```text
             CUSTOMER / ADMIN
                    |
                    v
             React Frontend
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
       Database  Auth     Payments
          |
          v
      PostgreSQL
```

The frontend will communicate with the backend through REST APIs.

The backend will manage authentication, product information, shopping carts, orders, and payment verification.

---

## 👥 User Roles

| Role | Responsibilities |
|---|---|
| Customer | Browse products, manage wishlist, add items to cart, and place orders |
| Administrator | Manage products, inventory, categories, and customer orders |
| Guest | Explore the store and browse public product information |

---

## 🗄️ Planned Database Design

The initial database is expected to include:

| Table | Purpose |
|---|---|
| users | Customer and administrator information |
| categories | Product categories |
| products | Product information and inventory |
| cart_items | Shopping cart records |
| orders | Customer orders |
| order_items | Products associated with orders |
| payments | Payment transaction records |

---

## 📁 Planned Project Structure

```text
NEHARA/
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
├── docs/
├── Features.md
├── README.md
└── .gitignore
```

*This is the proposed structure; it will be updated as development progresses.*

---

## 🚀 Development Roadmap

NÉHARA is being developed through the following milestones:

| Milestone | Development Task |
|---|---|
| 01 | Project planning and feature definition |
| 02 | Database schema and wireframes |
| 03 | Backend setup and database connection |
| 04 | User registration and password hashing |
| 05 | Login and JWT authentication |
| 06 | Product CRUD APIs |
| 07 | Product categories, search, and pagination |
| 08 | Frontend routing and authentication integration |
| 09 | Product listing and detail pages |
| 10 | Admin CRUD functionality |
| 11 | Shopping cart and order backend |
| 12 | Checkout and frontend integration |
| 13 | Testing and bug fixing |
| 14 | Deployment |
| 15 | Documentation and project launch |

---

## 📌 Current Development Status

**Project Status: In Development**

| Component | Status |
|---|---|
| Project planning | Completed |
| Problem statement | Completed |
| Feature documentation | Completed |
| Initial frontend | Developed locally |
| Frontend enhancements | Planned |
| Backend development | Pending |
| Database integration | Pending |
| Authentication | Pending |
| Shopping cart and checkout | Pending |
| Admin dashboard | Pending |
| Testing | Pending |
| Deployment | Pending |

---

## 🔮 Future Enhancements

- Personalized product recommendations.
- Customer reviews and ratings.
- Discount coupons and promotional offers.
- Advanced inventory analytics.
- Improved product discovery.
- Enhanced shopping experience.

---

## 📖 Documentation

For more information about the project's functionality and requirements, see:

- [Features and Requirements](Features.md)
- [Project Documentation](README.md)

---

## 🎨 Design Philosophy

NÉHARA follows a minimal luxury design approach.

Our design direction focuses on:

- Timeless typography.
- Elegant layouts.
- Refined neutral colour palettes.
- Clean product presentation.
- Smooth and subtle interactions.
- Responsive design across devices.

The goal is to create a digital experience that feels sophisticated without being overwhelming.

---

## 🎯 Project Goal

The objective of NÉHARA is to develop a complete full-stack luxury e-commerce platform while gaining practical experience in frontend development, backend engineering, database management, API integration, authentication, and deployment.

The final application will combine a premium shopping interface with reliable backend functionality and efficient store management.

---

<p align="center">

  **NÉHARA**

  *Elegance in Every Choice.*

  Built with creativity, precision, and a passion for technology.

</p>
