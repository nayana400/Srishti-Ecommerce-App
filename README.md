# E-commerce App (Frontend Only)

A simple React-based E-commerce application built with  `React + Vite` that demonstrates product listing, cart management, and a checkout flow using dummy data (no backend).

1. Setup Instructions

Clone the repo:

git clone <repo-url>
cd ecommerce-app


2. Install dependencies:

npm install


3. Start the development server:

npm run dev
Runs on http://localhost:5173 (default Vite port).

4. Libraries Used

React

React Router DOM

Bootstrap

5. Features

Product listing with dummy data (local array)

Add to Cart functionality

View cart with selected items and total price

Checkout form with validation

6. Assumptions

Dummy products stored in local variables (no backend / API).
Cart state managed in frontend only (resets on refresh).

Checkout validation includes:
Email,password (valid format)
Phone (10 digits)
Payment method (COD/UPI)
If UPI → must be valid format (xxxx@oksbi, etc.)


