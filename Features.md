# StoreFlow – Features

## 1. Project Overview

StoreFlow is a full-stack e-commerce web application that connects customers with an online store.

It provides a platform where customers can discover products, add items to their shopping carts, place orders, and manage their purchases.

Administrators can manage the product catalogue, inventory, categories, and customer orders through a dedicated dashboard.

## 2. User Roles

### 2.1 Customer

- Register and log in to the platform.
- Browse available products.
- Search products by name.
- Filter products by category.
- View product details and images.
- Add products to the shopping cart.
- Update product quantities.
- Remove products from the cart.
- Place orders.
- Complete test-mode payments.
- View order history.
- Track order status.

### 2.2 Administrator

- Log in to the administrative dashboard.
- View dashboard information.
- Add new products.
- Edit existing products.
- Delete products.
- Create and manage categories.
- Update product prices and stock.
- View all customer orders.
- Update order statuses.
- Manage product availability.

### 2.3 Guest

- Browse available products.
- Search for products.
- Filter products by category.
- View product details.
- Register or log in to access shopping functionality.

## 3. MVP Features

The following features will be implemented in the initial version.

| No. | Feature | Description |
|---|---|---|
| 1 | User Registration | Allow customers to create accounts. |
| 2 | User Login | Authenticate registered users. |
| 3 | JWT Authentication | Secure application access using JWT tokens. |
| 4 | Role-Based Access | Separate customer and administrator permissions. |
| 5 | Product Catalogue | Display available products with images and prices. |
| 6 | Product Categories | Organize products into categories. |
| 7 | Product Search | Search products by name. |
| 8 | Product Details | Display individual product information. |
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

## 4. Core Workflows

### 4.1 Customer Shopping Workflow

1. Customer visits the StoreFlow website.
2. Browses the product catalogue.
3. Searches or filters products.
4. Opens a product details page.
5. Registers or logs in.
6. Adds products to the shopping cart.
7. Updates quantities or removes unwanted products.
8. Proceeds to checkout.
9. Reviews the order total.
10. Completes payment using the test-mode payment gateway.
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
2. Opens the admin dashboard.
3. Manages products and categories.
4. Updates inventory.
5. Views customer orders.
6. Updates order statuses.

## 5. Payment Handling

StoreFlow will integrate Razorpay in test mode.

The payment workflow will include:

- Creating payment requests from the backend.
- Initiating payment through the gateway.
- Receiving payment responses.
- Verifying payment signatures on the backend.
- Recording successful and failed payment attempts.
- Preventing duplicate payment processing.
- Confirming orders only after successful verification.

**Important:** Frontend payment success alone will never be considered sufficient to confirm an order.

## 6. Future Features

The following features are outside the initial MVP scope and may be implemented in future versions.

- Wishlist functionality.
- Product ratings and reviews.
- Discount coupons.
- Advanced filtering and sorting.
- Email notifications.
- Sales analytics and revenue reports.
- Product recommendations.
- Multiple payment gateway support.
- Customer profile management.
- Delivery tracking.

## 7. Project Scope

**Initial Goal:** Develop a functional single-brand e-commerce platform with customer authentication, product browsing, shopping cart, order management, an administrative dashboard, and test-mode payments.

**Development Duration:** 15 Days (ALTA Builder 30).

**In Scope:**
- Customer registration and login.
- JWT authentication.
- Role-based access control.
- Product catalogue and search.
- Shopping cart with persistent storage.
- Checkout and order management.
- Admin dashboard.
- Product and inventory management.
- Test-mode payment integration.

**Out of Scope:**
- Real-money payment processing.
- Multiple sellers and vendor dashboards.
- Advanced recommendation systems.
- Logistics and delivery partner integrations.
- Complex sales analytics.
- Production-scale distributed infrastructure.

---

*Part of ALTA Builder 30 – Full-Stack Development Track.*
