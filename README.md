# ShopSphere — E-Commerce Platform

## Live Demo
https://ecommerce-capstone-pxdw.onrender.com

## Overview
A full-stack e-commerce web application built with the MERN stack (MongoDB, Express, React, Node.js), featuring product browsing, cart management, user authentication, and secure payment processing.

## Features
- Product listing and detail pages
- Shopping cart and checkout flow
- User registration/login (JWT authentication)
- Secure payment integration (PayPal, sandbox/test mode)
- Order confirmation and order history
- Admin product/order management

## Tech Stack
- Frontend: React, Bootstrap
- Backend: Node.js, Express
- Database: MongoDB (Atlas)
- Payments: PayPal

## Dataset
Product catalog structured using category taxonomy from the Olist Brazilian E-Commerce dataset (Kaggle), with representative sample products.

## Installation
1. Clone the repo
2. Run `npm install` in root and `/frontend`
3. Create a `.env` file with MongoDB URI, JWT secret, and PayPal client ID
4. Run `npm run data:import` to seed the database
5. Run `npm run dev` to start both servers
6. Visit http://localhost:3000

## Author
[Chinmaya Bharadwaj S V]