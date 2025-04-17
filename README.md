# 🏠 QualiBot: WhatsApp Lead Qualification Bot for Real Estate Agents in Dubai

QualiBot is a **simple WhatsApp-based assistant** that helps real estate agencies **qualify and route leads automatically** so they can focus on serious buyers instead of wasting time on cold inquiries.

---

## 🌟 What It Does

✅ Auto-responds to buyer/renter messages on WhatsApp  
✅ Asks questions like budget, location, and buying intent  
✅ Stores lead data in a secure database (Supabase)  
✅ Notifies the agent instantly via email or WhatsApp  
✅ Agent can view leads in a beautiful web dashboard  
✅ User login (Clerk) and payment (Stripe) built-in  
✅ Analytics to track engagement (PostHog)

---

## 📌 Use Case

> 🏢 Real estate agents in Dubai waste time on low-quality leads that contact them via WhatsApp.  
> This app filters, stores, and routes high-quality leads automatically, with zero effort.

---

## ⚙️ Tech Stack

| Purpose                | Tools Used |
|------------------------|------------|
| WhatsApp chatbot       | Python + Twilio WhatsApp API |
| Backend logic/API      | Node.js or Flask |
| Frontend dashboard     | Next.js + Vue (Later phase) |
| Styling/UI             | Tailwind CSS + shadcn/ui |
| Auth                   | Clerk.dev |
| DB & ORM               | Supabase (PostgreSQL) + Prisma |
| Email notifications    | Resend |
| Payments               | Stripe |
| Analytics              | PostHog |
| Deployment             | AWS Amplify |

---

## 🔄 High-Level Workflow (Beginner-Friendly)

1. 🧠 **User sends a WhatsApp message** like "I’m looking for a villa in Dubai Hills"
2. 🤖 **Bot (Twilio + Python) replies with questions** to collect data (budget, location, etc.)
3. 💾 **Lead data is stored in Supabase** using Prisma ORM
4. ✉️ **Agent is notified** instantly via email (Resend)
5. 🌐 **Agent logs into the dashboard** (built in Next.js) to view leads
6. 💳 **Stripe controls access** to features depending on plan
7. 📊 **PostHog logs activity** like leads created and messages sent
8. 🚀 **App is deployed on AWS Amplify** with a public URL

---

## 🗓️ Learning & Building Timeline (3 Months)

| Week | Focus |
|------|-------|
| 1–2  | Python, Twilio, chatbot basics |
| 3    | Supabase + Prisma |
| 4    | Resend emails + simple dashboard |
| 5    | Clerk authentication |
| 6    | Tailwind + UI polishing |
| 7    | Stripe billing |
| 8    | Lead routing + auto replies |
| 9    | Analytics with PostHog |
| 10   | Deployment on AWS Amplify |
| 11–12| Docs, cleanup, GitHub launch |

---

## 🧪 Status

🚧 Currently in development  
🧠 Only Python known for now – learning all other tech as I build  
📚 Documenting everything in public for the dev community

---

## 📖 Dev Blog / Notes (Coming Soon)

- Week 1: Setting up WhatsApp Bot with Python
- Week 2: How I Connected to Supabase
- Week 3: My First Real Dashboard with Next.js
- …

---

## 📎 License

MIT – feel free to use, remix, and learn.

---

