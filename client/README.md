# MERN Stack eCommerce App

A full-stack eCommerce web application built using the **MERN** stack (MongoDB, Express.js, React, Node.js). This app provides all the core functionality needed for an online store, including user authentication, product listing, cart management, order processing, and payment integration.

## Features

- **User Authentication**: Register, login, and manage user sessions.
- **Product Management**: View, filter, and search products in different categories.
- **Shopping Cart**: Add products to cart, update quantities, and remove items.
- **Order Management**: Users can place orders, view their order history, and track status.
- **Admin Dashboard**: Admin users can manage products, orders, and view analytics.
- **Responsive UI**: Built with **React**, **Vite**, and **Tailwind CSS** for a modern, responsive front-end.
- **Payment Integration**: Integrates with **PayPal** for processing payments.
- **Cloud Storage**: Product images are hosted on **Cloudinary** for fast, scalable image delivery.

## Tech Stack

- **Frontend**: 
  - React (with Vite for faster development)
  - Tailwind CSS
  - ShadCN UI (for components)

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (with Mongoose)
  
- **Other**:
  - JWT (JSON Web Tokens) for authentication
  - PayPal API for payment gateway integration
  - Cloudinary for image hosting
  
## Prerequisites

Before running this application, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- [MongoDB](https://www.mongodb.com/) (locally or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas))
- [Git](https://git-scm.com/)

.env file includes

 CLOUDINARY_CLOUD_NAME = drzyjxfzz
 CLOUDINARY_API_KEY = 349445685536529
 CLOUDINARY_API_SECRET = SfrrIGgkk4TOYyf70iL3dR19LbI

 PAYPAL_CLIENT_ID = AWJXAcgJSTe5eHi0GGatNcYWLe__xxxx8n55XCwY-0aDFgqbLtcIr-2GtHkDPCMa5eB3fn-PqEI0ugui02
 PAYPAL_CLIENT_SECRET = ECqdOvguZ_tt30DCVmVMusZJlb1fXKezwsz3n-i5DPELb1iB27QC5oAOi8HCZaz6Yll2APMXg_ik2Ior

 MONGO_URL = mongodb+srv://anishkandel1:Anish.1@cluster0.zaehy.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0

 PORT = 5000