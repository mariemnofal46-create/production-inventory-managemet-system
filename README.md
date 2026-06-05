#  Factory Management System

##  Project Description
This project is a simple relational database system designed to manage factory operations using MySQL (phpMyAdmin). It handles products, customers, workers, orders, and production processes.

---

## Database Tables

### 1. Customers
- customer_id (Primary Key)
- name
- phone

### 2. Products
- product_id (Primary Key)
- name
- price
- stock_quantity

### 3. Workers
- worker_id (Primary Key)
- name
- salary

### 4. Orders
- order_id (Primary Key)
- customer_id (Foreign Key)
- product_id (Foreign Key)
- quantity
- date

### 5. Production
- production_id (Primary Key)
- product_id (Foreign Key)
- worker_id (Foreign Key)
- quantity
- date

---

## 🔗 Relationships
- One Customer can make many Orders
- One Product can appear in many Orders
- One Worker can handle many Production records
- One Product can be produced many times

---

##  Tools Used
- MySQL
- phpMyAdmin
- Draw.io (ERD Design)

---

##  Objective
To demonstrate understanding of database design, relationships (1-to-many), and ERD modeling.

---

##  Author
Mariem Nofal
