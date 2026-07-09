# 🛍️ Nexora

A modern full-stack e-commerce web application built with **Django** and **PostgreSQL**, providing a complete online shopping experience with authentication, shopping cart, checkout, order management, and an admin dashboard.

---

## 🌐 Live Demo

🔗 **Live Website:** 
https://nexora-ecommerce.onrender.com/

## 💻 GitHub Repository

🔗 https://github.com/Stephenpaul07/nexora-ecommerce

---

# 🎥 Demo

Watch the complete application walkthrough here:

📺 **Demo Video:** 
https://youtu.be/MZf12t-tGiA


- Home Page
- Product Listing
- Product Details
- Shopping Cart
- Checkout
- User Dashboard
- Admin Dashboard

---

# ✨ Features

## User Features

- User Registration & Login
- User Dashboard
- Password Change
- Product Search
- Product Categories
- Product Variations
- Shopping Cart
- Quantity Management
- Checkout
- Cash on Delivery (COD)
- Order History
- Order Details
- Product Reviews & Ratings
- Responsive Design

---

## Admin Features

- Product Management
- Category Management
- Order Management
- Customer Management
- Review Management
- Inventory Management

---

# 🛠 Tech Stack

### Backend
- Python
- Django 6

### Database
- PostgreSQL

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- jQuery

### Deployment
- Render
- Gunicorn
- WhiteNoise

### Version Control
- Git
- GitHub

---

# 📂 Project Structure

```
Nexora
│
├── accounts/
├── carts/
├── category/
├── config/
├── media/
├── orders/
├── static/
├── store/
├── templates/
│
├── manage.py
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Stephenpaul07/nexora-ecommerce.git
```

Navigate to the project

```bash
cd nexora-ecommerce
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the environment

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ⚙️ Environment Variables

Create a `.env` file in the project root.

```env
SECRET_KEY=your-secret-key

DEBUG=True

DATABASE_URL=your_database_url

EMAIL_HOST_USER=your_email

EMAIL_HOST_PASSWORD=your_password
```

---

# 🗄 Database

Run migrations

```bash
python manage.py migrate
```

Create a superuser

```bash
python manage.py createsuperuser
```

Run the server

```bash
python manage.py runserver
```

---

# 📦 Deployment

This project is deployed using:

- Render
- PostgreSQL
- Gunicorn
- WhiteNoise

---

# 📈 Future Enhancements

- Online Payments (PhonePe / Razorpay)
- Wishlist
- Coupons & Discounts
- Product Recommendations
- Cloudinary / AWS S3 Media Storage
- REST API using Django REST Framework
- Docker Support
- CI/CD Pipeline

---

# 🎯 Learning Outcomes

This project helped me gain practical experience in:

- Django Development
- PostgreSQL Integration
- Authentication & Authorization
- Session Management
- Shopping Cart Logic
- Order Processing
- Database Design
- Production Deployment
- Environment Configuration
- Debugging Production Issues

---

# 📄 License

This project is intended for educational and portfolio purposes.

---

# 👨‍💻 Author

**Stephen Kondeparthi**

LinkedIn:
https://www.linkedin.com/in/stephen-kondeparthi-35a2422b1/
GitHub:
https://github.com/Stephenpaul07

Email:
kondeparthistephen@gmail.com