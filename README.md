# Fiverr

A **Pinterest-style clone** built with **Next.js**, **Convex**, and **Clerk**, designed for fast performance, modern UI, and scalable real-time features. This project demonstrates a full-stack application with authentication, database, and interactive feeds.

---

## 🚀 Tech Stack

* **Next.js** – App Router, Server Components, optimized performance
* **Convex** – Real-time backend & database
* **Clerk** – Authentication & user management
* **TypeScript** – Type-safe development
* **Tailwind CSS** – Modern, responsive UI styling

---

## ✨ Features

* 🔐 Secure authentication (Sign in / Sign up) using Clerk
* 📌 Pinterest-style feed layout
* ⚡ Real-time data updates with Convex
* 🖼️ Image-based posts (pins)
* ❤️ Like & interact with posts
* 🧑 User profiles
* 📱 Fully responsive design

---

## 📁 Project Structure

```
fiverr/
├── app/                # Next.js App Router
├── components/         # Reusable UI components
├── convex/             # Convex backend functions & schema
├── lib/                # Utility functions
├── public/             # Static assets
├── styles/             # Global styles
├── middleware.ts       # Clerk middleware
└── package.json
```

---

## 🛠️ Installation & Setup

This project uses **Bun** as the package manager and runtime.

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Adarsh-yadav-ui/Fiverr.git
cd Fiverr
```

### 2️⃣ Install dependencies (using Bun)

```bash
bun install
```

### 3️⃣ Environment Variables

Create a `.env.local` file and add the following:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CONVEX_URL=
```

> Make sure you have a Convex project and Clerk application set up.

---

### 4️⃣ Run the development server

```bash
bun dev
```

Open **[http://localhost:3000](http://localhost:3000)** in your browser.

---

## 📦 Convex Setup

```bash
npx convex dev
```

This starts the Convex backend and syncs your functions.

---

## 🔐 Authentication Flow

* Clerk handles authentication and session management
* Middleware protects private routes
* User data is synced with Convex

---

## 🎯 Future Improvements

* 🔍 Search functionality
* 💬 Comments on posts
* 📂 Boards / collections
* 🚀 Infinite scrolling
* 🌙 Dark mode

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

* Next.js Team
* Convex.dev
* Clerk.dev
* Pinterest (UI inspiration)

---

⭐ If you like this project, consider giving it a star on GitHub!
