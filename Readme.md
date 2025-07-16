# 📦 Inventory Management API

This document lists all API routes that i will build.

---

##  Authentication

| Method | Route             | Description                  |
|--------|-------------------|------------------------------|
| POST   | /auth/register    | Register a new user          |
| POST   | /auth/login       | Log in and get JWT token     |
| POST   | /auth/logout      | Log out current session      |
| POST   | /auth/forgot      | Send password reset email    |
| POST   | /auth/reset       | Reset password using token   |
| GET    | /auth/profile     | Get current user info        |

---

##  Products

| Method | Route            | Description            |
|--------|------------------|------------------------|
| GET    | /products        | List all products      |
| GET    | /products/:id    | Get single product     |
| POST   | /products        | Create new product     |
| PUT    | /products/:id    | Update product         |
| DELETE | /products/:id    | Delete product         |

---

##  Categories

| Method | Route              | Description            |
|--------|--------------------|------------------------|
| GET    | /categories        | List all categories    |
| POST   | /categories        | Add a new category     |
| PUT    | /categories/:id    | Update a category      |
| DELETE | /categories/:id    | Delete a category      |

---

##  Suppliers

| Method | Route             | Description            |
|--------|-------------------|------------------------|
| GET    | /suppliers        | List all suppliers     |
| POST   | /suppliers        | Add a new supplier     |
| PUT    | /suppliers/:id    | Update a supplier      |
| DELETE | /suppliers/:id    | Delete a supplier      |

---

##  Stock In

| Method | Route        | Description               |
|--------|--------------|---------------------------|
| POST   | /stock/in    | Add inventory stock       |

---

##  Stock Out

| Method | Route         | Description               |
|--------|---------------|---------------------------|
| POST   | /stock/out    | Remove inventory stock    |

---

##  Stock History

| Method | Route             | Description                     |
|--------|-------------------|---------------------------------|
| GET    | /stock/history    | View all stock movements        |

---

##  Orders

| Method | Route           | Description             |
|--------|-----------------|-------------------------|
| GET    | /orders         | List all orders         |
| GET    | /orders/:id     | Get single order        |
| POST   | /orders         | Create new order        |
| PUT    | /orders/:id     | Update an order         |
| DELETE | /orders/:id     | Cancel/delete an order  |
