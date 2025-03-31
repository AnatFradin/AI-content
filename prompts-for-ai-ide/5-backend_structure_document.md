# backend_structure_document.mdc v.1

number: 5
type: RULE - backend_structure_document.mdc

ALWAYS REMEMBER - This rule is attached to every chat and command/request

UPDATE THIS rule if user requested changes to the project requirement, etc.

# Project Overview

- At Code Product hunt is a web-based marketplace where no-code developers and Indie hackers can list their startups for sale, like name, website, app, industry, revenue, user base, and single-while allowing buyers to explore listings using conversations and negotiations about potential transactions. The platform leverages modern authentication, real-time database, and secure payment processing to ensure a seamless user experience.

# Backend Structure/Architecture Specific

# Directory Structure

- **API Routes** - Next.js 14 App Router is used for the `/api` route handlers with nested route folders. For example:
 - `/api/listings` - Handles listing creation, retrieval, and deletion.
 - `/api/listings/[id]` - Handles specific listing retrieval and updates.
 - `/api/auth/[...clerk]` - Handles Clerk authentication routes.
 - `/api/payments` - Handles Stripe payment processing.
- **Core Directories**
 - `/server` - Contains server-side logic, such as API routes, middleware, and utility functions.
 - `/lib` - Contains utility functions, such as database queries, API calls, and authentication logic.
 - `/db` - Contains database schema and migrations (if applicable).

# Serverless Structure

- **Authentication** - Next.js 14 API routes with Route Handlers for backend integrations such as Supabase and Clerk for user authentication.
- **Database** - Supabase (PostgreSQL) for storing user data, listings, and chat messages.
- **Storage** - Supabase Storage for storing images and other assets uploaded by users.
- **Payment Processing** - Stripe for payment processing, including listing fees and transaction fees.
- **Real-time Features** - Supabase Realtime for real-time chat and notifications.