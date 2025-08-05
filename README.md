# Smart Vendor Quote Assistant

> **"Let AI handle your quotes, follow-ups, and deposits — while you handle the real work."**

An AI-powered web app that automates quote generation and follow-ups for home service businesses. Built for HVAC, plumbing, electrical, and contractor professionals who waste hours on manual paperwork.

## 🎯 The Problem

Home service businesses **waste hours writing quotes, following up**, and handling **manual paperwork** (texts, emails, PDFs). They're not tech-savvy, and existing software like Jobber or Housecall Pro is **too complex or expensive**.

## 🛠️ The Solution

A **no-fuss AI quoting assistant** that:

- ✅ Parses incoming client requests (text/email/voice)
- ✅ Generates **smart quotes** using templates + AI
- ✅ Emails or texts quotes to clients automatically
- ✅ Follows up automatically if no reply in 48 hours
- ✅ Includes "accept" button + collects deposits
- ✅ Tracks all quotes in a simple dashboard

## 🏗️ Tech Stack (Lean & Profitable)

| Component        | Technology                                           |
| ---------------- | ---------------------------------------------------- |
| **Frontend**     | Next.js + React + Tailwind CSS                      |
| **Backend**      | Supabase (auth, database, storage, instant API)     |
| **AI**           | Lovable AI workflows (text → summary → quote)       |
| **Email/SMS**    | Resend + Twilio                                      |
| **Docs**         | PDF/HTML quote generation                            |
| **Auth**         | Supabase Auth                                        |
| **Payments**     | Stripe (for deposits & subscriptions)               |

## 🎯 Target Market

**Small home service providers** (1–10 employees):
- 🔧 HVAC technicians
- 🚰 Plumbers  
- ⚡ Electricians
- 🏊 Pool maintenance
- 🚗 Mobile car detailing
- 🏠 General contractors

**Pain Point**: Underserved by software, yet deal with constant quotes & invoices
**Willingness to Pay**: $20–50/month if it saves 5+ hours/week

## 💰 Business Model

- **Free Trial**: 14 days
- **Monthly Subscription**: $29–49/month
- **Add-ons**: 
  - Per text/email: $0.10
  - Payment processing: 2.5% fee

**Target**: $10K MRR within 6 months

## 🚀 MVP Features (3-Week Build)

| Priority | Feature                 | Technology                                |
| -------- | ----------------------- | ----------------------------------------- |
| **P0**   | Landing Page            | Next.js + Tailwind                       |
| **P0**   | Signup/Login            | Supabase Auth                             |
| **P1**   | Client Intake Form      | Simple web form                           |
| **P1**   | AI Quote Generator      | Lovable workflow (text → summary → quote) |
| **P1**   | Send via Email/Text     | Resend + Twilio                           |
| **P2**   | Quote Tracker Dashboard | Supabase DB + simple UI                   |
| **P2**   | Basic Quote Templates   | HTML + dynamic variables                  |

## 📋 Development Roadmap

### Phase 1: Foundation (Week 1)
- [ ] **Landing Page** - Convert visitors to signups
- [ ] **Authentication** - Supabase Auth integration
- [ ] **Database Setup** - User profiles, quotes schema

### Phase 2: Core Features (Week 2-3)
- [ ] Client intake form
- [ ] AI quote generation
- [ ] Email/SMS integration
- [ ] Basic dashboard

### Phase 3: Growth Features (Week 4+)
- [ ] Quote templates customization
- [ ] Automated follow-ups
- [ ] Payment collection
- [ ] Analytics dashboard

## 🔧 Installation & Setup

### Prerequisites
- Node.js 18+
- npm or yarn
- Supabase account
- Lovable account

### Quick Start

1. **Clone the repository:**
```bash
git clone <repository-url>
cd smart-vendor-quote-assistant
```

2. **Install dependencies:**
```bash
npm install
```

3. **Environment setup:**
```bash
cp .env.example .env.local
```

4. **Configure environment variables:**
```env
# Supabase
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key

# Lovable AI
LOVABLE_API_KEY=your_lovable_key

# Communications
RESEND_API_KEY=your_resend_key
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token

# Payments
STRIPE_PUBLISHABLE_KEY=your_stripe_key
STRIPE_SECRET_KEY=your_stripe_secret
```

5. **Start development server:**
```bash
npm run dev
```

## 📊 Growth Strategy

1. **Community Outreach**
   - Facebook Groups for tradespeople
   - Reddit communities (r/HVAC, r/Plumbing, etc.)
   - Local contractor associations

2. **Direct Outreach**
   - Cold email/DM small local businesses
   - Offer free setup for first 50 customers
   - Partner with equipment suppliers

3. **Content Marketing**
   - "How to write better quotes" guides
   - Time-saving tips for contractors
   - Case studies and testimonials

## 📈 Success Metrics

- **Customer Acquisition**: 50 beta users in Month 1
- **Revenue**: $1K MRR by Month 2, $10K MRR by Month 6
- **Retention**: >80% monthly retention
- **Time Savings**: Average 5+ hours saved per user per week

## 🏆 Competitive Advantages

- ✅ **High pain point** = low churn
- ✅ **Under-digitized industry** = low competition  
- ✅ **B2B market** = better payment behavior
- ✅ **Recurring revenue** model
- ✅ **Low infrastructure costs** (Supabase + Lovable = $0–$50/month)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support & Contact

- **Email**: support@smartquoteassistant.com
- **Discord**: [Join our community](https://discord.gg/smartquote)
- **Documentation**: [docs.smartquoteassistant.com](https://docs.smartquoteassistant.com)

---

**Built with ❤️ for hardworking contractors and home service professionals.**
