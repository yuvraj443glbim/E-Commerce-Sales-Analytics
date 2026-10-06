# E-Commerce Sales & Customer Analytics using SQL

## Objective

Analyze e-commerce sales and customer data using SQL to identify revenue trends, top-performing products and categories, customer purchasing behavior, and key business performance indicators.

## Business Areas

- Revenue Performance
- Product Performance
- Customer Behavior
- Category Performance
- Geographic Performance
- Order Performance

## Dataset Structure

The project uses four relational tables:

### 1. Customers
- customer_id
- customer_name
- city

### 2. Orders
- order_id
- customer_id
- order_date
- status

### 3. Order Items
- order_id
- product_id
- quantity

### 4. Products
- product_id
- product_name
- category
- price

## Table Relationships

- `customers.customer_id` → `orders.customer_id`
- `orders.order_id` → `order_items.order_id`
- `products.product_id` → `order_items.product_id`

### Data Flow

Customers → Orders → Order Items → Products

## Business Problem Statement

The e-commerce business wants to understand its sales and customer performance using historical transaction data.

This analysis aims to answer key business questions such as:

- Which products generate the most revenue?
- Which categories perform best?
- Which customers contribute the most revenue?
- Which cities generate the most revenue?
- How many customers make repeat purchases?
- What is the average order value?
- Which products and categories need further attention?


## Results

The analysis of delivered e-commerce orders produced the following key findings:

- **Total Revenue:** ₹409,800
- **Top Revenue Category:** Electronics — ₹359,800
- **Top Product:** Laptop — ₹195,000
- **Second-Highest Product:** Smartphone — ₹120,000
- **Top Customer by Spending:** Amit — ₹165,000
- **Highest-Revenue City:** Delhi — ₹207,500
- **Average Order Value:** ₹31,523.08
- **High-Revenue Products:** Laptop and Smartphone generated more than ₹50,000 each.
- **Repeat Customers:** Rahul and Amit had 3 delivered orders each.
- **Above-Average Customers:** Rahul and Amit spent above the average customer spending.
- **Top Products by Category:** Laptop led Electronics, Office Chair led Furniture, and Backpack led Accessories.


