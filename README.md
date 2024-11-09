# MERN E-Commerce Website

A full-stack eCommerce website built using the MERN stack (MongoDB, Express, React, Node.js). This project serves as a modern online store, allowing users to browse products, add items to their cart, and make purchases. The website also provides features for admin users to manage products, orders, and users.

## Features

### User Features:
- **Product Listing**: View products in various categories with pagination and sorting options.
- **Product Details**: View detailed product descriptions, images, and reviews.
- **Add to Cart**: Add products to a shopping cart, with quantity adjustments.
- **Checkout**: Secure checkout process with order summary, shipping details, and payment options.
- **User Authentication**: Register, login, and manage user profile.
- **Order History**: View past orders and track order status.
- **Search & Filters**: Search for products by name and filter by categories, price range, etc.

### Admin Features:
- **Product Management**: Add, edit, or delete products in the inventory.
- **Order Management**: View and update order statuses (e.g., processing, shipped, delivered).
- **User Management**: View and manage user profiles and permissions.
- **Analytics**: Overview of sales and product performance.

## Technologies Used

- **Frontend**:
  - React.js (UI Components)
  - Redux (State Management)
  - React Router (Routing)
  - Axios (API calls)
  - Shadcn/UI & Tailwind (UI styling)

- **Backend**:
  - Node.js
  - Express.js (API server)
  - JWT (JSON Web Tokens) for authentication
  - Bcrypt (Password hashing)
  - Paypal (Payment integration)

- **Database**:
  - MongoDB (NoSQL database)
  - Mongoose (ODM for MongoDB)

## Setup the Environment Variables

Create a `.env` file in the root of the project and add the following environment variables:
 
# Cloudinary credentials for image upload
CLOUDINARY_CLOUD_NAME=drzyjxfzz
CLOUDINARY_API_KEY=349445685536529
CLOUDINARY_API_SECRET=SfrrIGgkk4TOYyf70iL3dR19LbI

# PayPal API credentials for payment integration
PAYPAL_CLIENT_ID=AWJXAcgJSTe5eHi0GGatNcYWLe__xxxx8n55XCwY-0aDFgqbLtcIr-2GtHkDPCMa5eB3fn-PqEI0ugui02
PAYPAL_CLIENT_SECRET=ECqdOvguZ_tt30DCVmVMusZJlb1fXKezwsz3n-i5DPELb1iB27QC5oAOi8HCZaz6Yll2APMXg_ik2Ior

# MongoDB connection URL 
MONGO_URL=mongodb+srv://anishkandel1:Anish.1@cluster0.zaehy.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0

# Server port
PORT=5000
