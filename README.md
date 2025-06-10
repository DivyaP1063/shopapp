# 🛍️ ShopHub - Fashion E-Commerce Platform

**Project Title:** Dual Login E-Commerce Platform for Fashion Retail  
**Tech Stack:** React, Vite, TailwindCSS, ShadCN, Node.js, Express, MongoDB, Cloudinary, TypeScript

---

### 🔗 Demo Video

👉 [Click here to view the Demo Video](https://player.cloudinary.com/embed/?cloud_name=dfvs0kijp&public_id=shophub_prototype_den94y&profile=cld-default)

---

## 🎯 Objective

**ShopHub** is a full-scale fashion e-commerce platform designed to deliver a seamless and modern shopping experience. It supports dual user roles:

- 👩‍💼 **Sellers (Clients):** Register and manage product listings
- 🛒 **Buyers (Users):** Browse, filter, wishlist, and purchase products

Inspired by platforms like **Myntra**, **Zara**, and **ASOS**, ShopHub combines modern UI, secure transactions, and real-time user support.

---

## 👥 User Roles & Functionalities

### 🧾 Seller (Client) Portal

#### Core Features
- Secure registration and login
- Add, edit, delete product listings
- Upload multiple product images via **Cloudinary**
- Product categorization: category, size, pricing, stock
- Access and manage customer orders
- Track order status
- Sales dashboard with:
  - Tabular product management
  - Filters & sorting
  - Charts and graphs for product performance insights

---

### 🛍️ Buyer (User) Portal

#### Core Features
- Email login support
- Browse all products
- Advanced filtering (category, size, price, latest)
- Product pages with sizes, images
- Wishlist and cart functionalities
- Secure checkout with payment integration 
- Order history & tracking
- Chatbot integration for navigation and support

---

## 🧑‍💻 Tech Stack

| Layer        | Technology                             |
|--------------|-----------------------------------------|
| Frontend     | React, Vite, TailwindCSS, ShadCN, TypeScript |
| Backend      | Node.js, Express                        |
| Database     | MongoDB                                 |
| Auth         | JWT                             |
| Image Upload | Cloudinary                                |
| Styling UI   | TailwindCSS + ShadCN                    |
| Chatbot      | GPT/Dialogflow               |
| Payment      | Razorpay           |

---

## 📁 Project Structure

```
shophub/
├── client/         # React + Vite frontend
├── server/         # Node.js + Express backend
├── public/         # Static assets
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/DivyaP1063/shopapp.git
cd shophub
```

### 2. Install Dependencies

**Frontend (client):**
```bash
cd client
npm install
```

**Backend (server):**
```bash
cd ../server
npm install
```

### 3. Start Development Servers

**Frontend:**
```bash
npm run dev
```

**Backend:**
```bash
npm run dev
```

> Make sure MongoDB is running and `.env` is correctly configured.

---

## 🔐 Environment Variables

Create a `.env` file in the server directory with the following variables:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
RAZORPAY_API_KEY=your_api_key
RAZORPAY_API_SECRET=your_api_secret
```
Create a `.env` file in the client directory with the following variables:

```env

VIYE_RAZORPAY_API_KEY=your_api_key

---

## 💡 Future Enhancements

- Admin dashboard
- AI-powered product recommendations
- React Native mobile app
- Real-time push notifications
- Theme support (dark/light)

---

## 📬 Team Member
Gitanshi Sethi
Sparsh Singh
Siddharth Singh
Divya Prakash
---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---


## 📎 Links

- 🌐 Live Preview: _Coming soon_
- 📱 Mobile App: _Coming soon_
- 📽️ Demo Video: _Coming soon_