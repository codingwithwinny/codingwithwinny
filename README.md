<h1 align="center">Hi, I'm Winston 👋</h1>
<h3 align="center">Building AI products in public</h3>

---

### About me

I build AI-powered products and document the decisions behind them as I go.

Currently focused on shipping production AI features, practicing PM craft (public ADRs, transparent CHANGELOGs, scope discipline), and bridging the gap between engineering, product, and enterprise client work.

The question I keep returning to: **how do you build AI products that actually solve user problems instead of just demoing well?**

---

### Featured project

#### Ancy Expense Tracker — `ancy.co.in`

A personal expense PWA with three production AI features. Built with React, Firebase, and the Anthropic Claude API.

**Shipped AI features:**
- **Natural-language quick-add** — type *"500 on groceries, 200 on coffee"* → parsed into structured expense records via Claude API
- **Bank statement import** — PDF/CSV upload → AI-categorized transactions via Cloud Functions
- **AI Insights engine** — anomaly detection + spending personality archetypes from your data

**Practicing PM craft in public:**
- [Decision records (ADRs)](https://github.com/codingwithwinny/expense-tracker/tree/v2-development/docs/decisions) — every meaningful decision documented with options considered, trade-offs accepted, and revisit conditions
- [Public CHANGELOG](https://github.com/codingwithwinny/expense-tracker/blob/v2-development/CHANGELOG.md) — what shipped, the user problem it solves, what was deliberately scoped out
- Scope discipline through "not shipping yet" lists

**Stack:** React, Vite, Tailwind CSS, Firebase (Firestore, Auth, Cloud Functions, Hosting), Anthropic Claude API, Framer Motion, Recharts.

**Repo →** [`expense-tracker`](https://github.com/codingwithwinny/expense-tracker)

---

### How I work

- **Ship-first, polish-second.** I'd rather ship a v0.1 that works than a v1.0 that doesn't exist.
- **Decisions over code.** Code can be rewritten in a day; rebuilding the reasoning behind a decision takes weeks.
- **Constraints sharpen products.** A weekly chart view sounds nice — until you realize people budget monthly. Most "useful features" aren't.
- **AI bugs are usually plumbing bugs.** Most AI features fail at JSON parsing, not at the model.

---

### Currently learning

- Production patterns for shipping AI products (cost, latency, reliability, eval)
- Product strategy & roadmap thinking
- Prompt engineering for structured output

---

### Connect

- **LinkedIn** → [linkedin.com/in/ancywinstondsilva](https://linkedin.com/in/ancywinstondsilva)
- **GitHub** → [github.com/codingwithwinny](https://github.com/codingwithwinny)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=codingwithwinny&show_icons=true&hide_title=true&theme=dark" alt="Winston's GitHub stats" />
</p>
