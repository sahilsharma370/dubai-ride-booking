# Dubai Ride Booking Platform

A full-stack ride-booking web application built for a real Dubai-based transportation business — replacing a manual phone-based booking system with an online platform where customers can browse drivers, check real-time availability, and book rides by date and time.

> **Status: In Development** — April 2026 – Present

---

## About the Project

This platform was built to solve a real operational problem: a Dubai transportation business was managing all bookings through manual phone calls, with no way for customers to check availability or book online.

The system replaces this entirely — customers can browse available drivers, see real-time slot availability, and complete bookings online or via cash-on-delivery. The business owner gets a full admin dashboard to manage drivers, bookings, and operations.

---

## Features

- **Driver browsing** — customers can view available drivers and vehicles
- **Real-time availability** — live slot checking by date and time
- **Multi-driver fleet system** — owner can onboard partner drivers, so customers can still book when the primary vehicle is occupied
- **Dual payment support** — online payment and cash-on-delivery for Dubai's diverse customer base
- **OpenAI-powered chatbot** — handles customer inquiries about bookings, availability, and services
- **WhatsApp Business API notifications** — automated booking confirmations and updates
- **Admin dashboard** — full control over bookings, drivers, and operations
- **Responsive design** — works across desktop and mobile

---

## Tech Stack

| Technology | Purpose |
|---|---|
| React | Frontend UI |
| Node.js | Backend API |
| PostgreSQL | Database |
| Supabase | Hosted database + auth |
| OpenAI API | Customer inquiry chatbot |
| WhatsApp Business API | Booking notifications |
| Vercel | Deployment |

---

## Architecture

```
├── client/                 # React frontend
│   ├── components/         # UI components (booking form, driver cards, etc.)
│   ├── pages/              # Route pages
│   └── utils/              # API calls, helpers
├── server/                 # Node.js backend
│   ├── routes/             # API endpoints
│   ├── controllers/        # Business logic
│   └── db/                 # PostgreSQL queries
└── admin/                  # Admin dashboard
```

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/sahilsharma370/dubai-ride-booking.git
cd dubai-ride-booking

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your Supabase, OpenAI, and WhatsApp API keys

# Run development server
npm run dev
```

---

## Status

| Feature | Status |
|---|---|
| Booking flow (browse, select, confirm) | 🔨 In Progress |
| Multi-driver fleet system | 🔨 In Progress |
| Admin dashboard | 🔨 In Progress |
| OpenAI chatbot | 🔨 In Progress |
| WhatsApp notifications | 📋 Planned |
| Payment integration | 📋 Planned |

---

## Author

**Sahil Sharma** — [github.com/sahilsharma370](https://github.com/sahilsharma370) · [linkedin.com/in/sahillsharma](https://linkedin.com/in/sahillsharma)
