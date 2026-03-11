**Staff Engineer & Software Architect** at [Nexly Group](https://nexlygroup.com) — building systems that hold up in production.

I design and implement backend-heavy platforms across the full delivery lifecycle: architecture decisions, async pipelines, API contracts, data modeling, observability and deployment. Most of my work lives at the intersection of correctness, operability and long-term maintainability.

Currently leading technical architecture for a portfolio of clients in fintech, edtech and e-commerce — ranging from greenfield platforms to legacy system migrations under live traffic.

---

### Selected work

**FAMATH Enrollment Ecosystem**
End-to-end academic enrollment platform serving thousands of candidates per cycle. Covers candidate portal, admin backoffice, WhatsApp LLM agent, payment processing and synchronization with a government-operated legacy enrollment system. Designed the async ingestion layer to decouple high-volume intake from downstream processing, eliminating timeout failures and ensuring idempotent delivery across enrollment stages.

**Fintech CRM with AI Lead Qualification**
CRM platform built for a financial services client handling inbound WhatsApp leads at scale. Implemented LLM-driven qualification with structured output constraints, stage-based pipeline routing, round-robin assignment with configurable rules, and real-time Kanban updates over WebSockets. Designed for auditability — every qualification decision is logged with the model output and the rule that triggered the transition.

**Multi-tenant DRE Engine**
Financial reporting platform with versioned rule definitions, tenant isolation and historical integrity guarantees. Built to allow clients to evolve their accounting rules without invalidating prior period reports. Focused on correctness over feature velocity — the system is boring by design.

**Data Warehouse Migration — Silva Nutrition**
Led the full migration of a production data warehouse from a legacy Supabase environment to a clean, governed schema. Resolved 26k orphan records, eliminated 60% duplicate rates, enforced referential integrity and RLS across 18 tables, and designed the incremental sync architecture using AWS Lambda for ongoing pipeline operations.

Architecture decisions, patterns and case studies: [github.com/Bruno-Alvez/real-use-cases](https://github.com/Bruno-Alvez/real-use-cases)

---

### How I work

I favor systems that other engineers can debug at 2am without needing me on the call. That means structured logging, clear failure modes, idempotent operations and APIs with explicit contracts. I treat observability as a first-class concern, not an afterthought. When I introduce complexity, I document the trade-off.

On architecture: I default to boring technology and reserve novelty for problems that genuinely require it. Most systems are over-engineered before they're under-understood.

---

### Contact

[LinkedIn](https://linkedin.com/in/brunoalves-tech) · [bruno.bsantos75@gmail.com](mailto:bruno.bsantos75@gmail.com)
