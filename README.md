<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Sankalp Pandey — Full Stack Product Engineer. App, storefront, API and infrastructure." />

</div>

## About

I'm a full-stack product engineer based in New Delhi. I design, build and
operate production software from the UI down to the droplet.

At **[BillingFast](https://www.billingfast.com/)**, I work across the full
delivery chain: the Flutter app on Android, iOS and Web, merchant storefronts,
WhatsApp automation, backend services and infrastructure. I am comfortable
taking a feature from schema migration to production deployment and incident
response. I also manage Android publishing through Google Play Console and have
published **10 apps for my clients**.

[BillingFast product](https://www.billingfast.com/) ·
[Android app](https://play.google.com/store/apps/details?id=com.apnidukan.my_app)
· [iOS app](https://apps.apple.com/in/app/billing-fast-kirana-fast/id1567324958)
· [Web app](https://www.billingfast.com/app/) ·
[LinkedIn](https://www.linkedin.com/in/sankalp-pandey-108562217) ·
[Email](mailto:sankalppandey696@gmail.com)

---

## Selected work

### BillingFast — retail billing, inventory and commerce

A production platform that helps retailers manage billing, stock, reporting,
online sales and customer communication. The Android app has reached
**[50K+ downloads](https://play.google.com/store/apps/details?id=com.apnidukan.my_app)**,
with the product also shipping on iOS and the Web.

- **Multi-platform client:** Flutter across Android, iOS and Web, with
  Drift/SQLite local persistence, background cloud sync and conflict handling
- **Fast catalog workflows:** low-latency product search through Typesense for
  inventory and billing screens
- **Merchant storefronts:** catalog, cart, checkout, coupons and order tracking,
  including custom-domain onboarding and automated TLS
- **WhatsApp automation:** campaigns, order updates, cart recovery and
  rule-driven workflows on the
  [WhatsApp Business API](https://www.billingfast.com/blog/whatsapp-order-automation.html)
- **Production operations:** Deno/Hono services, Redis-backed queues, Postgres,
  Nginx and containerized deployments

### [Floofy](https://github.com/SankalpPyFever333/Floofy) — community platform for pet lovers

I built Floofy as a full-stack MERN application for people to share pet content,
discover products and services, manage profiles and interact through community
features. It includes authentication, administrative workflows and scheduled
database backups.

[Try the live application](https://floofy-eta.vercel.app/) ·
[Explore the source](https://github.com/SankalpPyFever333/Floofy)

`React` · `Redux` · `Node.js` · `Express` · `MongoDB` · `Firebase`

---

## The system I run

Flutter clients and merchant storefronts enter through Nginx and managed TLS.
Deno services coordinate Postgres, Redis queues, Typesense and object storage,
while background workers handle scheduled and asynchronous jobs. Local app data
syncs back to the cloud with explicit conflict handling.

```mermaid
flowchart LR
    subgraph clients["Clients"]
        A["Flutter App<br/>Android · iOS · Web PWA"]
        B["Online Store<br/>Customer PWA"]
        C["WhatsApp<br/>Business API"]
    end

    subgraph edge["Edge"]
        D["Nginx<br/>TLS · Reverse Proxy"]
        E["Custom Domains<br/>DNS · Auto Certs"]
    end

    subgraph services["Application Services · Docker"]
        F["Deno API<br/>Hono"]
        G["WhatsApp Agent<br/>Webhooks · Automations"]
        H["Workers<br/>Queues · Cron · Shipping"]
    end

    subgraph data["Data"]
        I[("Postgres<br/>Supabase")]
        J[("Redis<br/>Cache · Queues")]
        K[("Typesense<br/>Search")]
        L["Object Storage<br/>Media · Invoices"]
    end

    A --> D
    B --> E
    C --> G
    E --> D
    D --> F
    F --> G
    F --> H
    G --> J
    H --> J
    F --> I
    F --> J
    F --> K
    F --> L
    I -. "sync" .-> A

    classDef c fill:#0080ee,stroke:#172a43,stroke-width:1px,color:#ffffff
    classDef e fill:#005773,stroke:#172a43,stroke-width:1px,color:#ffffff
    classDef s fill:#172a43,stroke:#0080ee,stroke-width:1px,color:#ffffff
    classDef d fill:#dba54d,stroke:#887456,stroke-width:1px,color:#172a43
    class A,B,C c
    class D,E e
    class F,G,H s
    class I,J,K,L d
```

---

## Core stack

- **Client:** Flutter, Dart, Drift, GetX, React, Next.js, TypeScript, Redux,
  Tailwind CSS, PWA
- **Backend and APIs:** Deno, Hono, Node.js, Express, GraphQL, webhooks,
  WhatsApp Cloud API
- **Data and search:** Postgres, Supabase, Redis, Typesense, SQLite, MongoDB,
  Firebase, object storage
- **Platform and delivery:** Docker, Nginx, Cloudflare, DigitalOcean, Let's
  Encrypt, Linux, GitHub Actions, Google Play Console, Bash

---

## Background

- **Master of Computer Applications**, Jamia Millia Islamia
- **Bachelor of Computer Applications**, National PG College

---

## Let's build something that ships

I enjoy hard product and infrastructure problems—especially the ones that need
ownership across client experience, APIs, data and deployment.

[Email me](mailto:sankalppandey696@gmail.com) ·
[Connect on LinkedIn](https://www.linkedin.com/in/sankalp-pandey-108562217) ·
[View my GitHub](https://github.com/SankalpPyFever333)

<div align="center">

<img src="./assets/footer.svg" width="100%" alt="From app development to Play Store release and production operations — end-to-end product delivery by Sankalp Pandey." />

</div>
