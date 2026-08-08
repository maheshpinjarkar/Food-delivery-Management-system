
# 🍔 Food Delivery Management System

A modern **single-vendor food delivery platform** designed to help restaurants manage online food orders, customers, riders, deliveries, and day-to-day operations from a centralized system.

The platform includes dedicated interfaces for **customers, delivery riders, and restaurant administrators**, providing a complete food-ordering and delivery workflow.

> **Note:** This repository is based on the Enatega Single Vendor Food Delivery Solution and is presented here for educational, development, and portfolio purposes. Please refer to the original project license and attribution requirements before redistributing or commercializing the code.

---

## 🚀 Key Features

### 👨‍💼 Admin Dashboard

* Restaurant administration
* Order management
* Rider management
* Customer management
* Order analytics
* Delivery management
* Responsive dashboard
* Order status tracking
* Restaurant operations management

### 👨‍🍳 Customer App

* Browse food items
* Customize food selections
* Add items to cart
* Place orders
* Order tracking
* Ratings and reviews
* Address/GPS integration
* Email order confirmation
* Social authentication support
* Multi-language support

### 🛵 Rider App

* Accept delivery orders
* Manage assigned deliveries
* Customer location tracking
* Google Maps integration
* Location-based delivery zones
* Delivery status management

---

## ⭐ Main Functionalities

* 📦 Complete order management
* 💳 Payment integration
* 📍 GPS-based address detection
* 🗺️ Delivery location tracking
* ⭐ Ratings and reviews
* 🔔 Push notifications
* 📧 Email notifications
* 🔐 Authentication
* 🌎 Multi-language support
* 📱 Mobile-responsive dashboard
* 🍕 Food item variations
* 📊 Analytics dashboard
* 👨‍🚴 Dedicated rider application
* 👤 Customer account management

---

## 🏗️ System Architecture

The application is divided into three major components:

```text
                    FOOD DELIVERY SYSTEM
                            │
             ┌──────────────┼──────────────┐
             │              │              │
             ▼              ▼              ▼
       Customer App     Admin Panel     Rider App
             │              │              │
             └──────────────┼──────────────┘
                            │
                            ▼
                     Backend / API
                            │
                            ▼
                         Database
```

### Modules

| Module          | Purpose                                  |
| --------------- | ---------------------------------------- |
| Customer App    | Browse menu and place orders             |
| Admin Dashboard | Manage restaurant operations             |
| Rider App       | Manage deliveries                        |
| Backend/API     | Application business logic               |
| Database        | Store users, orders and application data |

---

## 🛠️ Technology Stack

### Frontend

* React.js
* React Native
* React Router
* React Navigation
* Reactstrap

### Backend

* Node.js
* Express.js
* GraphQL
* Apollo GraphQL

### Database

* MongoDB

### Mobile Development

* Expo
* React Native

### Authentication & Services

* Firebase
* Google Authentication
* Facebook Authentication
* GPS / Maps integration
* Push Notifications

### Additional Tools

* Amplitude Analytics
* Stripe
* PayPal
* Email integration
* Localization / Multi-language support

The technology stack is based on the technologies documented by the original project.

---

## 📂 Project Components

```text
Food Delivery System
│
├── Customer Application
│   ├── Food browsing
│   ├── Cart
│   ├── Checkout
│   ├── Order tracking
│   └── Reviews & ratings
│
├── Rider Application
│   ├── Order acceptance
│   ├── Delivery management
│   ├── Location tracking
│   └── Customer navigation
│
└── Admin Dashboard
    ├── Order management
    ├── Customer management
    ├── Rider management
    ├── Analytics
    └── Restaurant management
```

---

## ⚙️ Installation

### Prerequisites

Make sure the following are installed:

* Node.js
* npm or Yarn
* MongoDB
* Expo CLI (for mobile applications)

The original documentation specifies Node.js **14.x–16.x** for this project.

### Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/food-delivery-management-system.git
cd food-delivery-management-system
```

### Install Dependencies

```bash
npm install
```

Or:

```bash
yarn install
```

### Start Development Server

```bash
npm start
```

Or:

```bash
yarn start
```

The repository's contributing guide also documents the basic `npm install` and `npm start` workflow.

---

## 📸 Screenshots

Add your own screenshots here after running the project:

### Customer Application

```text
docs/screenshots/customer-app.png
```

### Rider Application

```text
docs/screenshots/rider-app.png
```

### Admin Dashboard

```text
docs/screenshots/admin-dashboard.png
```

Example Markdown:

```markdown
![Customer App](docs/screenshots/customer-app.png)

![Rider App](docs/screenshots/rider-app.png)

![Admin Dashboard](docs/screenshots/admin-dashboard.png)
```

The original repository also documents screenshots for the customer app, rider app, and dashboard.

---

## 🔐 Security

Do not commit sensitive credentials such as:

* Database passwords
* Firebase credentials
* API keys
* Payment gateway keys
* Email passwords
* Authentication secrets

Use environment variables or a secure configuration system for production deployments.

---

## 📈 Future Improvements

* Advanced restaurant analytics
* Real-time delivery tracking
* AI-powered food recommendations
* Advanced order prediction
* Automated customer support chatbot
* Improved payment gateway integration
* Advanced delivery optimization
* Restaurant inventory management
* Coupon and promotional campaign management
* Cloud deployment
* Docker-based deployment
* Advanced role-based access control

---

## 🎯 Project Objective

The goal of this project is to demonstrate a complete **restaurant food delivery ecosystem** where customers can order food, administrators can manage restaurant operations, and riders can handle deliveries through dedicated applications.

This project demonstrates practical experience with:

* Full-stack application architecture
* REST/GraphQL APIs
* Mobile application development
* Database integration
* Authentication
* Payment integration
* GPS/location services
* Real-time order workflows
* Admin dashboard development
* Multi-platform application design

---

## 🤝 Contributing

Contributions, bug reports, feature suggestions, and improvements are welcome.

For bug reports, provide a clear description, reproduction steps, logs, screenshots, and other useful diagnostic information.

---

## 📄 License

This project is distributed under the license included in this repository.

Please review the `LICENSE` file before using, modifying, or redistributing the project.

---

## ⚠️ Disclaimer

This repository is based on the **Enatega Single Vendor Food Delivery Solution**. The original project documentation states that the frontend source code is open source while the backend/API is proprietary and available under a paid license.

Make sure you comply with the original project's license, attribution, and usage terms when publishing or modifying this repository.

---

## 👨‍💻 Developer

**Mahesh**

B.Tech Cyber Security Engineer

GitHub: `https://github.com/YOUR-USERNAME`

---

⭐ If you find this project useful, consider giving the repository a star.
