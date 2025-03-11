# Forever-Ecommerce

## Overview
Forever-Ecommerce is a full-stack eCommerce web application that allows users to browse, search, and purchase products. The project consists of three main components:
1. **Frontend** - Built using React.js
2. **Backend** - Built using Node.js, Express.js, and MongoDB, Cloudinary
3. **Admin Panel** - A separate dashboard for managing products, add items, users, and orders

## Features
- User Authentication & Authorization 
- Product Listings with Categories & Filters
- Shopping Cart & Checkout
- Payment Gateway Integration
- Admin Dashboard for Product & Order Management
- Image Upload using Cloudinary
- RESTful API for seamless communication between frontend and backend

## Tech Stack
### Frontend
- React.js
- axios
- Redux (for state management)
- Tailwind CSS / Bootstrap (for UI styling)

### Backend
- Node.js
- MongoDB
- Cloudinary

### Other Integrations
- Cloudinary (for image storage)
- Stripe / Razorpay / Cash 0n dilavary (for payments)

## Setup
### Prerequisites
Make sure you have the following Setup:
- Node.js
- MongoDB
- Cloudinary com

### Backend Setup
```sh
cd backend
npm install
npm start
```

### Frontend Setup
```sh
cd frontend
npm install
npm start
```

### Admin Panel Setup
```sh
cd admin
npm install
npm start
```

## Environment Variables
Create a `.env` file in the backend directory and add:
```
JWT_SECRET = "lankeabhishek2003"
ADMIN_EMAIL = "admin@example.com"
ADMIN_PASSWORD = "arig6P9dN355hio6"

MONGODB_URI = "mongodb+srv://lankeabhishek2003:arig6P9dN355hio6@cluster0.0l97w.mongodb.net/"

CLOUDINARY_API_KEY = "243929752418779"
CLOUDINARY_SECRET_KEY = "weGViiQdjpRkx1EDZsdxFMl0mjk"
CLOUDINARY_NAME = "dagbzmaov"

STRIPE_SECRET_KEY = "-------- Paste Stripe Secret key --------"

RAZORPAY_KEY_SECRET = '-------- Paste Razorpay Secret key --------'
RAZORPAY_KEY_ID = '-------- Paste Razorpay key Id --------'
```



