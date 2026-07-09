# 🏠 Ajeet Home Appliances — Premium E-Commerce & Vendor Platform

[![React](https://img.shields.io/badge/React-19.1-61DAFB.svg?logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-5.0-646CFF.svg?logo=vite)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC.svg?logo=tailwind-css)](https://tailwindcss.com/)
[![Firebase](https://img.shields.io/badge/Firebase-Auth_%26_Firestore-FFCA28.svg?logo=firebase)](https://firebase.google.com/)
[![Cloudinary](https://img.shields.io/badge/Cloudinary-Media_Management-3448C5.svg?logo=cloudinary)](https://cloudinary.com/)

**Ajeet Home Appliances** is a modern, responsive e-commerce web application designed for browsing, purchasing, and managing home appliances. It features a sleek customer storefront alongside a dedicated **Vendor / Admin Management Portal** for inventory control, media uploads, and order fulfillment.

---

## ✨ Key Features

### **🛍️ Customer Storefront**
- **Catalog & Category Navigation:** Explore appliances across categorized listings with search and filtering (`Category.jsx`, `ProductDetail.jsx`).
- **Interactive Shopping Cart & Checkout:** Real-time cart management (`CartContext.jsx`) and streamlined checkout flows (`Checkout.jsx`).
- **User Authentication & Profiles:** Supports email/password, phone authentication, and Google OAuth via Firebase (`Login.jsx`, `Register.jsx`, `Profile.jsx`).
- **Help & Support Center:** Customer inquiry and support portal (`HelpSupport.jsx`).

### **🏪 Dedicated Vendor / Admin Portal**
- **Vendor Access Control:** Role-protected vendor login and routing (`RequireVendor.jsx`, `VendorLogin.jsx`).
- **Analytics Dashboard:** Comprehensive overview of store metrics (`VendorDashboard.jsx`).
- **Full Product Lifecycle Management:** Create, edit, inspect, and organize products (`AddProduct.jsx`, `EditProduct.jsx`, `ProductsManagement.jsx`).
- **Cloudinary Image Storage:** High-performance media upload pipeline for product imagery (`uploader.js`, `cloudinary.js`).
- **Order Processing:** Track and update customer orders (`OrdersManagement.jsx`).

---

## 🛠️ Tech Stack

- **Frontend Framework:** React 19 + Vite
- **Styling & UI:** Tailwind CSS + Headless UI + Lucide Icons
- **Backend & Auth:** Firebase Authentication, Firebase Admin SDK, Custom JWT handling
- **Media Uploads:** Cloudinary API
- **State Management:** React Context (`CartContext`, `UserContext`, `VendorContext`)
- **Deployment:** Vercel (`vercel.json`)

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+)
- A [Firebase](https://firebase.google.com/) Project with Firestore & Authentication enabled
- A [Cloudinary](https://cloudinary.com/) account for image uploads

---

### 1. Clone the Repository
```bash
git clone https://github.com/Asceptic07/Ajeet-Home-Appliances-.git
cd Ajeet-Home-Appliances-
