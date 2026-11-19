# 🍔 Royal Kasi Bites

### Big Flavour. Made Kasi. 🔥

\<p align="center">   \<img src="[https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)" />   \<img src="[https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)" />   \<img src="[https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)" />   \<img src="[https://img.shields.io/badge/Responsive-Design-2EA44F?style=for-the-badge](https://img.shields.io/badge/Responsive-Design-2EA44F?style=for-the-badge)" />   \<img src="[https://img.shields.io/badge/Storage-LocalStorage-orange?style=for-the-badge](https://img.shields.io/badge/Storage-LocalStorage-orange?style=for-the-badge)" />   \<img src="[https://img.shields.io/badge/Currency-ZAR-blue?style=for-the-badge](https://img.shields.io/badge/Currency-ZAR-blue?style=for-the-badge)" /> \</p>

\<p align="center">   \<strong>A modern online food ordering and restaurant management platform bringing authentic Kasi flavours to a digital experience.\</strong> \</p>

---

## 📖 About the Project

Welcome to the official GitHub repository for **Royal Kasi Bites**, a modern, responsive online food ordering and restaurant management website designed to bring the authentic taste of Kasi food to customers through a convenient digital experience.

The platform allows customers to explore the menu, customise their orders, select collection or delivery, apply discount codes and track their orders.

It also includes a dedicated staff management portal with tools for managing orders, stock, promotions, customers and drivers.

**Project Highlights:**

- Online food ordering and checkout.
- Customer accounts and loyalty programme.
- Delivery and collection management.
- Order tracking and management.
- Restaurant administration dashboard.
- Inventory and promotional management.

---

## 🌟 Features

### 🛒 Customer Experience

- Modern, responsive website design.
- Food menu with product images, descriptions and pricing.
- Menu categories and search functionality.
- Shopping cart with quantity management.
- Customer checkout system.
- Customer name, surname and contact information.
- WhatsApp and alternative contact numbers.
- Customer accounts and Royal Rewards programme.

### 🚚 Delivery & Collection

- Free collection option.
- Distance-based delivery pricing:
  - 0–5 km: R15
  - 5–10 km: R25
  - 10–15 km: R35
  - Over 15 km: Fee confirmation required.
- Standard and priority delivery options.
- Delivery address and address type selection.
- Delivery instructions and special requests.

### 💳 Payment Options

Customers can select from:

- Cash.
- Card.
- Cash on delivery.
- Card on delivery.
- Online card payment (payment gateway integration required).

### 📦 Order Management & Tracking

- Unique order references.
- Order status tracking.
- Order preparation updates.
- Collection and delivery progress.
- Driver assignment.
- WhatsApp order follow-up.

### 🎁 Promotions & Customer Loyalty

- Discount and promotional codes.
- Percentage-based discounts.
- Fixed-value discounts.
- Minimum purchase requirements.
- Customer profiles.
- Royal Rewards points.
- Customer order history and spending totals.

---

## 📊 Restaurant Administration Portal

The staff portal provides dedicated management workspaces for restaurant operations.

| Module            | Functionality                                  |
| ----------------- | ---------------------------------------------- |
| Owner Dashboard   | View orders, active orders and order values    |
| Kitchen Display   | View orders and update preparation status      |
| Stock Management  | Monitor stock levels and low-stock alerts      |
| Promotions        | Create, activate and deactivate discount codes |
| Customers         | View customer profiles and loyalty points      |
| Driver Management | Register drivers and assign delivery orders    |
| Order Management  | Update order statuses and monitor progress     |

---

## 🎨 Design & Technology

The website features a modern dark-themed interface with gold and orange accents, inspired by the Royal Kasi Bites brand identity.

### Technology Stack

| Technology   | Purpose                                        |
| ------------ | ---------------------------------------------- |
| HTML5        | Website structure                              |
| CSS3         | Styling, responsive layouts and animations     |
| JavaScript   | Interactive functionality and order processing |
| LocalStorage | Browser-based demo data storage                |
| Google Fonts | DM Sans and Oswald typography                  |
| WhatsApp     | Customer communication and order follow-ups    |

---

## 🚀 Getting Started

Follow these steps to run Royal Kasi Bites locally.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/royal-kasi-bites.git
```

### 2. Navigate to the Project Directory

```bash
cd royal-kasi-bites
```

### 3. Launch the Website

Open the `index.html` file in your preferred browser.

Alternatively, use Visual Studio Code with the Live Server extension.

**Requirements:**

- A modern web browser.
- Visual Studio Code (optional).
- No build tools or package installation required for the current front-end version.

---

## 📁 Project Structure

```text
royal-kasi-bites/
│
├── index.html
├── README.md
└── assets/
    └── images/
```

The current website is delivered as a standalone HTML file, with its CSS, JavaScript and embedded product imagery included in the HTML.

The structure above represents a suggested GitHub repository organisation.

---

## 🔐 Demo Staff Access

The website includes a demonstration staff portal.

**Demo Access Code:**

```text
1234
```

Available workspaces:

- Owner Dashboard
- Kitchen Display
- Driver Dashboard
- Stock Management
- Promotions & Discounts
- Customer Accounts & Loyalty

---

## ⚙️ Configuration

The JavaScript configuration includes the WhatsApp contact number and payment gateway placeholder.

```javascript
const RKB_CONFIG = {
    whatsappNumber: '27790279426',
    paymentGatewayUrl: '',
    currency: 'ZAR'
};
```

Update these values when configuring the website for production.

---

## ⚠️ Production Deployment & Future Improvements

The current implementation is a front-end demonstration. Several features use browser LocalStorage rather than a central database.

Before using the platform for actual restaurant operations, the following integrations are recommended:

| Component         | Recommended Improvement                             |
| ----------------- | --------------------------------------------------- |
| Backend           | Secure server-side application                      |
| Database          | Centralised customer, order and stock storage       |
| Online Payments   | PayFast or Yoco integration                         |
| Authentication    | Secure customer and staff login                     |
| Order Tracking    | Real-time order status updates                      |
| WhatsApp          | Official WhatsApp Business API                      |
| Driver Management | Centralised driver assignments and delivery updates |

**Security Notice:** The existing demonstration staff PIN is not secure authentication and should not be used to protect a live administration system.

---

## 🌍 Deployment

Royal Kasi Bites can be hosted using:

- GitHub Pages
- Netlify
- Vercel
- Any web hosting provider supporting static HTML websites

### Deploy Using GitHub Pages

1. Upload the website files to your GitHub repository.
2. Open the repository's **Settings**.
3. Select **Pages**.
4. Under Build and Deployment, select **Deploy from a branch**.
5. Choose the `main` branch.
6. Select the `/ (root)` folder.
7. Click **Save**.

GitHub will generate a public website URL once deployment is complete.

---

## 📍 Business Information

### Royal Kasi Bites

📍 **Business Address**

Front of 46 Anderson Street
Promenade Shopping Centre – Kiosk D
Nelspruit, South Africa.

📞 **Contact Numbers**

- 079 027 9426
- 076 770 1755

💬 **WhatsApp:** [Contact Royal Kasi Bites](https://wa.me/27790279426)

---

## 🎯 Project Objective

The objective of Royal Kasi Bites is to create a convenient digital restaurant platform that improves customer ordering, simplifies restaurant operations and provides a foundation for future business growth.

The platform aims to combine online food ordering, customer engagement, delivery coordination, inventory management and restaurant administration into one integrated experience.

---

## 📄 License

**Copyright © 2026 Royal Kasi Bites.**

All rights reserved.

Please contact the business owner for permission before redistributing, modifying or commercially using this project.

---

\<p align="center">   \<strong>ROYAL KASI BITES\</strong>   \<br/>   🍔 BIG FLAVOUR. MADE KASI. 🔥   \<br/>\<br/>   \<i>Bringing the taste of Kasi closer to you.\</i> \</p>
