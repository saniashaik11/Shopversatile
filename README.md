# 🛒 ShopVersatile

**ShopVersatile** is a full-stack MERN (MongoDB, Express.js, React, Node.js) e-commerce platform built for learning and experimentation.

## 🚀 Features

- 🧾 Product listing with name and price
- 🛒 Add to cart and remove from cart functionality
- 🔢 Quantity update in the cart
- 💰 Real-time total price calculation
- 🧠 Backend cart persistence using MongoDB

## 🏗️ Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Styling**: CSS

## 📁 Folder Structure

shopversatile/
├── client/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ │ └── ProductList.js
│ │ └── index.js
│ └── public/
├── server/ # Express backend
│ ├── models/
│ │ ├── Product.js
│ │ └── Cart.js
│ ├── routes/
│ │ ├── product.js
│ │ └── cart.js
│ └── index.js (or server.js)
└── .env # Environment variables

bash
Copy
Edit

## 🛠️ Getting Started

### 1. Clone the repo


git clone https://github.com/saniashaik11/Shopversatile.git
cd Shopversatile
2. Install dependencies
Backend:
cd server
npm install

Frontend:
Open a new terminal:
cd client
npm install

3. Run the app
Start the backend server:
cd server
npm start

Start the frontend app:
cd client
npm start

4. Open in browser
Visit: http://localhost:3000

