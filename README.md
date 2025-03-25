Food Delivery Website 🍔🚀
Overview
This is a fully functional food delivery web application built using the MERN stack. It allows users to browse restaurants, add food items to their cart, place orders, and track deliveries in real-time. The platform ensures a seamless user experience with an intuitive React.js front-end and a scalable Node.js back-end.


Features 🌟
✅ User Authentication – Secure login/signup with JWT authentication.
✅ Restaurant Listings – Browse a variety of restaurants and cuisines.
✅ Food Ordering System – Add items to cart, customize orders, and checkout seamlessly.
✅ Real-Time Order Tracking – Users can track their orders in real-time.
✅ Secure Payments – Integrated Stripe for hassle-free payments.
✅ Admin Panel – Manage restaurants, food items, and orders efficiently.
✅ Mobile Responsive – Fully optimized for all devices.
✅ Dark Mode Support – User-friendly theme switching option.

Tech Stack 🛠️
Technology	Usage
MongoDB	Database for storing user data, orders, and food items
Express.js	Backend framework for handling API requests
React.js	Frontend framework for building an interactive UI
Node.js	Server-side runtime environment
Redux/Context API	State management for a seamless user experience
Tailwind CSS	Styling for a modern and responsive design
JWT	User authentication and authorization
Stripe API	Secure payment gateway integration
Cloudinary	Image storage for restaurant and food images

Installation & Setup 🏗️
Step 1: Clone the Repository
git clone https://github.com/karthiksuresh007/food-delivery-website.git
cd food-delivery-website

Step 2: Install Dependencies
Backend Setup
cd backend
npm install

Frontend Setup
cd frontend
npm install

Step 3: Environment Variables
Create a .env file in the backend directory and add:

env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_api_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret



Step 4: Start the Application
Run Backend
cd backend
npm start

Run Frontend
cd frontend
npm start

