🛒 Full Stack E-Commerce Web Application

A production-style full-stack e-commerce platform built using **React (Frontend)** and **Node.js + Express (Backend)**.  
This application simulates real-world online shopping functionality including product browsing, cart management, checkout, order placement, and admin order control.

🚀 Key Features

👤 User Features

- Browse products with images and pricing
- Add / remove items from cart
- Increase or decrease product quantity
- Persistent cart using LocalStorage
- Checkout with shipping address
- Payment method selection (Cash on Delivery / Card)
- Order confirmation page with full summary

🛠 Admin Features

- Secure admin login
- View all placed orders
- View payment method & payment status
- Delete orders
- Add new products via UI

⚙ Backend Capabilities

- RESTful API architecture
- Products & Orders management
- In-memory data storage
- CORS enabled for frontend-backend communication
- Express middleware for JSON handling

🧰 Tech Stack

Frontend
- React
- React Router DOM
- JavaScript (ES6+)
- HTML5 & CSS

Backend
- Node.js
- Express.js
- CORS

🔌 API Endpoints

Products
GET /api/products → Fetch all products

Orders
POST /api/orders → Place new order
GET /api/orders → Fetch all orders (Admin)
DELETE /api/orders/:id → Delete order (Admin)

🧪 Application Flow

1. User visits homepage  
2. Browses products  
3. Adds items to cart  
4. Reviews cart  
5. Proceeds to checkout  
6. Enters shipping details  
7. Selects payment method  
8. Places order  
9. Order stored on backend  
10. Admin manages orders  

▶️ How to Run Locally

1️⃣ Start Backend

cd backend
npm install
node server.js
Backend runs at:
http://localhost:5000

2️⃣ Start Frontend

cd frontend
npm install
npm run dev
Frontend runs at:
http://localhost:5173

🔐 Admin Credentials
Password: `admin`

🧠 Learning Outcomes

- Full-stack architecture understanding
- REST API design
- React state management
- Client-side routing
- Cart & checkout logic implementation
- Frontend–backend integration

🚧 Future Improvements

- Database integration (MongoDB / PostgreSQL)
- Authentication with JWT
- Real payment gateway (Stripe / Razorpay)
- Order status tracking
- Product image upload
- Responsive UI & improved styling

💡 Conclusion

This full-stack e-commerce platform demonstrates the implementation of real-world shopping features such as product listing, cart management, checkout flow, and order handling. The project highlights strong fundamentals in React, REST API development with Express, and seamless frontend–backend integration, making it a solid production-style web application.
This project reflects hands-on experience in developing an end-to-end full-stack system, demonstrating problem-solving skills, clean code practices, and real-world application development experience.
