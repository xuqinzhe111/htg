# E-commerce Take-Home Assessment

## Overview

You are tasked with developing a comprehensive full-stack **e-commerce web application** using the MERN stack (MongoDB, Express.js, React, Node.js). This realistic scenario enables users to browse products, manage shopping carts, place orders, and view store locations using integrated Google Maps functionality. Provided data includes products, categories, and store locations. This project tests your abilities in database structuring, API design, authentication, front-end integration, and performance optimization. The expected time commitment is approximately **6-8 hours**.

**Important:** We utilize AI detection tools. Please ensure that your submission is your own original work and **not AI-generated**. Clearly document your development process with frequent commits to show your progress and thought process.

### Project Requirements

### Backend (Node.js, Express, MongoDB)

- **RESTful API & CRUD Operations:**
  - Clearly defined API endpoints for products, categories, users, shopping carts, and orders.

- **MongoDB Schema:**
  - Optimized database schemas for efficient storage and querying of products, categories, user profiles, carts, orders, and store locations.

- **JWT Authentication:**
  - Secure authentication including user registration, login, and role-based access control (admin/customer roles).

- **Security Measures:**
  - Implement rate limiting, request validation, input sanitization, and comprehensive error handling.

- **Performance Optimization:**
  - Apply indexing strategies, efficient data handling, pagination, and lean queries.

### Frontend (React.js)

- **User Interface:**
  - Responsive, intuitive, and accessible UI supporting product browsing, cart management, checkout, and store location visualization.

- **State Management:**
  - Implement global state management using Redux or React Context for authentication, cart contents, and app data.

- **Authentication Handling:**
  - Securely manage user registration, login, logout, and JWT tokens.

- **Protected Routes & Role-Based Access:**
  - UI adjustments based on roles (admin/customer) with appropriate access controls.

- **Query Features:**
  - Robust filtering, search, pagination, and efficient fetching from the backend.

- **Google Maps API Integration:**
  - Dynamically visualize provided store locations using Google Maps.

## Provided Data

JSON data provided includes:
- **Products:** name, description, price, category, image URLs
- **Categories:** category names
- **Store Locations:** name, address, latitude, longitude

Use this data to initially populate your database.

## Deployment and Documentation

- **Deployment:**
  - Deploy backend and frontend separately (AWS, Azure, GCP, Heroku, Render, Netlify, Vercel).

- **Documentation:**
  - Detailed setup, local environment instructions, deployment instructions, and clear explanations of design decisions in your README.

- **Testing:**
  - Unit/integration tests for critical features including authentication, CRUD operations, and API endpoints.

## Bonus (Optional)

- Set up Continuous Integration/Continuous Deployment (CI/CD) pipelines using GitHub Actions.
- Containerize your application with Docker.

## Submission Guidelines

- Upload your solution to a public GitHub repository.
- Provide URLs for deployed frontend and backend.
- Clearly document your approach, major design decisions, and optimization strategies in the README.
- **AI Detection:** Ensure your code submission is authentic and human-written, as we utilize AI detection tools during evaluation.
- **Detailed Commits:** Make frequent commits detailing your development process to showcase your thinking and workflow clearly.

We look forward to reviewing your submission!
