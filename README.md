# 🍽️ food-del — Full Stack Food Delivery Web App

A modern full stack food delivery platform with seamless user experience, real-time admin controls, secure payments, and full deployment — built with 💻 React, ⚙️ Node.js, ☁️ MongoDB, and ☁️ Vercel + Render.

---

## 🔗 Live Demo Links

| Section     | URL |
|-------------|-----|
| 🧑‍🍳 User Frontend | [https://food-del-ten-lake.vercel.app](https://food-del-ten-lake.vercel.app) |
| 🛠️ Admin Panel     | [https://food-del-he3i.vercel.app](https://food-del-he3i.vercel.app) |
| ⚙️ Backend API      | [https://food-backend-frk9.onrender.com](https://food-backend-frk9.onrender.com) |

---

## 🧠 Tech Stack

**Frontend & Admin Panel**:
- Vite + React
- React Hooks + Context API
- Axios for HTTP requests
- Tailwind CSS

**Backend**:
- Node.js + Express
- MongoDB + Mongoose
- JWT Authentication
- Stripe for Payments
- CORS, Helmet, Morgan

**Deployment**:
- Vercel (Frontend & Admin)
- Render (Backend API)

---

## 🖼️ Screenshots

> *(Add screenshots here after taking them: homepage, product list, cart, admin dashboard, etc.)*

---

## 🧩 Features

### 👨‍🍳 User Side:
- User Authentication (JWT)
- Browse & filter food items
- Add to cart and checkout
- Stripe payment integration
- Order tracking

### 🛠️ Admin Panel:
- Secure login
- View all orders
- Add/update/delete food items
- Image upload
- Realtime updates

---

## 📁 Folder Structure

# 🍽️ food-del — Full Stack Food Delivery Web App

A modern full stack food delivery platform with seamless user experience, real-time admin controls, secure payments, and full deployment — built with 💻 React, ⚙️ Node.js, ☁️ MongoDB, and ☁️ Vercel + Render.

---

## 🔗 Live Demo Links

| Section     | URL |
|-------------|-----|
| 🧑‍🍳 User Frontend | [https://food-del-ten-lake.vercel.app](https://food-del-ten-lake.vercel.app) |
| 🛠️ Admin Panel     | [https://food-del-he3i.vercel.app](https://food-del-he3i.vercel.app) |
| ⚙️ Backend API      | [https://food-backend-frk9.onrender.com](https://food-backend-frk9.onrender.com) |

---

## 🧠 Tech Stack

**Frontend & Admin Panel**:
- Vite + React
- React Hooks + Context API
- Axios for HTTP requests
- Tailwind CSS

**Backend**:
- Node.js + Express
- MongoDB + Mongoose
- JWT Authentication
- Stripe for Payments
- CORS, Helmet, Morgan

**Deployment**:
- Vercel (Frontend & Admin)
- Render (Backend API)

---

## 🖼️ Screenshots

> *(Add screenshots here after taking them: homepage, product list, cart, admin dashboard, etc.)*

---

## 🧩 Features

### 👨‍🍳 User Side:
- User Authentication (JWT)
- Browse & filter food items
- Add to cart and checkout
- Stripe payment integration
- Order tracking

### 🛠️ Admin Panel:
- Secure login
- View all orders
- Add/update/delete food items
- Image upload
- Realtime updates

---

## 📁 Folder Structure

# 🍽️ food-del — Full Stack Food Delivery Web App

A modern full stack food delivery platform with seamless user experience, real-time admin controls, secure payments, and full deployment — built with 💻 React, ⚙️ Node.js, ☁️ MongoDB, and ☁️ Vercel + Render.

---

## 🔗 Live Demo Links

| Section     | URL |
|-------------|-----|
| 🧑‍🍳 User Frontend | [https://food-del-ten-lake.vercel.app](https://food-del-ten-lake.vercel.app) |
| 🛠️ Admin Panel     | [https://food-del-he3i.vercel.app](https://food-del-he3i.vercel.app) |
| ⚙️ Backend API      | [https://food-backend-frk9.onrender.com](https://food-backend-frk9.onrender.com) |

---

## 🧠 Tech Stack

**Frontend & Admin Panel**:
- Vite + React
- React Hooks + Context API
- Axios for HTTP requests
- Tailwind CSS

**Backend**:
- Node.js + Express
- MongoDB + Mongoose
- JWT Authentication
- Stripe for Payments
- CORS, Helmet, Morgan

**Deployment**:
- Vercel (Frontend & Admin)
- Render (Backend API)

---

## 🖼️ Screenshots

> *(Add screenshots here after taking them: homepage, product list, cart, admin dashboard, etc.)*

---

## 🧩 Features

### 👨‍🍳 User Side:
- User Authentication (JWT)
- Browse & filter food items
- Add to cart and checkout
- Stripe payment integration
- Order tracking

### 🛠️ Admin Panel:
- Secure login
- View all orders
- Add/update/delete food items
- Image upload
- Realtime updates

---

## 📁 Folder Structure

food-del/
├── frontend/ # React app for users
├── admin/ # Admin dashboard app
├── backend/ # Node.js/Express backend


---

## 🔌 API Endpoints

> Base URL: `https://food-backend-frk9.onrender.com`

- `POST /api/user/register` — Register a user
- `POST /api/user/login` — Login and get JWT
- `GET /api/food/list` — Get food items
- `POST /api/order/place` — Place an order
- `GET /api/order/user` — Get user orders
- `GET /api/order/admin` — Admin view all orders
- `POST /api/food/add` — Admin adds item
- `DELETE /api/food/:id` — Admin deletes item

---

## 🧪 Run Locally

### 1. Clone the Repo

```bash
git clone https://github.com/karthiksuresh007/food-del.git
cd food-del

2. Setup Backend
bash
Copy
Edit
cd backend
npm install
npm run dev
🔐 Create a .env file in backend/:

ini
Copy
Edit
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_key
MONGO_URL=your_mongodb_url


3. Setup Frontend & Admin
bash
Copy
Edit
cd ../frontend
npm install
npm run dev
bash
Copy
Edit
cd ../admin
npm install
npm run dev
🔐 Add .env in both frontend/ and admin/ folders:

ini
Copy
Edit
VITE_API_URL=http://localhost:4000


🚀 Deployment Guide
Frontend/Admin:
Hosted on Vercel with build setup:

yaml
Copy
Edit
Root Directory: frontend or admin
Build Command: npm run build
Output Directory: build
Backend:
Hosted on Render using Express
Auto-deploys from GitHub with environment variables set in Render's settings.

👨‍💻 Author
Karthik Suresh
📍 B.Tech CSE | Full Stack Dev Enthusiast
🔗 LinkedIn (Add your actual profile)
🐦 Twitter (Optional)
🌐 Portfolio (Optional)

📜 License
This project is licensed under the MIT License — use it freely and proudly.

🥡 Bon Appétit!
This isn’t just another CRUD project — it’s a real-world full stack system.
Feel free to fork, star ⭐, or share it!
