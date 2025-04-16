# 🍽️ FoodOnline - Full Stack Food Delivery Web App (Django)

A fully responsive, real-time, location-based food delivery web application built using **Django**, **PostgreSQL**, **AJAX**, and deployed on a **Linode VPS** with **Gunicorn**, **Nginx**, and **SSL**.

---

## 🚀 Live Demo
👉 [FoodOnline live site link here](http://127.0.0.1:8000/) 

---

## 💡 Key Features

### 🔐 Authentication
- Register/login with email verification
- Separate login for **Customers** and **Vendors**
- Email templates for order confirmation & vendor notifications

### 🛍️ Marketplace
- Browse restaurants by food category
- View restaurant profiles & food items
- Smart search + location-based search using GeoDjango
- Google Autocomplete for address input

### 🛒 Cart & Checkout
- Add/remove food items via AJAX
- Dynamic cart updates without page reload
- Razorpay integration for payments
- Secure order placement & unique order number generation

### 📦 Orders
- Track recent and past orders
- Dynamic tax calculation
- Many-to-many order management between customers & vendors

### 📍 Location & Business Hours
- Display nearby restaurants using GeoDjango + user geolocation
- Vendor-specific business hours with real-time "Open/Closed" badge

### 📊 Dashboards
- Admin, Vendor & Customer dashboards
- Real-time data tables for vendor order management
- Monthly revenue tracking using custom middleware

### 📱 Responsive Design
- Fully mobile-friendly with intuitive UI

---

## 🛠️ Tech Stack

| Frontend         | Backend             | DevOps & Deployment         |
|------------------|---------------------|-----------------------------|
| HTML, CSS, JS     | Django, PostgreSQL  | Linode VPS, Gunicorn, Nginx |
| Bootstrap, AJAX  | GeoDjango, GDAL     | Let's Encrypt SSL, Git      |
| SweetAlert       | Razorpay            | Ubuntu Server               |

---

## 🐘 Database Models Overview
- User (AbstractBaseUser)
- Vendor
- Customer
- FoodItem
- Cart
- Order & OrderedFood
- OpeningHour
- Tax

---

## 🧪 Testing
- Manually tested across different roles & use cases
- Mobile responsiveness verified
- Order flow tested end-to-end with Razorpay (sandbox)

---

## 🌐 Deployment
Deployed on a Linode VPS with:
- PostgreSQL + PostGIS
- Gunicorn for WSGI server
- Nginx as reverse proxy
- SSL via Let's Encrypt
- Git integration for CI/CD

---

## 🤝 Author

**Lakshmi S Belgavi**  
💻 Aspiring Software Engineer | Data Enthusiast 
📬 [Email](lakshmisb282003@email.com) | [LinkedIn](https://www.linkedin.com/in/lakshmi-s-belgavi-505768283/) 

---

## ⭐️ Show Your Support
If you like this project:
- Give it a ⭐ on GitHub  
- Fork it and build your own version  
- Share with your friends or tech community!

---

