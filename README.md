# E-commerce Take-Home Assessment

## Overview

You are tasked with developing a comprehensive full-stack **e-commerce web application** using the MERN stack (MongoDB, Express.js, React, Node.js). This project simulates a realistic scenario where users can browse products, manage shopping carts, place orders, and explore store locations via Google Maps integration. Provided data includes products, categories, and store locations. This challenge evaluates your skills in database structuring, API design, authentication, front-end integration, and performance optimization. The expected completion time is approximately **6-8 hours**.

## Project Requirements

### Backend (Node.js, Express, MongoDB)

- **RESTful API & CRUD Operations:**
  - Develop API endpoints for products, categories, users, shopping carts, and orders.

- **MongoDB Schema:**
  - Create optimized schemas for products, categories, user profiles, carts, orders, and store locations.

- **JWT Authentication:**
  - Secure authentication with registration, login, and role-based access control (admin, customer).

- **Security Measures:**
  - API rate limiting, request validation, input sanitization, error handling.

- **Performance Optimization:**
  - Implement database indexing, efficient pagination, and lean queries.

### Frontend (React.js)

- **User Interface:**
  - Responsive, accessible UI for browsing, cart management, order processing, and viewing store locations.

- **State Management:**
  - Manage global states using Redux or React Context for authentication, cart, and application data.

- **Authentication Handling:**
  - Secure user registration/login with JWT management.

- **Protected Routes & Role-Based Access:**
  - UI displays based on user roles with specific admin/customer features.

- **Query Features:**
  - Implement robust filtering, search, pagination, and efficient data fetching.

- **Google Maps API Integration:**
  - Visualize provided store locations dynamically using Google Maps.

## Provided Data

JSON dataset includes:
- **Products:** name, description, price, category, image URLs
- **Categories:** category names
- **Store Locations:** name, address, latitude, longitude

Populate your database initially using the provided dataset.

## Deployment and Documentation

- **Deployment:**
  - Host backend/frontend separately (AWS, Azure, GCP, Heroku, Render, Netlify, Vercel).

- **Documentation:**
  - Detailed setup and deployment instructions included in the README.

- **Testing:**
  - Basic unit/integration tests for authentication, CRUD operations, and API endpoints.

## Bonus (Optional)

- CI/CD implementation with GitHub Actions
- Docker containerization

## Submission Guidelines

- Upload to a public GitHub repository.
- Provide URLs for deployed frontend/backend.
- Document implementation approach and significant design/optimization choices.
