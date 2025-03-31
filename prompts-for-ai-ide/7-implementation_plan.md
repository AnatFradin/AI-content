# implementation_plan.mdc v.1

number: 7
type: RULE - implementation_plan.mdc

ALWAYS REMEMBER - This rule is attached to every chat and command/request

UPDATE THIS rule if user requested changes to the project requirement, etc.

# 50-Step Implementation Plan

This document provides a 50-step plan to code the At Code Product hunt platform end-to-end. This plan ensures that the AI coding model follows a structured approach to building the app, minimizing errors and ensuring consistency.

# Step 1: Project Setup

1. Initialize a new Next.js 14 project with App Router.
2. Install TypeScript, Tailwind CSS, and Shadcn UI.
3. Set up ESLint and Prettier for code linting and formatting.
4. Configure environment variables for Supabase, Clerk, and Stripe.
5. Set up a basic project structure with `/components`, `/pages`, `/lib`, `/styles`, and `/public` directories.

# Step 2: Authentication Setup

6. Integrate Clerk for user authentication with Google OAuth.
7. Set up Clerk middleware to protect routes.
8. Create a sign-in and sign-up page with Clerk components.
9. Implement a password recovery flow.
10. Test authentication flows and ensure secure user sessions.

# Step 3: Database and Storage Setup

11. Set up Supabase (PostgreSQL) for the database.
12. Create database tables for users, listings, and chat messages.
13. Set up Supabase Storage for storing images and assets.
14. Write utility functions for database queries in `/lib/db`.
15. Test database connectivity and ensure data is being stored correctly.

# Step 4: Backend API Routes

16. Create Next.js API routes for listings (`/api/listings`).
17. Implement CRUD operations for listings (create, read, update, delete).
18. Create API routes for chat messages (`/api/chat`).
19. Integrate Supabase Realtime for real-time chat.
20. Test API routes and ensure they are secure and functional.

# Step 5: Frontend Development

21. Build a landing page with a clear CTA for sign-up/sign-in.
22. Create a dashboard page for logged-in users.
23. Build a listing creation form with fields for name, website, app, industry, revenue, user base, description, reason for selling, and images.
24. Create a listing page with search and filter functionality.
25. Build a chat interface for buyers and sellers to communicate.
26. Ensure all components are responsive and mobile-friendly.

# Step 6: Payment Integration

27. Integrate Stripe for payment processing.
28. Create a payment page for listing fees and transaction fees.
29. Implement Stripe webhooks for payment events.
30. Test payment flows and ensure secure transactions.

# Step 7: Testing and Optimization 

31. Write unit tests for API routes and utility functions.
32. Test the frontend for responsiveness and accessibility.
33. Optimize performance by lazy-loading images and minimizing re-renders.
34. Ensure the app meets WCAG 2.1 accessibility guidelines.
35. Test the app on multiple devices and browsers.

# Step 8: Deployment

36. Deploy the app on Vercel.
37. Set up domain and SSL on Vercel.
38. Configure Vercel Analytics for monitoring.
39. Test the deployed app for functionality and performance.
40. Fix any bugs or issues found during testing.

# Step 9: Post-Deployment

41. Monitor user feedback and analytics.
42. Fix any bugs or issues reported by users.
43. Add new features based on user feedback.
44. Optimize the app for performance and scalability.
45. Document the codebase and update the knowledge base.

# Step 10: Maintenance

46. Regularly update dependencies to the latest versions.
47. Monitor for security vulnerabilities and apply patches.
48. Back up the database and storage regularly.
49. Scale the app as user base grows.
50. Continuously improve the app based on user feedback.