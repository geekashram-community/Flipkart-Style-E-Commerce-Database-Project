# Flipkart-Style E-Commerce Database Project

## 🎯 Problem Statement
Build a robust database to manage an online shopping system where:

- Users can browse products, add them to a cart, place orders, and make payments.
- Products belong to categories and are sold by different sellers.
- Orders can contain multiple products.
- Users can review products they have purchased.

---

## 💡 Key Requirements & Data

### 1. Users
- Can create an account and place orders.
- Can review products.
- **Data Fields**:  
  - Name  
  - Email  
  - Password  
  - Address  
  - Phone

### 2. Products
- Belong to a category.
- Sold by sellers.
- Can have multiple reviews.
- **Data Fields**:  
  - Name  
  - Price  
  - Stock

### 3. Sellers
- Each product is linked to a seller.
- **Data Fields**:  
  - Name  
  - Email  
  - Contact

### 4. Payments
- Each order must have a payment record.
- Transaction ensures stock is updated only if payment succeeds.
- **Data Fields**:  
  - Amount  
  - Payment Date  
  - Payment Method  
  - Status

### 5. Reviews
- Users can give ratings and comments for products they bought.
- Each user can review a product only once.

### 6. Orders
- Can contain multiple products.
- Must store quantity and price for each product.
- **Data Fields**:  
  - Date  
  - Quantity  
  - Price  
  - Total Amount  
  - Status
