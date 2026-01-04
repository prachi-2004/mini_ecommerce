# Mini E-Commerce Product & Cart

## Objective
A mini e-commerce application built using React to demonstrate component design,
state management, and core React fundamentals.

## Features
- Product listing with stock status
- Search products by name
- Filter products by category
- Sort products by price (Low–High, High–Low)
- Add/remove products from cart
- Update cart item quantities with stock constraints
- Real-time cart total and item count
- Empty state handling (no products, empty cart)

## Tech Stack
- React (Functional Components)
- JavaScript (ES6+)
- CSS

## Data Source
- https://dummyjson.com/products

## Project Structure

```bash
mini-ecommerce-react/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── ProductList.jsx
│   │   ├── ProductCard.jsx
│   │   ├── Filters.jsx
│   │   ├── Cart.jsx
│   │   ├── CartItem.jsx
│   │
│   ├── hooks/
│   │   └── useProducts.js
│   │
│   ├── App.jsx
│   ├── index.js
│   ├── styles.css
│
├── .gitignore
├── package.json
├── README.md



## How to Run Locally
```bash
npm install
npm start
