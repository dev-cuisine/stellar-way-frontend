#  Stellar Way — E-Commerce & Delivery Platform

A full-featured e-commerce and delivery management platform built with **Next.js 16**, featuring real-time order tracking, live rider messaging, rider application management, and a comprehensive admin dashboard.

---

##  Description

Stellar Way is a full-stack delivery platform connecting customers, riders, and admins in real time. Customers place and track orders on a live map, riders manage deliveries and chat with customers, and admins oversee everything through a powerful dashboard — all powered by Socket.IO and built with Next.js 16.

---

##  Features

###  Customer
- Browse products and place orders
- Real-time order tracking with live map view
- Live chat with assigned delivery rider
- Order history and status updates
- QR code support for orders

###  Rider
- Apply to become a delivery rider
- Accept and manage assigned deliveries
- Real-time location sharing
- In-app messaging with customers
- Delivery history and earnings overview

###  Admin
- Full order management dashboard
- Rider application review & approval
- User and rider account management
- Analytics and reporting with charts
- Real-time monitoring of all active deliveries

---

##  Live URL

> [https://stellar-way-coral.vercel.app](https://stellar-way-coral.vercel.app)

---

## 🔑 Credentials

| Role | Email | Password |
|---|---|---|
| Customer | `imam@gmail.com` | `123456` |
| Rider | `imam1@gmail.com` | `123456` |



---

##  Installation & Setup

### Prerequisites

- **Node.js** v18+
- **npm** / yarn / pnpm / bun

### Steps

```bash
git clone https://github.com/dev-cuisine/stellar-way-frontend
cd stellar-way-frontend
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

##  Environment Variables

Create a `.env.local` file in the project root:

```env
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret

NEXT_PUBLIC_API_URL=http://localhost:5000/api/v1
NEXT_PUBLIC_SOCKET_URL=http://localhost:5000
```


---

##  Tech Stack

| Layer | Technology |
|---|---|
| Framework | Next.js 16 (App Router) |
| Language | TypeScript |
| Styling | Tailwind CSS v4 |
| Auth | NextAuth.js |
| Data Fetching | TanStack React Query + Axios |
| Real-time | Socket.IO Client |
| Maps | Leaflet + React Leaflet |
| Charts | Recharts |
| Forms | React Hook Form |
| Animations | Framer Motion, GSAP |
| Notifications | React Hot Toast, SweetAlert2 |
| PDF/Export | jsPDF, html2canvas, modern-screenshot |
| UI Components | Lucide React, React Icons, Swiper |

---

##  License

This project is private and proprietary. All rights reserved.

---

> Built with  using [Next.js](https://nextjs.org)
