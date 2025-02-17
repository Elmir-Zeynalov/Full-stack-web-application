# Full-Stack Web Application 🚀

This repository serves as a **starter template** for a Next.js **App Router** project. It provides a scalable and maintainable structure with authentication, routing, and Tailwind CSS for styling.

## ✨ Features

- 🔹 **Next.js App Router** – Efficient, structured navigation.
- 🔹 **Authentication** – Configured via `auth.config.ts` and `auth.ts`.
- 🔹 **Middleware Protection** – Uses `middleware.ts` for access control.
- 🔹 **Tailwind CSS** – Utility-first styling for a modern UI.
- 🔹 **Scalable Project Structure** – Organized and maintainable codebase.

---

## 🛠 Built With

- **Next.js** – React framework for SSR & static sites.
- **Tailwind CSS** – Modern, utility-based styling.
- **TypeScript** – Ensures type safety.
---


## 🛠 Installation & Setup

Follow these steps to get started:

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/Elmir-Zeynalov/Full-stack-web-application.git
cd Full-stack-web-application
```

### 2️⃣ Install Dependencies

Ensure you have **pnpm** installed, then run:

```sh
pnpm install
```

### 3️⃣ Start the Development Server

```sh
pnpm dev
```

The application will start running locally.

---

## 📂 Project Structure

```
Full-stack-web-application/
│── app/                 # Main application pages & components
│── public/              # Static assets (images, fonts, etc.)
│── auth.config.ts       # Authentication configurations
│── auth.ts              # Authentication logic
│── middleware.ts        # Middleware for request handling
│── next.config.ts       # Next.js configuration
│── tailwind.config.ts   # Tailwind CSS configuration
│── package.json         # Project dependencies
```

---

## 🚀 Routing

The application leverages **Next.js App Router**, which:

✅ Uses file-based routing inside the `app/` directory.  
✅ Automatically maps components to routes.  
✅ Supports dynamic and nested routes.

**Example:**
```
app/
│── page.tsx        →  /
│── dashboard/
│   ├── page.tsx    →  /dashboard
│   ├── settings/
│   │   ├── page.tsx  →  /dashboard/settings
```

---

## 🔑 Authentication

Authentication is handled via:

- **`auth.config.ts`** – Defines authentication providers & settings.
- **`auth.ts`** – Manages login, logout, and session handling.
- **`middleware.ts`** – Protects private routes.

---

## 🎨 Styling

The project is styled using **Tailwind CSS**, configured in:

```sh
tailwind.config.ts
```

Customization is possible directly in this file.

---




This is a Next.js project bootstrapped with create-next-app.


You can start editing the page by modifying app/page.tsx. The page auto-updates as you edit the file.

This project uses next/font to automatically optimize and load Geist, a new font family for Vercel.

Learn More
To learn more about Next.js, take a look at the following resources:

Next.js Documentation - learn about Next.js features and API.
Learn Next.js - an interactive Next.js tutorial.
You can check out the Next.js GitHub repository - your feedback and contributions are welcome!

Deploy on Vercel
The easiest way to deploy your Next.js app is to use the Vercel Platform from the creators of Next.js.

Check out our Next.js deployment documentation for more details.



