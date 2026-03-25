# Client Commerce Case Study

Public case study for a client-facing e-commerce platform built and deployed for **AmJes Couture**, a medical wear brand.

## Project Summary

This project involved designing and shipping a production-ready commerce experience for a real business. The platform combines a polished storefront with secure checkout, customer accounts, order tracking, and an admin dashboard for daily operations.

Because this was developed for a client, the production source code remains private. This repository exists as a professional case study that documents the scope, engineering decisions, and final product experience.

## My Role

I built and deployed the platform end to end as the developer responsible for:

- Frontend implementation
- Backend integration
- Authentication and authorization
- Payment integration
- Order persistence and tracking
- Admin tooling
- Deployment and production configuration

## What I Built

### Customer Experience

- Responsive storefront for browsing medical scrubs
- Interactive set builder for selecting tops and bottoms
- Authentication with email/password and Google sign-in
- Three-step checkout flow
- Paystack payment processing
- Customer order history
- Order tracking with unique tracking numbers
- Transactional email updates after purchase and status changes

### Admin Experience

- Secure admin-only dashboard
- Product creation, editing, and deletion
- Price and stock management
- Product image handling
- Order management and status updates
- Customer notification triggers from admin actions

## Stack

- **Next.js 15**
- **React 19**
- **TypeScript**
- **Supabase** for auth, database, and storage
- **Paystack** for payments
- **Resend** for transactional email delivery
- **Vercel** for deployment

## Engineering Highlights

- Server-side Paystack verification before saving paid orders
- Supabase Row Level Security to protect customer order access
- Admin route and action protection based on authenticated identity
- Server-authoritative pricing to prevent checkout tampering
- Tracking-number generation for customer order lookup
- Real operational workflows for product edits, payments, and order updates

## Screenshots

### Storefront

![Homepage](assets/screenshots/home.png)

![Products](assets/screenshots/products.png)

![Product Detail / Selection Flow](assets/screenshots/product-detail.png)

### Checkout

![Checkout Shipping Step](assets/screenshots/checkout-shipping.png)

![Checkout Review Step](assets/screenshots/checkout-review.png)

### Operations

![Admin Dashboard](assets/screenshots/admin-dashboard.png)

![Orders and Tracking](assets/screenshots/orders-tracking.png)

## Project Outcome

The finished platform supports real business operations, not just a static storefront. It gives the client a live commerce workflow covering product management, secure payments, customer order visibility, and operational follow-up from a single system.

## Note

Source code is private because this was developed as a client project.
