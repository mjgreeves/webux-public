# 🕸️ WebUX — AI Website Analyzer & UX Intelligence

**WebUX** is an AI-powered website analyzer that evaluates UX clarity, messaging, conversion friction, structure, and competitive positioning.  
It helps SaaS teams understand how their site performs, where it’s leaking conversions, and how to improve.

This public repo provides a high-level overview, architecture, screenshots, and product direction.  
The core production code lives inside the private PlayHero monorepo.

---

## 🚀 What WebUX Does

WebUX turns any website URL into a complete AI-driven UX and CRO report:

- **UX clarity scoring**  
- **Conversion friction analysis**  
- **Messaging diagnostics**  
- **Competitor benchmarks**  
- **CRO insights + improvement recommendations**  
- **Spider charts + bar charts for UX categories**  
- **Whitespace discovery** (market + competitor gaps)  
- **AI-generated summaries for quick reporting**

Perfect for founders, marketers, growth teams, and SaaS product owners.

---

## 🧩 Core Modules

### **UX Analyzer**
Breaks down clarity, structure, hierarchy, friction, readability, and messaging.

### **Competitor Scout**
Benchmarks competitors and identifies differentiators + whitespace.

### **CRO Insights Engine**
Surfaces actionable improvements for copy, layout, flows, and conversions.

### **Chart Layer**
Spider, bar, and trend charts built with PlayHero’s shared UI components.

### **AI Summaries**
Synthesizes findings into digestible, executive-ready insights.

---

## 📐 Architecture Snapshot

```txt
webux
├── analyzer
│   ├── messaging
│   ├── structure
│   ├── clarity
│   ├── friction
│   └── sentiment
│
├── competitor-scout
│
├── charts
│   ├── spider
│   ├── bar
│   └── trend
│
├── ai
│   ├── summarizer
│   └── recommendations
│
└── ui
    ├── components
    └── dashboard
````

---

## 🏗 Tech Stack

* **Next.js 15** (App Router + RSC)
* **Vercel** (deploy, edge runtime, AI SDK)
* **Supabase** (auth, DB, RLS, real-time sync)
* **Tailwind + shadcn/ui**
* **TypeScript**
* **PlayHero DSv1 Design System**

---

## 📊 Key Capabilities

* UX clarity scoring
* Conversion friction detection
* Visual hierarchy and structure analysis
* Copy + messaging diagnostics
* Competitor benchmarking
* CRO recommendations
* AI summaries for execs or clients
* Spider and bar chart visualization
* Whitespace and differentiation insights

---

## 🛠 Current Development Areas

* Expanded competitor analysis
* Multi-page UX scoring
* Dashboard v2 (more charts and insights)
* DSv1 integration + UI polish
* Deeper CRO pattern library
* Blueprint export for PlayGTM

---

## 🔗 Live Link

* **WebUX** → [https://www.webux.ai](https://www.webux.ai)

---

## 📬 Contact

**Mike Greeves** — Founder, PlayHero

* LinkedIn → [https://www.linkedin.com/in/michaelgreeves](https://www.linkedin.com/in/michaelgreeves)
* X → [https://x.com/mjgreeves](https://x.com/mjgreeves)
* Web → [https://www.webux.ai](https://www.webux.ai)

---

Always building, always shipping.
