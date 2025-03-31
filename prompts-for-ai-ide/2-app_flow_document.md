# app_flow_document.mdc v.1

number: 2
type: RULE - app_flow_document.mdc

ALWAYS REMEMBER - This rule is attached to every chat and command/request

UPDATE THIS rule if user requested changes to the project requirement, etc.

# Onboarding and Sign-up/Sign-in

When first time users visit the At Code Product hunt platform, they are greeted with a clean and welcoming Landing page on the website (e.g., localhost:3000). The page includes a clear call-to-action (CTA) to either sign up or sign in using Google authentication via Clerk, which ensures a simple and secure login process. New users are offered an onboarding flow to list their own startup if they are a seller. For those who already have an account, a simple sign-in button redirects them to the main dashboard. A password recovery process is in place that allows the user to reset their credentials and regain access with minimal hassle.

# Main Dashboard or Home Page

After signing in, users are taken directly to the main dashboard where they can start interacting with the platform. The dashboard acts as the central hub, providing quick access to key features like creating a new listing, browsing existing listings, accessing their profile, and viewing notifications. The navigation menu that provides direct access to every major part of the application, ensuring that users can easily move between exploring startup listings, accessing analytics, managing their chats. The main area of the dashboard displays a curated list of startup listings that match their criteria. The clear, minimalistic interface and neutral color palette ensure that users can focus on the content without distractions and keep user experience high.

# Detailed Features and Page Transitions

- **User Profile Section** - From the dashboard users can access their profile section to manage their account details, update their listings, and view their transaction history.
- **Listing Creation** - Sellers can create a new listing by filling out an easy-to-use form that asks for details about their startup. This form includes fields for the startup name, website, app, industry, revenue, user base, description, reason for selling, and images.
- **Search and Filter** - Buyers can use the search bar and filters to narrow down their choices, and can initiate communication with sellers directly from the listing page.
- **Chat System** - The chat system allows buyers and sellers to communicate directly within the platform, ensuring that all communication is secure and centralized.
- **Payment Integration** - The payment integration with Stripe allows users to pay for listing fees and transaction fees securely.