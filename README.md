# 🛒 Full-Stack Web Store Project

## Overview

In this final project, you will design and build a complete web store application from scratch using:

* **Frontend:** React
* **Backend:** Express (Node.js)
* **Authentication:** JWT (JSON Web Tokens)
* **AI Integration:** LLM-powered feature(s)

You will choose a product domain (e.g., sneakers, books, art, gadgets, plants, etc.) and create a fully functional online store experience.

> ⚠️ Note: No real payment integration is required. Just build a shopping cart.

---

## 🎯 Learning Objectives

By completing this project, you will:

* Build a full-stack application
* Design and consume REST APIs
* Implement authentication and protected routes
* Manage application state in React
* Integrate AI (LLM) features into a real product
* Handle search and filtering (faceted search)

---

## 🧱 Core Requirements (MVP)

### 1. Authentication (JWT Required)

* User registration
* User login
* Password hashing (e.g., bcrypt)
* JWT-based authentication
* Protected routes (e.g., cart, checkout)

### 2. Product Catalog

* Product listing page
* Product detail page

Each product must include:

* Title
* Description
* Price
* Image(s)
* Category or tags

### 3. Search & Filtering

* Search page with:

  * Text search
  * At least 2 filters (e.g., category, price range, rating)

> Bonus: Implement faceted search UI

### 4. Cart System

* Add/remove items
* Update quantities
* Persist cart (backend)
  
### 6. Backend API (Express)

You must build a REST API with routes such as:

* `POST /auth/register`
* `POST /auth/login`
* `GET /products`
* `GET /products/:id`
* `GET /products/search`
* `POST /cart`
* `POST /orders`

Use a SQLite database

---

## 🤖 LLM Integration (Required)

You must integrate at least **one meaningful AI feature**.

### Examples:

* 🧠 Product description generator (admin tool)
* 💬 Chat assistant for shopping help
* 🔍 Natural language search ("Find me cheap red sneakers")
* ⭐ Review summarization
* 🎯 Product recommendation assistant

### Requirements:

* Must call an LLM API (e.g., OpenAI or similar)
* Must be integrated into the UI
* Should solve a real user problem

---

## 🧑‍💻 Frontend Requirements (React)

* Use functional components + hooks
* Routing (React Router)
* State management (Context API, Redux, or similar)
* API integration

### Required Pages:

* Home / Product listing
* Search page
* Product detail page
* Add product page (only for admins)
* Cart page
* Login/Register page
* Checkout page

---

## 🔐 Security & Best Practices

* Hash passwords
* Store JWT securely
* Validate API inputs
* Handle errors properly
* Use environment variables

---

## 🌟 Nice-to-Have Features (Bonus)

Choose a few to make your project stand out:

### UX / UI

* Responsive design (mobile-first)
* Dark mode
* Skeleton loaders
* Toast notifications

### E-commerce Features

* Wishlist
* Product reviews & ratings
* Recently viewed items
* Related products
* Add geolocation functionality

### Advanced Search

* Faceted filters (multi-select)
* Sorting (price, popularity)
* Autocomplete suggestions

### AI Enhancements

* Personalized recommendations
* "Explain this product" button
* Smart comparison between products

### Technical Enhancements

* Pagination / infinite scroll
* Caching (React Query, SWR)
* Deployment (Vercel, Render, etc.)

---

## 🚀 Getting Started (Suggested Steps)

1. Choose your product domain
2. Design wireframes
3. Set up backend (Express + DB)
4. Implement authentication
5. Build product APIs
6. Create React app
7. Connect frontend to backend
8. Add search & filtering
9. Implement cart & checkout
10. Add LLM feature
11. Polish UI and deploy

---

## 💡 Tips

* Start simple, then iterate
* Commit often
* Test your API with Postman
* Focus on usability, not just features

---

## 🎉 Goal

By the end of this project, you will have built a **portfolio-ready full-stack application** demonstrating real-world development skills.

Good luck and have fun building! 🚀
