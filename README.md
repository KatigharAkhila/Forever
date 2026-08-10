# 🛒 E-Commerce App

A **full-stack E-Commerce application** built with the **MERN stack** that allows users to browse products, filter products based on different attributes, select product variants such as size, manage their shopping cart, and place orders.

The application supports both **Cash on Delivery (COD)** and **online payments through Stripe**, providing a secure and seamless checkout experience.

An **Admin Dashboard** is also included, allowing administrators to manage products, monitor orders, and view the store inventory.

---

## 🌐 Demo

| Application          | Link                     |
| -------------------- | ------------------------ |
| 🛍️ User Application | [**Live Demo**](#)       |
| 🔐 Admin Dashboard   | [**Admin Dashboard**](#) |

> Replace the `#` placeholders with your deployed application URLs.

---

## 📋 Table of Contents

* [✨ Key Features](#-key-features)
* [🛠️ Technologies Used](#️-technologies-used)
* [📁 Project Structure](#-project-structure)
* [⚙️ Installation and Setup](#️-installation-and-setup)
* [🔐 Environment Variables](#-environment-variables)
* [🚀 Running the Application](#-running-the-application)
* [📸 Screenshots](#-screenshots)
* [🔮 Future Enhancements](#-future-enhancements)
* [🤝 Contribution](#-contribution)
* [📄 License](#-license)

---

## ✨ Key Features

### 👤 For Users

* 🛍️ **Product Exploration**

  * Browse a variety of products.
  * Filter products by category, size, and other attributes.

* 🛒 **Cart Management**

  * Add products to the shopping cart.
  * Select product variants such as size.
  * View and modify cart items.

* 📦 **Order Placement**

  * Provide delivery information.
  * Review selected products before checkout.
  * Choose between COD and online payment.

* 💳 **Secure Online Payments**

  * Integrated with **Stripe** for secure online transactions.

### 🔐 For Admins

* 📦 **Product Management**

  * Add new products.
  * Edit existing products.
  * Delete products.

* 📋 **Order Monitoring**

  * View orders placed by customers.

* 📊 **Inventory Overview**

  * View all products available in the store.

---

## 🛠️ Technologies Used

This project is built using the **MERN Stack**, providing a modern and scalable full-stack architecture.

| Technology    | Purpose                          |
| ------------- | -------------------------------- |
| ⚛️ React.js   | Frontend UI development          |
| 🟢 Node.js    | Backend runtime                  |
| 🚂 Express.js | REST API development             |
| 🍃 MongoDB    | Database                         |
| 💳 Stripe     | Online payment processing        |
| ☁️ Cloudinary | Product image storage            |
| 🔑 JWT        | Authentication and authorization |

### Architecture

```text
┌──────────────────────┐
│     React.js UI      │
│      Frontend        │
└──────────┬───────────┘
           │
           │ REST APIs
           ▼
┌──────────────────────┐
│   Node.js + Express  │
│       Backend        │
└───────┬────────┬─────┘
        │        │
        ▼        ▼
┌───────────┐  ┌──────────────┐
│ MongoDB   │  │    Stripe    │
│ Database  │  │   Payments   │
└───────────┘  └──────────────┘
```

---

## 📁 Project Structure

```text
ecommerce-app/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── admin/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/elyse502/ecommerce-app.git
cd ecommerce-app
```

### 2. Install Backend Dependencies

```bash
cd backend
npm install
```

### 3. Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

### 4. Install Admin Dashboard Dependencies

```bash
cd ../admin
npm install
```

---

## 🔐 Environment Variables

Create a `.env` file inside the **backend** directory and add the required configuration:

```env
MONGO_URI="your_mongodb_connection_string"

CLOUDINARY_API_KEY="your_cloudinary_api_key"
CLOUDINARY_SECRET_KEY="your_cloudinary_secret_key"
CLOUDINARY_NAME="your_cloudinary_name"

JWT_SECRET="your_jwt_secret_key"

ADMIN_EMAIL="admin_email_address"
ADMIN_PASSWORD="admin_password"

STRIPE_SECRET_KEY="your_stripe_secret_key"
```

> ⚠️ **Security:** Never commit your `.env` file or expose your MongoDB, Cloudinary, JWT, or Stripe credentials publicly.

Add `.env` to `.gitignore`:

```gitignore
.env
node_modules/
```

---

## 🚀 Running the Application

The application consists of three parts:

### 🖥️ Backend

From the `backend` directory:

```bash
npm run server
```

### 🛍️ Frontend

From the `frontend` directory:

```bash
npm run dev
```

### 🔐 Admin Dashboard

From the `admin` directory:

```bash
npm run dev
```

---

## 🌐 Local URLs

Once the applications are running:

| Application          | URL                   |
| -------------------- | --------------------- |
| 🛍️ User Application | http://localhost:5173 |
| 🔐 Admin Dashboard   | http://localhost:5174 |

---

## 📸 Screenshots

### 👤 User Dashboard

Add your screenshots here:

```text
ui0
ui1
```

Example:

```markdown
![User Dashboard](./screenshots/ui0.png)

![Product Listing](./screenshots/ui1.png)
```

---

### 🔐 Admin Dashboard

Add your screenshots here:

```text
ap0
ap1
```

Example:

```markdown
![Admin Dashboard](./screenshots/ap0.png)

![Product Management](./screenshots/ap1.png)
```

---

## 🔮 Future Enhancements

Planned improvements include:

* ⭐ Add product reviews and ratings.
* 🔐 Implement social login authentication.
* ❤️ Add a wishlist feature.
* 📦 Improve inventory management.
* 🔔 Add order status notifications.
* 📊 Add more advanced analytics to the Admin Dashboard.

---

## 🤝 Contribution

Contributions are welcome! If you'd like to contribute:

1. **Fork** the repository.
2. Create a new branch:

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Commit your changes:

```bash
git commit -m "feat: add your feature"
```

5. Push your branch:

```bash
git push origin feature/your-feature
```

6. Open a **Pull Request**.

---

## 📄 License

This project is open-source and available for use and modification.

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub!
