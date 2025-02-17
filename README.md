# Full-Stack Web Application

This repository serves as a starter template for a **Next.js App Router** project. It provides the foundational structure for building a scalable and maintainable web application with authentication, routing, and Tailwind CSS for styling.

## Features

- **Next.js App Router**: Utilizes Next.js's built-in App Router for structured navigation.
- **Authentication**: Configured via `auth.config.ts` and `auth.ts` for handling user authentication.
- **Middleware**: Uses `middleware.ts` for route protection and access control.
- **Tailwind CSS**: Integrated for easy styling and UI consistency.
- **Scalable File Structure**: Organized directory layout for better maintainability.

---

## 🛠 Installation & Setup

To get started with the project locally, follow these steps:



📂 Project Structure
Full-stack-web-application
│── app/                 # Main application pages & components
│── public/              # Static assets (images, fonts, etc.)
│── auth.config.ts       # Authentication configurations
│── auth.ts              # Authentication logic
│── middleware.ts        # Middleware for request handling
│── next.config.ts       # Next.js configuration
│── tailwind.config.ts   # Tailwind CSS configuration
│── package.json         # Project dependencies



🚀 Routing
The application uses Next.js App Router, meaning:

Each page is a React component inside the app/ directory.
Pages are automatically mapped to their respective routes.
Nested directories create dynamic routes for better scalability.

🔑 Authentication
The project includes authentication setup:

auth.config.ts: Defines authentication providers and settings.
auth.ts: Handles login, logout, and session management.
middleware.ts: Ensures protected routes are only accessible to authenticated users.


🎨 Styling
This project uses Tailwind CSS for styling. The configuration can be found in:
tailwind.config.ts

Custom styles and global themes can be modified directly in this file.

