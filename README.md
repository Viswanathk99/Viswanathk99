# Viswanath K

I'm a software engineer who likes hard problems.

I care about building systems that actually work under pressure  not just writing code that compiles, but code that scales, recovers gracefully, and doesn't wake anyone up at 3am. I get the most energy from debugging something nobody else can figure out, or rethinking an architecture that's about to hit its ceiling.

Right now I'm building backend infrastructure for **SITHA**, a gig-economy marketplace serving thousands of users on Android and iOS. I've taken systems from "it works on my machine" to production on AWS, migrated ORMs to raw SQL when the abstraction became the bottleneck, and wired together payments, logistics, and messaging into workflows that handle real money and real deadlines.

---

### How I think about engineering

**Start from the problem, not the tool.** I pick the technology that fits the constraint  not the one I used last time.

**Measure before you optimize.** I migrated TypeORM to raw SQL at SITHA not because ORMs are bad, but because query profiling showed they were the bottleneck. The fix was specific, not ideological.

**Own the whole stack.** I don't throw code over the wall. I deploy it, monitor it, and fix it when it breaks. My work spans from database schema design to AWS infrastructure to the alerts that tell me something's wrong.

---

### What I work with

**Languages** — TypeScript, JavaScript, Java, Python  
**Backend** — NestJS, Express.js, Spring Boot, FastAPI  
**Databases** — MySQL, PostgreSQL, MariaDB (Aurora), MongoDB, Redis  
**Cloud** — AWS (ECS, Fargate, CloudWatch), Docker, HashiCorp Vault  
**Integrations** — Razorpay, Shiprocket, WhatsApp Business API

---

### Problems I've solved

**Performance bottleneck at scale** — Core data access at SITHA was choking under load. Profiled the ORM-generated queries, identified the worst offenders, and migrated critical paths to optimized raw SQL. Response times dropped significantly.

**End-to-end payment infrastructure** — Integrated Razorpay gateway and IDFC Bank payout workflows from scratch. Sellers transact, settlements happen automatically, edge cases (failed payouts, partial refunds) are handled — not ignored.

**Logistics with real SLAs** — Built Shiprocket integration with deadline-aware booking workflows. Orders don't just ship — they ship on time, with tracking, and the system knows when something's late before the customer does.

**Detecting fake media** — Built a CNN + ResNet pipeline in TensorFlow that classifies manipulated audio, video, and images in real time. The interesting part wasn't the model — it was making inference fast enough to be useful.

**ML-powered recommendations** — Built a scikit-learn pipeline analyzing purchase behavior, served predictions through FastAPI, and built a React dashboard to close the feedback loop on recommendation quality.

---

### What I'm working toward

I want to be the engineer you call when the system is on fire, and also the one who architects it so it doesn't catch fire in the first place. I'm deepening my understanding of distributed systems, system design, and performance engineering  not to collect certifications, but to solve bigger problems.

---

### Let's talk

If you're building something technically interesting, I'd like to hear about it.

[LinkedIn](https://linkedin.com/in/viswanath-k-413031202) · [Email](mailto:viswanathk333@gmail.com)
