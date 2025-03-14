# E-commerce Take-Home Assessment

## Overview

You are tasked with developing a comprehensive full-stack **e-commerce web application** using the MERN stack (MongoDB, Express.js, React, Node.js). This realistic scenario enables users to browse products, manage shopping carts, place orders, and view store locations using integrated Google Maps functionality. Provided data includes products, categories, and store locations. This project tests your abilities in database structuring, API design, authentication, front-end integration, DevOps best practices, and performance optimization. The expected completion time is approximately **6-8 hours**.

**Important:** We utilize AI detection tools. Please ensure that your submission is your own original work and **not AI-generated**. Clearly document your development process with frequent commits.

## Project Requirements

### Backend (Node.js, Express, MongoDB)

- **RESTful API & CRUD Operations:**
  - Clearly defined API endpoints for products, categories, users, shopping carts, and orders.

- **MongoDB Schema:**
  - Optimized database schemas for efficient storage and querying of products, categories, user profiles, carts, orders, and store locations.

- **JWT Authentication:**
  - Secure authentication with registration, login, and role-based access control (admin/customer roles).

- **Security Measures:**
  - Implement rate limiting, request validation, input sanitization, and comprehensive error handling.

- **Performance Optimization:**
  - Apply indexing strategies, efficient data handling, pagination, and lean queries.

### Frontend (React.js)

- **User Interface:**
  - Responsive, intuitive, accessible UI supporting product browsing, cart management, checkout, and store location visualization.

- **State Management:**
  - Implement global state management using Redux or React Context for authentication, cart contents, and application data.

- **Authentication Handling:**
  - Securely manage user registration, login, logout, and JWT tokens.

- **Protected Routes & Role-Based Access:**
  - UI adjustments based on roles (admin/customer) with appropriate functionalities.

- **Query Features:**
  - Robust filtering, search, pagination, and efficient data fetching.

- **Google Maps API Integration:**
  - Dynamically visualize provided store locations using Google Maps.

### Provided Data

JSON data provided includes:
- **Products:** name, description, price, category, image URLs
- **Categories:** category names
- **Store Locations:** name, address, latitude, longitude

Use this data to initially populate your database.

## Deployment and Documentation

- **Deployment:**
  - Deploy backend/frontend separately on services like Heroku, Render, Netlify, or Vercel.

- **Documentation:**
  - Provide detailed setup, local environment instructions, deployment instructions, and clearly document design decisions in your README.

- **Testing:**
  - Provide unit/integration tests covering authentication, CRUD operations, and API endpoints.

- **CI/CD & Docker:**
  - Implement Continuous Integration/Continuous Deployment (CI/CD) pipelines with GitHub Actions.
  - Containerize your application using Docker.

## Submission Guidelines

- Upload your project to a public GitHub repository.
- Provide URLs for deployed frontend/backend.
- Clearly document your implementation approach and explain significant design or optimization choices.
- We utilize AI detection tools—please ensure your submission is your original, human-written code.
- Frequent commits are required to showcase your development process.

We look forward to reviewing your submission!
