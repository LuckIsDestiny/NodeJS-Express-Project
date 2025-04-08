```markdown
# 🛍️ Products API

A simple RESTful API built using **Node.js**, **Express.js**, and **MongoDB** with **Mongoose** for managing product data.

---

## 🚀 Features

- Create a product
- Get all products
- Get a single product by ID
- Update a product
- Delete a product

---

## 📦 Requirements

- Node.js (v14 or later)
- MongoDB (running locally on default port `27017`)
- MongoDB Compass (optional for GUI)

---

## 📥 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/LuckIsDestiny/NodeJS-Express-Project.git
   cd products-api
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start MongoDB (if not already running):**
   - Using terminal:
     ```bash
     mongod
     ```
   - Or use **MongoDB Compass** (GUI)

4. **Run the server:**
   ```bash
   npm run dev
   ```

---

## 🔌 API Endpoints

Base URL: `http://localhost:3000`

### ➕ Create a Product
`POST /products`

```json
{
  "name": "iPhone 15",
  "price": 999,
  "description": "Latest iPhone model"
}
```

---

### 📃 Get All Products
`GET /products`

---

### 🔍 Get a Product by ID
`GET /products/:id`

---

### ✏️ Update a Product
`PUT /products/:id`

```json
{
  "price": 899
}
```

---

### ❌ Delete a Product
`DELETE /products/:id`

---

## 📚 Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**

---

## 🙌 Author

**Aashin K S**

---

## 📝 License

This project is licensed under the MIT License.
```

---
