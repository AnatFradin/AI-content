# cursorrules_document.mdc v.1

number: 6
type: RULE - cursorrules_document.mdc

ALWAYS REMEMBER - This rule is attached to every chat and command/request

UPDATE THIS rule if user requested changes to the project requirement, etc.

# Backend Structure Document

This document provides an overview of the backend setup for the At Code Product hunt platform. Our goal is to ensure that anyone can follow along, regardless of technical background.

# 1. Backend Architecture

The backend is built with a focus on scalability, maintainability, and performance. We have used a modular approach where each component is responsible for a specific part of the system. Here are a few key points:

- **Modular Structure** - Each feature (authentication, listings, chat, payments) is split into separate modules for better organization.
- **API Routes** - Use Next.js API routes for handling API requests, such as `/api/listings`, `/api/auth/[...clerk]`, and `/api/payments`.
- **Database** - Use Supabase (PostgreSQL) for storing user data, listings, and chat messages.
- **Storage** - Use Supabase Storage for storing images and other assets uploaded by users.
- **Authentication** - Use Clerk for user authentication, including Google OAuth.
- **Payment Processing** - Use Stripe for payment processing, including listing fees and transaction fees.

# Modern Framework

- **Tech Stack Highlights**
 - **Next.js 14** - For API routes and server-side rendering.
 - **Supabase** - For database, authentication, and storage.
 - **Clerk** - For user authentication.
 - **Stripe** - For payment processing.

# Deployment

- **Vercel** - The platform is deployed on Vercel for its ease of deployment, automatic scaling, and domain management.
- **Environment Variables** - Use environment variables for sensitive data, such as API keys, database URLs, and Stripe keys.
- **Monitoring** - Use Vercel Analytics for monitoring and performance tracking.