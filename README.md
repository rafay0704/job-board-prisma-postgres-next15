# Job Board App with Next.js & Prisma

<div align="center">

   <h3 align="center">Job Board App built with Next.js, Prisma, PostgreSQL, and TailwindCSS</h3>
  
  <br />
</div>

## 📋 Table of Contents

1. [Introduction](#-introduction)
2. [Tech Stack](#-tech-stack)
3. [Features](#-features)
4. [Quick Start](#-quick-start)
5. [Screenshots](#-screenshots)
6. [Deployment](#-deployment)

---

## 🚀 Introduction

This is a **modern Job Board App** built with **Next.js**, **Prisma**, **PostgreSQL**, and **TailwindCSS**.  
It supports **CRUD operations**, **dynamic search filters**, **user dashboards**, and **job applications**.  
This project is fully customizable and ready to be deployed.

---

## ⚙️ Tech Stack

* **Next.js 15** – React fullstack framework with server components
* **Prisma** – ORM for database management
* **PostgreSQL** – Relational database
* **TailwindCSS** – Utility-first CSS framework
* **React Hooks** – For client-side state management
* **TypeScript** – Optional, for type safety
* **Authentication** – NextAuth or custom session handling

---

## ⚡️ Features

* 📝 **Post Job Offers** – Authenticated users can post new job listings with title, description, type, and location.
* 🔍 **Advanced Search** – Filter jobs by keyword, type (Full-time, Part-time, Contract), and location.
* 👤 **User Dashboard** – Users can view their posted jobs and applications.
* ✅ **Job Applications** – Users can apply to jobs; dashboard shows application statuses.
* 🔄 **Dynamic Routes & Pages** – Each job has a detail page with full info and "Apply" functionality.
* 🔐 **Authentication & Authorization** – Only signed-in users can post or apply for jobs.

---

## 👌 Quick Start

### Prerequisites

* [Node.js](https://nodejs.org/)
* [PostgreSQL Database](https://www.postgresql.org/)
* [Prisma CLI](https://www.prisma.io/docs/getting-started)
* [Next.js](https://nextjs.org/)

### Setup and Run

```bash
# Clone the repo
git clone https://github.com/yourusername/job-board-next-prisma.git
cd job-board-next-prisma

# Install dependencies
npm install

# Configure your database in .env
npx prisma generate
npx prisma migrate dev

# Start development server
npm run dev
