# Infinity 99 Realty

A modern real estate web application built with React, TypeScript, and Tailwind CSS that helps users explore residential and commercial properties.

## Features
- Property Listing
- Property Details
- Search & Filters
- Authentication
- Admin Dashboard
- Contact Forms
- Responsive UI

## Tech Stack
- React
- TypeScript
- Tailwind CSS
- React Router
- API Integration
- Firebase/Supabase (if used)

---

# Project Structure

src/
├── components/
├── pages/
├── layouts/
├── hooks/
├── services/
├── utils/
├── assets/
└── App.tsx

---

# Website Flow

Home (/)
│
├── About
│
├── Projects
│   ├── Residential
│   ├── Commercial
│   └── Project Details
│
├── Properties
│   ├── Buy
│   ├── Rent
│   └── Property Details
│
├── Blog
│   └── Blog Details
│
├── Contact
│
└── Login
    └── Dashboard

---

# Routing Explanation

| Route | Component | Purpose |
|--------|-----------|---------|
| / | Home | Landing page |
| /about | About | Company information |
| /projects | Projects | All projects |
| /project/:id | Project Details | Individual project |
| /contact | Contact | Inquiry form |
| ... | ... | ... |

---

# How the Application Works

1. User lands on Home.
2. Navbar provides navigation to all pages.
3. Clicking a property opens its detail page.
4. Forms send data to the backend.
5. Authentication protects dashboard routes.
6. Admin manages listings from dashboard.

---

# Folder Explanation

## components
Reusable UI components like Navbar, Footer, Cards.

## pages
Contains all application pages.

## layouts
Common page layouts.

## services
API calls.

## hooks
Custom React hooks.

## utils
Helper functions.

---

# Installation

npm install
npm run dev

---

# Environment Variables

VITE_API_URL=
...

---

# Future Improvements

- Payment Gateway
- Property Comparison
- Favorites
- Google Maps
- AI Property Recommendation
