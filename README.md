# 🍽️ Foodizo, Restaurant Management System(POS)

A full-stack **Restaurant Point of Sale (POS) System** developed as a college project using the **MERN Stack**. The application is designed to simplify restaurant operations by providing an intuitive interface for managing orders, tables, billing, and payments.

---

## 📌 Features

- 🍽️ Order Management
  - Create and manage customer orders
  - Track order status in real time
  - Update or cancel orders

- 🪑 Table Management
  - Manage table availability
  - Reserve tables for customers
  - View occupied and available tables

- 👥 User Authentication
  - Secure login using JWT
  - Role-based access control
  - Password encryption using bcrypt

- 💳 Payment Processing
  - Support for online payments
  - Secure payment gateway integration

- 🧾 Billing System
  - Automatic bill generation
  - Order summaries and invoices

- 📊 Dashboard
  - Overview of orders, tables, and sales
  - Quick access to restaurant operations

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Frontend | React.js, Tailwind CSS |
| State Management | Redux Toolkit |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JWT, bcrypt |
| API | REST API |
| Data Fetching | React Query |
| Payments | Razorpay |

---

## 📂 Project Structure

```
Restaurant-POS/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── package.json
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js
- MongoDB
- npm

### Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
cd client
npm install

cd ../server
npm install
```

Create a `.env` file in the server directory and configure the required environment variables.

Run the development servers:

```bash
# Backend
npm run dev

# Frontend
npm run dev
```

---