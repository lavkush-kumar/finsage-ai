# Welth: Full Stack AI Finance Platform

A modern, AI-powered financial management platform built with Next.js, Supabase, Tailwind CSS, Prisma, Inngest, ArcJet, and Shadcn UI. Track, analyze, and optimize your spending with real-time insights and automation.

---

---

## 🚀 Features

- **AI-Powered Analytics:** Get detailed insights into your spending patterns.
- **Smart Receipt Scanner:** Extract data from receipts using advanced AI.
- **Budget Planning:** Create and manage budgets with intelligent recommendations.
- **Multi-Account Support:** Manage multiple accounts and credit cards in one place.
- **Multi-Currency:** Support for multiple currencies with real-time conversion.
- **Automated Insights:** Receive actionable financial advice and alerts.
- **Recurring Transactions:** Automate and track recurring expenses and income.
- **Email Reports & Alerts:** Get monthly reports and budget alerts via email.

---

## 🛠️ Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS, Shadcn UI
- **Backend:** Next.js API routes, Prisma ORM, Supabase (Postgres)
- **AI/Automation:** Google Generative AI, Inngest (background jobs)
- **Email:** Resend
- **Security & Rate Limiting:** ArcJet

---

## ⚡ Getting Started

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd <repo-folder>
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up your environment variables

Create a `.env` file in the root directory and add the following:

```env
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
RESEND_API_KEY=
ARCJET_KEY=
```

- Get your keys from [Clerk](https://clerk.dev/), [Supabase](https://supabase.com/), [Resend](https://resend.com/), [ArcJet](https://arcjet.com/), and [Google AI](https://ai.google.dev/).

### 4. Set up the database

```bash
npx prisma migrate dev --name init
```

### 5. Run the development server

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to view the app.

---

## 📦 Usage

- Sign up and create your account.
- Add accounts, set budgets, and start tracking transactions.
- Scan receipts, get AI-powered insights, and receive email reports.

---

## 🤝 Contributing

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📄 License

This project is for educational/demo purposes. Add a license if you plan to use it in production.