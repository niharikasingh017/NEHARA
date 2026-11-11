# NEHARA – E-commerce Platform Features

## 1. Project Overview

**NEHARA** is a full-stack e-commerce web application designed to deliver a modern, seamless, and user-friendly online shopping experience.

The platform allows customers to explore products, discover new collections, manage shopping carts, place orders, and track their purchases through a beautifully designed interface.

Administrators can manage the product catalogue, inventory, categories, and customer orders through a dedicated administrative dashboard.

NEHARA aims to combine elegant design, smooth navigation, secure authentication, and reliable e-commerce functionality in one platform.

## 2. User Roles

### 2.1 Customer
- Register and log in to the platform.
- Browse available products and collections.
- Search products by name.
- Filter products by category.
- View product details, descriptions, and images.
- Add products to the shopping cart.
- Update product quantities.
- Remove products from the cart.
- Place orders.
- Complete test-mode payments.
- View order history.
- Track order status.

### 2.2 Administrator
- Access the administrative dashboard.
- View dashboard statistics.
- Add new products.
- Edit existing products.
- Delete products.
- Create and manage categories.
- Update product prices and stock.
- View customer orders.
- Update order statuses.
- Manage product availability.

### 2.3 Guest
- Browse available products.
- Search for products.
- Filter products by category.
- View product details.
- Register or log in to access shopping functionality.

## 3. MVP Features

| No. | Feature | Description |
|---|---|---|
| 1 | User Registration | Allow customers to create accounts. |
| 2 | User Login | Authenticate registered users. |
| 3 | JWT Authentication | Secure application access using JWT tokens. |
| 4 | Role-Based Access | Separate customer and administrator permissions. |
| 5 | Product Catalogue | Display products with images, descriptions, and prices. |
| 6 | Product Categories | Organize products into different collections. |
| 7 | Product Search | Search products by name. |
| 8 | Product Details | Display detailed product information. |
| 9 | Shopping Cart | Add, update, and remove cart items. |
| 10 | Persistent Cart | Maintain cart contents after page refresh. |
| 11 | Checkout | Review cart items and calculate the total. |
| 12 | Order Placement | Create confirmed orders after successful payment verification. |
| 13 | Order History | Display previous customer purchases. |
| 14 | Admin Dashboard | Provide administrative store management. |
| 15 | Product Management | Add, edit, and delete products. |
| 16 | Inventory Management | Maintain product stock information. |
| 17 | Order Management | View and update customer order statuses. |
| 18 | Payment Integration | Support test-mode Razorpay payments and failed-payment handling. |
| 19 | Responsive Design | Provide an optimized experience across desktop, tablet, and mobile devices. |
| 20 | Interactive UI | Include smooth transitions, animations, and interactive product cards. |

## 4. Core Workflows

### 4.1 Customer Shopping Workflow
1. Customer visits the NEHARA website.
2. Explores the product catalogue.
3. Searches or filters products.
4. Opens a product details page.
5. Registers or logs in.
6. Adds products to the shopping cart.
7. Updates quantities or removes unwanted products.
8. Proceeds to checkout.
9. Reviews the order summary and total.
10. Completes payment through the test-mode payment gateway.
11. Backend verifies the payment.
12. Confirmed order is saved in the database.
13. Customer views the order in order history.

### 4.2 Failed Payment Workflow
1. Customer proceeds to checkout.
2. Payment gateway processes the payment.
3. Payment fails or is cancelled.
4. Backend records the failed payment attempt.
5. No confirmed order is created.
6. Customer can retry payment.

### 4.3 Administrator Workflow
1. Administrator logs in.
2. Opens the NEHARA admin dashboard.
3. Manages products and categories.
4. Updates inventory.
5. Views customer orders.
6. Updates order statuses.

## 5. Payment Handling

NEHARA will integrate **Razorpay in test mode**.

The payment workflow will include:
- Creating payment requests from the backend.
- Initiating payments through the gateway.
- Receiving payment responses.
- Verifying payment signatures on the backend.
- Recording successful and failed payment attempts.
- Preventing duplicate payment processing.
- Confirming orders only after successful verification.

**Security Requirement:** Frontend payment success alone will never be considered sufficient to confirm an order.

## 6. UI/UX and Design Features

NEHARA will focus on delivering a premium and visually appealing shopping experience.

- Elegant beige and brown visual theme.
- Modern landing page with a promotional hero section.
- Attractive product cards with hover effects.
- Smooth page transitions and micro-animations.
- Clean navigation bar and category sections.
- Featured products and new arrivals sections.
- Responsive layouts for different screen sizes.
- Consistent typography and visual hierarchy.
- Clear cart and checkout interfaces.
- Attractive footer with useful navigation links.

## 7. Future Features

The following features may be implemented in future versions:

- Wishlist functionality.
- Product ratings and reviews.
- Discount coupons and promotional offers.
- Advanced filtering and sorting.
- Email notifications.
- Sales analytics and revenue reports.
- Personalized product recommendations.
- Multiple payment gateway support.
- Customer profile management.
- Delivery tracking.
- Recently viewed products.
- Flash sales and limited-time offers.

## 8. Project Scope

**Initial Goal:** Develop a functional single-brand e-commerce platform with customer authentication, product browsing, shopping cart, order management, an administrative dashboard, and test-mode payments.

**Development Duration:** 15 Days (ALTA Builder 30).

### In Scope
- Customer registration and login.
- JWT authentication.
- Role-based access control.
- Product catalogue and search.
- Shopping cart with persistent storage.
- Checkout and order management.
- Admin dashboard.
- Product and inventory management.
- Test-mode payment integration.
- Responsive and interactive frontend.

### Out of Scope
- Real-money payment processing.
- Multiple sellers and vendor dashboards.
- Advanced recommendation systems.
- Logistics and delivery partner integrations.
- Complex sales analytics.
- Production-scale distributed infrastructure.

## 9. Project Identity

**Project Name:** NEHARA

**Project Type:** Full-Stack E-commerce Web Application

**Development Track:** ALTA Builder 30 – Full-Stack Development

**Primary Objective:** Building a modern, secure, and visually engaging online shopping platform.

**Brand Experience:** Elegant. Modern. Seamless.

---

*NEHARA – Redefining the Online Shopping Experience.*
