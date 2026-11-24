# AuraGifts — Professional E-Commerce Gift Shop (MERN Stack)

Welcome to **AuraGifts**, a modern, production-grade gift boutique e-commerce web application engineered with the MERN stack (MongoDB, Express, React, Node.js) and styled with Tailwind CSS.

---

## 🎨 Color Palette & Design System
- **Primary:** `#563047` (Deep Mulberry / Wine)
- **Secondary:** `#E99A91` (Dusty Rose / Coral)
- **Background:** `#FAF7F2` (Warm Alabaster / Cream)
- **Accent:** `#C4A46C` (Warm Gold / Champagne)
- **Text:** `#292629` (Espresso Charcoal)
- **White:** `#FFFFFF`
- **Border:** `#E9E2DC`
- **Headings Font:** *Playfair Display* (Editorial Serif)
- **Body Font:** *Inter* (Clean Modern Sans-Serif)

---

## 📁 Project Architecture

```
gift-shop/
├── frontend/                     # React + Vite Client
│   ├── public/                   # Static assets & favicon
│   ├── src/
│   │   ├── assets/               # Local icons & media
│   │   ├── components/           # Reusable UI components
│   │   │   ├── common/           # Navbar, Footer, Buttons, Modals
│   │   │   └── home/             # Hero, CategoryGrid, BestSellers, etc.
│   │   ├── pages/                # Route views (Home, Products, Admin, etc.)
│   │   ├── layouts/              # MainLayout, AdminLayout, DashboardLayout
│   │   ├── context/              # AuthContext, CartContext, WishlistContext
│   │   ├── hooks/                # Custom React hooks
│   │   ├── services/             # Axios API client calls
│   │   ├── routes/               # Public & Protected route definitions
│   │   ├── utils/                # Helpers, formatters, sample data
│   │   ├── styles/               # index.css (Tailwind layers & fonts)
│   │   ├── App.jsx               # Root application router
│   │   └── main.jsx              # React DOM entry point
│   ├── index.html                # HTML template with Google Fonts
│   ├── vite.config.js            # Vite configuration
│   ├── tailwind.config.js        # Design tokens & color system
│   └── package.json
│
├── backend/                      # Node.js + Express REST API
│   ├── config/                   # Database (Mongoose), Cloudinary, Razorpay
│   ├── controllers/              # Request handlers (Auth, Products, Orders)
│   ├── middleware/               # Auth (JWT), Admin check, Rate limits, Multer
│   ├── models/                   # Mongoose schemas (User, Product, Order, etc.)
│   ├── routes/                   # API route definitions
│   ├── services/                 # Business logic, email sending
│   ├── validators/               # Input validation schemas
│   ├── utils/                    # Helper functions & error handlers
│   ├── uploads/                  # Temporary file upload staging
│   ├── server.js                 # Express server bootstrap
│   └── package.json
│
├── .gitignore                    # Git ignore file for node_modules, .env, dist
└── README.md                     # Comprehensive developer manual
```

---

## 🚀 How to Run the Application

### 1. Start the Backend API Server
Open a terminal in the root directory:
```bash
cd backend
npm run dev    # Or: npm start
```
- Server URL: `http://localhost:5000`
- API Health Check: `http://localhost:5000/api/health`

### 2. Start the Frontend Vite Dev Server
Open a second terminal in the root directory:
```bash
cd frontend
npm run dev
```
- Web Application URL: `http://localhost:5173`

---

## 🧭 Step-by-Step Development Phases
- **Phase 1 (Active):** Project Architecture, Design System & Luxury Homepage
- **Phase 2-3:** Product Listing, 15 Categories & Deep Product Details
- **Phase 4-5:** Customer Authentication & Comprehensive User Dashboard
- **Phase 6-8:** Express REST APIs, MongoDB Atlas Connection, Products & Categories
- **Phase 9:** Admin Panel (Orders, Products, Inventory, Analytics)
- **Phase 10-11:** Cart, Wishlist, Multi-Step Checkout & Order Tracking
- **Phase 12-14:** Razorpay Payment, Cloudinary Images, Invoices & Reports
- **Phase 15:** Security Hardening, Audit Logs & Production Deployment
