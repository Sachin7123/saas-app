<div align="center">
  <img src="https://img.shields.io/badge/-Next.JS-black?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/-Vapi-green?style=for-the-badge&logo=vapi&logoColor=white" />
  <img src="https://img.shields.io/badge/-Tailwind-00BCFF?style=for-the-badge&logo=tailwind-css&logoColor=white" />
</div>

<h3 align="center">SaaS LMS App – Built with Next.js, Supabase, Vapi & More</h3>

---

## 📋 Table of Contents

1. [🚀 Introduction](#introduction)
2. [⚙️ Tech Stack](#tech-stack)
3. [🔋 Features](#features)
4. [🚀 Quick Start](#quick-start)
5. [🔗 Assets & Links](#assets-links)
6. [📄 License](#license)

---

## 🤖 Introduction

A modern **Learning Management System (LMS)** SaaS app built with **Next.js**, **Supabase**, **Stripe**, **Clerk**, and **Vapi**. This project enables users to:

- Authenticate and manage subscriptions
- Interact with AI voice agents
- Bookmark and revisit sessions
- Seamlessly learn in real time

You’ll get hands-on experience with full-stack SaaS development using cutting-edge tools.

---

## ⚙️ Tech Stack

| Technology  | Description |
|-------------|-------------|
| **Next.js** | React-based framework for server-side rendering and static site generation |
| **Tailwind CSS** | Utility-first CSS framework for fast UI development |
| **Clerk** | Authentication and user management platform |
| **Supabase** | Real-time database and authentication (PostgreSQL-based) |
| **Vapi** | AI voice assistant platform for real-time, low-latency voice interaction |
| **Stripe** | Payment and subscription management |
| **shadcn/ui** | Pre-built UI components based on Radix UI & Tailwind CSS |
| **Zod** | TypeScript-first schema validation |
| **Sentry** | Real-time error tracking and performance monitoring |

---

## 🔋 Features

- 🎙 **AI Voice Agents** — Talk to AI tutors trained on your selected topics.
- 🔐 **Authentication** — Secure sign-up/sign-in with social logins via Clerk.
- 💳 **Subscriptions** — Manage billing, upgrades, and access levels.
- 📌 **Bookmarks & History** — Save tutors and revisit past sessions easily.
- 🧠 **Custom AI Tutors** — Create your own AI tutor by selecting topics and tone.
- 🔍 **Search Tutors** — Quickly find tutors via filters and search bar.
- 📱 **Responsive UI** — Works perfectly across all screen sizes.
- ⚡ **Real-time Data** — Integrated with Supabase for live updates.
- 🧩 **Modular Codebase** — Reusable components and clean architecture.
- 🎨 **Modern UI** — Built with Tailwind CSS and shadcn/ui.

---

## 🤸 Quick Start

### ✅ Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

### 📦 Installation

Install the project dependencies using npm:

```bash
npm install
```


## ⚙️ Environment Variables
### Create a .env file in the root directory and add:

# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=

# 🧪 Run the Development Server
```bash
npm run dev
```

