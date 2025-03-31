# frontend_guidelines_document.mdc v.1

number: 4
type: RULE - frontend_guidelines_document.mdc

ALWAYS REMEMBER - This rule is attached to every chat and command/request

UPDATE THIS rule if user requested changes to the project requirement, etc.

# Frontend Guidelines Document

This document outlines the frontend architecture, design principles, and technologies used in the At Code Product hunt platform, even without a technical background.

# Frontend Architecture

The frontend is built using Next.js 14 with App Router, using TypeScript for robust type-checking and code quality. We rely on a component-based architecture to keep the codebase modular and reusable. Some key points:

- **Component Structure** - Use a component-based architecture with reusable components (e.g., buttons, cards, modals) to ensure consistency across the platform.
- **File Structure** - Organize files into `/components`, `/pages`, `/lib`, `/styles`, and `/public` directories for better organization.
- **State Management** - Use React's built-in state management (useState, useReducer) for simple state management, and Zustand for complex state management.
- **Routing** - Use Next.js App Router for routing, with dynamic routes for listings (e.g., `/listings/[id]`) and static routes for static pages (e.g., `/about`).

# Design Guidelines

- **Typography** - Use Inter font for all text, with a font size of 16px for body text, 24px for headings, and 14px for secondary text.
- **Color Palette** - Use a neutral color palette with primary colors (#1A1A1A, #FFFFFF), accent colors (#4A90E2, #50E3C2), and background colors (#F5F5F5, #E5E5E5).
- **Spacing** - Use a 4px grid system for spacing and padding (e.g., 4px, 8px, 16px, 24px, 32px).
- **Responsive Design** - Ensure all components are responsive and mobile-friendly, with a mobile-first approach.
- **Accessibility** - Follow WCAG 2.1 guidelines for accessibility, including keyboard navigation, screen reader support, and sufficient color contrast.

# Scalability and Maintainability

- **Modular Components** - Build reusable components to ensure consistency and reduce duplication.
- **Code Consistency** - Enforce code consistency using ESLint and Prettier for linting and formatting.
- **Performance** - Optimize performance by lazy-loading images, using Next.js Image component, and minimizing re-renders.