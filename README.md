# 🎟️ TickrPay

> Real-time event payment registration and instant attendee ID generation.

TickrPay is a production-ready event check-in system built to eliminate manual payment tracking during live events. It allows organizers to confirm payments, generate unique attendee IDs instantly, and manage registrations from a single, streamlined dashboard.

---

## 🚀 Why TickrPay?

Most small and mid-scale events still rely on spreadsheets, manual confirmations, or scattered messaging threads.

TickrPay solves that by providing:

* Instant payment logging
* Automated unique ID issuance
* Real-time attendee visibility
* Searchable check-in system
* Clean, event-ready interface

Built with scalability and developer experience in mind.

---

## ✨ Core Features

* ⚡ Real-time payment registration
* 🆔 Deterministic unique attendee ID generation
* 🔎 Search by name or ID
* 🟢 Live event status indicator
* 👥 Single & batch entry support
* 🔐 Secure admin authentication (Supabase Auth)
* ☁️ Cloud database with Supabase

---

## 🖥️ System Overview

**Flow**

1. Admin logs in
2. Registers attendee payment
3. System generates a structured unique ID
4. Attendee is added to live dashboard
5. Records persist in Supabase

Designed for speed under live-event pressure.

---

## 🛠️ Tech Stack

### Frontend

* **Next.js (App Router)**
* **React**
* **TypeScript**
* **Tailwind CSS**
* **shadcn/ui**

### Backend & Infrastructure

* **Supabase**

  * PostgreSQL database
  * Authentication
  * Real-time capabilities

### Deployment

* Vercel-ready

---

## 🏗️ Architecture Highlights (For Recruiters)

* Component-driven UI architecture
* Separation of concerns (UI / logic / config)
* Environment-based configuration
* Scalable database schema design
* Real-time state updates
* Clean, production-level folder structure

---

## 📂 Project Structure

```bash
TickrPay/
│
├── app/              # Next.js routes (App Router)
├── components/       # Reusable UI components
├── lib/              # Business logic & utilities
├── supabase/         # Supabase configuration
├── public/           # Static assets
├── styles/           # Global styles
└── types/            # TypeScript types
```

---

## ⚙️ Getting Started

### Prerequisites

* Node.js (v18+)
* npm / pnpm / yarn
* Supabase project

---

### Installation

```bash
git clone https://github.com/georgegoodluck/TickrPay.git
cd TickrPay
npm install
```

---

### Environment Setup

Create a `.env.local` file:

```env
NEXT_PUBLIC_SUPABASE_URL=your_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_anon_key
```

---

### Run Locally

```bash
npm run dev
```

Visit:

```
http://localhost:3000
```

---

## 📈 Roadmap

* QR code generation per attendee
* CSV export
* Multi-event support
* Role-based access control
* Payment gateway integration
* Analytics dashboard

---

## 🤝 Contributing

Contributions are welcome.

If you’d like to improve the project:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

Areas open for contribution:

* Performance optimization
* UI/UX improvements
* Test coverage
* Feature expansion
* Documentation

---

## 🧪 Future Improvements (Engineering Focus)

* Unit & integration testing
* Rate limiting
* Audit logging
* Event-level permissions
* Database indexing optimization

---

## 📜 License

MIT License. See `LICENSE` for details.

---

## 👤 Author

**George Goodluck**
FullStack Developer
