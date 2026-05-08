# Afaq Mall — Modern E-Commerce Platform

A modern and scalable e-commerce web application built using **Next.js**, **TypeScript**, and **Supabase** as a Backend-as-a-Service (BaaS).
> Designed to demonstrate real-world full-stack architecture and modern web development practices.
# Overview
Afaq Mall is a full-featured e-commerce platform that allows users to browse products, manage carts, and place orders seamlessly.
The system integrates a modern frontend with a backend service to ensure scalability and maintainability.
# Key Features
-  Product browsing by categories
- Search functionality
-  Shopping cart & checkout
-  User authentication (Login / Signup)
- Order management system
- Product ratings & recommendations
-  Notifications system
-  Fully responsive design(feature)
  # ech Stack

| Layer        | Technology |
|-------------|-----------|
| Frontend    | Next.js (App Router) |
| Language    | TypeScript |
| Styling     | CSS / Tailwind |
| Backend     | Supabase |
| Database    | PostgreSQL |
| Auth        | Supabase Auth |

# System Architecture

## Environment Variables
Create a `.env` file:
```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key

# Installation & Setup:
git clone https://github.com/your-username/afaqmall.git
cd afaqmall
npm install
npm run dev
# Project Structure
app/           → Application routes
components/    → UI components
lib/           → Business logic & Supabase integration
hooks/         → Custom hooks
styles/        → Global styles

-Project Goals:
Demonstrate full-stack development skills
Apply modern architectural patterns
Integrate frontend with backend services
Build a scalable and maintainable system

-Security Considerations:
API keys are stored in environment variables
Sensitive data is not exposed
Supabase security rules can be applied

-Author:
Raghad Mjbel
