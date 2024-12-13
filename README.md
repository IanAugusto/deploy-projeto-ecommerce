# Shopyy - Online Store  
Link of website:
https://shopit-v2-8vys.onrender.com/

This is the **Shopyy** project, an e-commerce platform that allows users to register, manage products, use a shopping cart, and access an admin panel. The project uses a serverless database and has been deployed on Render.  

## Project Overview  

**Shopyy** is a backend application for managing e-commerce functionality, including user authentication, product filtering, CRUD operations, and more.  

## Requirements  

- **Node.js** (version 14 or higher)  
- **Yarn** (package manager)  
- **MongoDB Atlas** (or local MongoDB database)  
- **Stripe** (for payment processing)  
- **Cloudinary** (for image management)  

## Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/IanAugusto/deploy-projeto-ecommerce.git
   cd deploy-projeto-ecommerce
   ```  

2. **Install dependencies**  
   ```bash
   yarn install
   ```  

3. **Set up environment variables**  
   Create a `.env` file in the root directory and configure the following environment variables:  
   ```
   MONGO_URI=<your_mongodb_connection_string>
   STRIPE_SECRET_KEY=<your_stripe_secret_key>
   CLOUDINARY_NAME=<your_cloudinary_name>
   CLOUDINARY_API_KEY=<your_cloudinary_api_key>
   CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
   JWT_SECRET=<your_jwt_secret_key>
   ```  

4. **Start the development server**  
   ```bash
   yarn start
   ```  

## Features Delivered  

- Complete backend setup for local development.  
- Middleware definition for handling API requests.  
- Creation and testing of APIs for the project.  
- Creation and testing of the database for the project.  
- Backend routes for CRUD operations via API.  
- Development of the initial frontend using React.  
- DOM structure for the store's main page.  
- State management using Redux.  
- Product filtering on the main page.  
- User login and authentication system.  
- Application deployed on Render.  
