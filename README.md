# Hi there, I'm Joel Kiggwe 👋
### Backend & Enterprise ERP Specialist • Mukono, Uganda

---

## 🎯 About Me

With an analytical foundation in Mathematics and Physical Sciences (B.Sc. Education), I approach software engineering with algorithmic discipline, invariant constraints, and edge-case rigor. Based in Mukono, Uganda, I build concurrent REST APIs in Node.js and architect enterprise ERP data backends in Python and PostgreSQL.

- 🛠️ **Core Technologies:** Node.js, Express, Python 3, PostgreSQL, MongoDB Atlas, Odoo 19 ERP.
- 💡 **Engineering Invariant:** *"Strict schema contracts at the request boundary, atomic operations in the database, and zero tolerance for race conditions."*

---

## 🚀 Featured Backend Projects & Case Studies

### 1. 🎟️ [Event Discovery & Concurrent Ticketing API](https://github.com/KenjxJJ/event-discovery-ticketing-api)
> **Zero-Overbooking Concurrency Control in Venue Ticketing**

- **Problem:** High-volume concurrent checkouts cause race conditions and oversold venue capacity.
- **System Architecture:** Built with Node.js, Express, MongoDB Atlas, and Mongoose. Enforces atomic conditional mutations (`$inc` coupled with `$expr: { $lte: [{ $add: ["$seatsBooked", qty] }, "$capacity"] }`) to mathematically prevent overbooking at database write time.
- **Key Outcome:** 0 race conditions under simultaneous requests; compound indexed search and pagination.

### 2. 🏢 [Enterprise ERP Workflows & Odoo 19 Systems](https://github.com/KenjxJJ?tab=repositories&q=odoo)
> **Custom Business Logic, Vehicle Tax Estimation & ERP Automation**

- **Problem:** Transactional query bottlenecks in accounting valuations, supply chain flows, and tax computing.
- **System Architecture:** Engineered custom modular addons in Python 3 and PostgreSQL for Odoo 19 with Model Context Protocol (MCP) tooling.
- **Key Outcome:** Eliminated N+1 query overhead using batched ORM operations; automated inspection workflows via 40+ MCP tools.

### 3. 🔐 [Secure Content Publishing & RBAC API](https://github.com/KenjxJJ/week9-blog-api)
> **Stateless Authentication Engine & Role Authorization Guardrails**

- **Problem:** Managing authorization boundaries and protected resources across multi-tier user groups.
- **System Architecture:** Node.js, Express, JWT, bcrypt. Stateless token lifecycle with role authorization middleware.
- **Key Outcome:** Fine-grained role enforcement (Admin/Editor/User), standardized RFC error contracts, and sanitized queries.

---

## 🧰 Technical Skills

```
┌─────────────────┬──────────────────────────────────────────────────────────────┐
│ Category        │ Technologies & Tools                                         │
├─────────────────┼──────────────────────────────────────────────────────────────┤
│ Languages       │ JavaScript (ES6+), TypeScript, Python 3, Bash, SQL           │
│ Backend         │ Node.js, Express.js, RESTful APIs, JWT, Middleware Pipelines │
│ Databases       │ MongoDB / Mongoose, PostgreSQL, ACID & Atomic Mutations      │
│ Enterprise ERP  │ Odoo 17 / 19 Core & Enterprise, Batched ORM, MCP Tooling     │
│ Architecture    │ Concurrency Control, Atomic Locks, Schema Validation (Joi)   │
│ DevOps & Tools  │ Git & Worktrees, Linux CLI, Render, Postman, Swagger/OpenAPI │
└─────────────────┴──────────────────────────────────────────────────────────────┘
```

---

## 📊 GitHub & Engineering Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KenjxJJ&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true" alt="KenjxJJ's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KenjxJJ&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top Languages" />
</div>

<div align="center" style="margin-top: 15px;">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=KenjxJJ&theme=tokyonight&hide_border=true" alt="KenjxJJ's GitHub Streak" />
</div>

<div align="center" style="margin-top: 20px;">
  <a href="https://github.com/KenjxJJ">
    <img src="https://ghchart.rshah.org/22c55e/KenjxJJ" alt="KenjxJJ's GitHub Contribution Heatmap" style="width: 100%; max-width: 850px;" />
  </a>
</div>

---

## 📬 Connect with Me

- **Email:** [joelkiggwe94@gmail.com](mailto:joelkiggwe94@gmail.com)
- **LinkedIn:** [linkedin.com/in/kiggwe-joel](https://www.linkedin.com/in/kiggwe-joel/)
- **X (Twitter):** [x.com/JoelKiggwe](https://x.com/JoelKiggwe)
- **Portfolio:** [kenjxjj.github.io/j-portfolio](https://kenjxjj.github.io/j-portfolio/)
- **Location:** Mukono, Uganda (UTC+3)

---
*⭐ Joel Kiggwe — Backend & Enterprise ERP Specialist.*
