# tech_stack_document.mdc v.1

number: 3
type: RULE - tech_stack_document.mdc

ALWAYS REMEMBER - This rule is attached to every chat and command/request

UPDATE THIS rule if user requested changes to the project requirement, etc.

At Code Product hunt - Tech Stack document

This doc explains the technology choices for the At Code Product hunt platform, a marketplace for no-code developers and Indie hackers to list their startups for sale. Below, you'll find an overview of our technology choices, including the rationale behind each choice, to ensure the platform is scalable, secure, and user-friendly.

# Frontend Technologies

- **Next.js 14** (with App Router) - Popular framework helps build fast, dynamic websites and improves navigation. We use Next.js 14 for its performance, SEO benefits, and ability to handle both client-side and server-side rendering.
- **TypeScript** - Adds static types to JavaScript, improving code quality and reducing bugs. We use TypeScript for better type safety and catching potential errors early.
- **Tailwind CSS** - A utility-first CSS framework for rapid UI development. We use Tailwind CSS for its flexibility, ease of use, and ability to create responsive designs.
- **Shadcn UI** - A collection of reusable, lightweight components that add a modern touch to the visuals without overwhelming the codebase. We use Shadcn UI for its simplicity and ease of customization.
- **Lucide Icons** - A collection of simple, lightweight icons that add a modern touch to the visuals without overwhelming the codebase. We use Lucide Icons for their simplicity and ease of customization.

# Backend Technologies

- **Next.js API Routes** - Next.js API routes for backend logic, such as handling API requests, authentication, and data fetching.
- **Supabase** - An open-source Firebase alternative for database, authentication, and storage. We use Supabase for its ease of use, real-time capabilities, and scalability.
- **Clerk** - A user authentication and management platform. We use Clerk for its secure, user-friendly authentication flows, including Google OAuth.
- **Stripe** - A payment processing platform for handling payments. We use Stripe for its secure payment processing, subscription management, and ease of integration.

# Database and Storage

- **Supabase (PostgreSQL)** - A cloud-based PostgreSQL database for storing user data, listings, and chat messages. We use Supabase for its scalability, real-time capabilities, and ease of use.
- **Supabase Storage** - For storing images and other assets uploaded by users. We use Supabase Storage for its simplicity and integration with Supabase.

# Infrastructure

- **Vercel** - The platform is deployed on Vercel for its ease of deployment, automatic scaling, and domain management.