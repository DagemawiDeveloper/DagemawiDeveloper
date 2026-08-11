# Hi, I'm Dagemawi Alemayehu 👋

**PHP / Laravel / WordPress / REST API / SaaS Engineer**

I build and debug production web systems—especially the parts that become difficult once a project moves beyond basic CRUD: plugin conflicts, API integrations, background jobs, multi-tenant data, payments, webhooks, database issues, and existing systems that need careful troubleshooting instead of a rewrite.

## What I work on

```text
WordPress & PHP       Plugin development, troubleshooting, hooks, AJAX, REST APIs
Laravel & SaaS        Backend architecture, APIs, queues, multi-tenancy, dashboards
API Integrations      Webhooks, HMAC signing, retries, idempotency, external services
Commerce & Payments   E-commerce workflows, Stripe Checkout, payment webhooks
Databases             MySQL, schema design, migrations, query/debugging work
Mobile                Flutter apps connected to Laravel APIs
```

## Featured engineering work

| Project | What it demonstrates |
|---|---|
| **[WP Integration Toolkit](https://github.com/DagemawiDeveloper/wordpress-plugin-development-demo)** | WordPress plugin architecture, REST endpoints, AJAX, signed webhooks, encrypted settings, logging and retry workflows |
| **[Boldinone](https://github.com/DagemawiDeveloper/Boldinone)** | Real Laravel e-commerce application: catalog, cart, roles/permissions, administration, Stripe Checkout, idempotent payment handling, orders, inventory, wishlist and reviews |
| **[RelayHub](https://github.com/DagemawiDeveloper/laravel-api-integration-demo)** | Laravel API integrations, queues, HMAC webhooks, idempotency, retries, dead-letter handling and tests |
| **[SaaS Architecture Showcase](https://github.com/DagemawiDeveloper/saas-architecture-showcase)** | Multi-tenant architecture, security, queue design, observability, deployment and failure-mode decisions |
| **[Commission Calculation Engine](https://github.com/DagemawiDeveloper/CommissionApp-Dagemawi)** | Framework-independent PHP, business rules, weekly limits, currency conversion, PSR-4 design and PHPUnit testing |

## The kind of problems I like solving

- “This WordPress/WooCommerce plugin setting refuses to save.”
- “Our API integration works sometimes, but retries create duplicate records.”
- “We need to receive and verify webhooks securely.”
- “This Laravel job/API is failing in production and we need the real cause.”
- “Our checkout/payment callback needs to be reliable and traceable.”
- “Our SaaS needs tenant isolation, queues, roles and a maintainable backend structure.”
- “The existing codebase works, but adding features is becoming risky.”

I prefer to trace the actual failure path, make the smallest safe change, and leave the codebase easier to operate afterward.

## Architecture mindset

```mermaid
flowchart LR
    ISSUE[Problem / Requirement] --> TRACE[Trace actual flow]
    TRACE --> ROOT[Find root cause]
    ROOT --> DESIGN[Choose maintainable fix]
    DESIGN --> BUILD[Implement]
    BUILD --> VERIFY[Test + observe]
    VERIFY --> DOC[Document handoff]
```

My default engineering priorities are:

1. **Correctness before cleverness**
2. **Observable integrations instead of silent failures**
3. **Idempotent/retry-safe background work and webhooks**
4. **Clear tenant and authorization boundaries**
5. **Maintainable extension points instead of core/theme hacks**
6. **Practical solutions that fit the existing system**

## Selected production experience

A large part of my current production work is private. It includes:

- Multi-tenant SaaS platforms with Laravel backends
- Survey/data-collection workflows with web and Flutter clients
- Geofenced field operations and dynamic forms
- API and automation services
- AI-assisted analytics and developer tooling
- WordPress, landing-page and external-data integrations

For private client/product work, I publish sanitized architecture and reference implementations rather than exposing proprietary source code.

## Public repositories

The featured projects above are the best starting point if you're evaluating my current Laravel, WordPress, integration and system-design work. Older repositories that are only historical artifacts are labeled clearly so they are not confused with current engineering samples.

## Work with me

I’m best suited for projects where you need someone who can **understand an existing system, debug it at code level, integrate external services, and ship a maintainable fix**.

- Upwork: [Dagemawi Alemayehu](https://www.upwork.com/freelancers/dagemawialemayehu)
- GitHub: [DagemawiDeveloper](https://github.com/DagemawiDeveloper)

---

**Core stack:** PHP · Laravel · WordPress · MySQL · JavaScript · REST APIs · Stripe · Flutter
