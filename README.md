#  AfaqMall
##  Overview
AfaqMall is a modern e-commerce web application developed to provide users with a smooth online shopping experience. The system allows users to browse products, manage shopping carts, complete secure checkout operations, and receive smart product recommendations.
The platform also provides administrative functionalities for managing products and orders, in addition to notification integration using Telegram Bot.
---
#  Features
##  User Features
* User Registration & Authentication
* Browse Categories and Products
* View Product Details
* Add Products to Cart
* Update Cart Quantities
* Remove Products from Cart
* Checkout & Payment
* Product Rating System
* AI-Based Product Recommendations
---
##  Shopping Features
* Smart Product Organization
* Automatic Total Price Calculation
* Delivery Information Management
* Multiple Payment Methods
* Responsive Shopping Experience
---
##  Payment Integration
* PayPal Integration
* ShamCash Integration
* Secure Checkout Process
---
##  Admin Features
* Product Management (Add / Edit / Delete)
* Category Management
* Order Management
* Dashboard Access Control
---
##  System Features
* Telegram Bot Notifications
* Database Order Storage
* Role-Based Access Control
* Secure Authentication
---
##  system Architecture
AfaqMall follows a layered system architecture combined with a Client–Server architecture model to ensure scalability, maintainability, and clear separation of concerns.

 Client Side (Frontend)
The client side is developed using Next.js and represents the user interface of the system. It is responsible for:
Displaying products and categories
Handling user interactions
Managing shopping cart operations
Sending HTTP requests to the server
Providing a responsive and interactive UI
The client communicates with the backend through API requests.
Server Side (Backend)
The server side handles the core business logic of the system. It is responsible for:
User authentication and authorization
Product and category management
Order processing
Payment handling
Database communication
Sending notifications via Telegram Bot
Providing AI-based recommendations
The server processes requests received from the client and returns appropriate responses.
Database Layer
The system uses Supabase as the backend and database service to store:
Users
Products
Categories
Orders
Ratings
Comments
External Services
The system integrates with several external services:
Payment Gateways
PayPal
ShamCash
Used for secure online transactions

#  Technologies Used

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Next.js          | Frontend Framework        |
| TypeScript       | Application Logic         |
| JavaScript       | Client-side Functionality |
| Supabase         | Backend & Database        |
| Tailwind CSS     | UI Styling                |
| PayPal API       | Online Payment            |
| Telegram Bot API | Notifications             |
| Vercel           | Deployment                |

#  Project Structure
```bash
AfaqMall/
│
├── app/
├── components/
├── pages/
├── public/
├── styles/
├── lib/
├── supabase/
├── api/
└── README.md
```
#  Installation & Setup

## 1️ Clone the Repository
```bash
https://github.com/raghadmjbel/afaqmallraghad
```
## 2️ Navigate to Project Folder
```bash
cd afaqmallraghad
```
## 3️ Install Dependencies
```bash
npm install --legacy-peer-deps
```
## 4️ Run the Development Server
```bash
npm run dev
```
## 5️ Open in Browser
```bash
http://localhost:3000
```
# Telegram Notification System
When a new order is completed, the system automatically sends a notification to the admin using Telegram Bot integration.
#  Future Improvements
* Advanced AI Recommendation Engine
* Multi-language Support
* Mobile Application Version
* Order Tracking System
* Advanced Analytics Dashboard
---
#  Developer
**Raghad Mjbel**



