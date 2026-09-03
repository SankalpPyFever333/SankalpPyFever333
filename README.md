<div align="center">

<img src="https://raw.githubusercontent.com/SankalpPyFever333/SankalpPyFever333/main/assets/hero.svg" width="100%" alt="Sankalp Pandey — Full Stack Product Engineer" />

<img src="https://readme-typing-svg.demolab.com?font=Segoe+UI&weight=600&size=21&pause=1100&color=3FD3FF&center=true&vCenter=true&width=780&height=42&lines=Flutter+apps+on+Android%2C+iOS+and+Web;Storefronts+with+custom+domains+and+auto+TLS;WhatsApp+agents+on+queues+and+webhooks;Deno+APIs+behind+Nginx+on+DigitalOcean" alt="What I do" />

<a href="https://www.linkedin.com/in/sankalp-pandey-108562217"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<img src="https://img.shields.io/github/followers/SankalpPyFever333?style=for-the-badge&color=172a43&labelColor=005773&logo=github&logoColor=white" alt="Followers" />
<img src="https://komarev.com/ghpvc/?username=SankalpPyFever333&style=for-the-badge&color=0080ee&label=PROFILE+VIEWS" alt="Profile views" />
<img src="https://img.shields.io/badge/New%20Delhi,%20India-172a43?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />

</div>

---

## About

I design, build and operate production software from the UI down to the droplet.

Right now I own **BillingFast** end to end: the Flutter app on Android, iOS and
Web, the online storefront, the WhatsApp automation agent, and the entire
backend and infrastructure behind them. That means Drift/SQLite offline sync and
conflict resolution on one side, and Nginx, TLS, Redis queues and DigitalOcean
deploys on the other.

- Shipping retail billing, inventory, e-commerce and messaging automation for
  real merchants
- Comfortable owning a feature from schema migration to app store release to
  production incident
- Previously built **Floofy**, a platform for pet lovers
- **MCA**, Jamia Millia Islamia · **BCA**, National PG College

---

## What I'm building

<table>
<tr>
<td width="33%" valign="top">

### BillingFast

Retail billing, inventory and e-commerce platform.

Flutter across Android, iOS and Web PWA. Offline-first with Drift, cloud sync
via Supabase, sub-100ms product search with Typesense.

`Flutter` `Drift` `Supabase` `Typesense`

</td>
<td width="33%" valign="top">

### WhatsApp Agent

Conversational commerce and automation layer.

Broadcast campaigns, order updates, cart recovery and rule-driven automations on
the WhatsApp Business API.

`Deno` `Hono` `Redis` `Webhooks`

</td>
<td width="33%" valign="top">

### Online Store

Customer-facing storefront per merchant.

Catalog, cart, checkout, coupons and order tracking, with custom domain
onboarding and automatic TLS.

`PWA` `Postgres` `Nginx` `Cloudflare`

</td>
</tr>
</table>

---

## The system I run

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

    subgraph services["Services · Docker on DigitalOcean"]
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

## Stack

<div align="center">

<sub><b>C L I E N T</b></sub><br/>
<img src="https://skillicons.dev/icons?i=flutter,dart,firebase,androidstudio,react,nextjs,ts,js,redux,tailwind&theme=dark&perline=10" alt="Client stack" />

<sub><b>S E R V I C E</b></sub><br/>
<img src="https://skillicons.dev/icons?i=deno,nodejs,express,supabase,graphql,postman&theme=dark&perline=10" alt="Service stack" />

<sub><b>D A T A</b></sub><br/>
<img src="https://skillicons.dev/icons?i=postgres,redis,mongodb,sqlite&theme=dark&perline=10" alt="Data stack" />

<sub><b>P L A T F O R M</b></sub><br/>
<img src="https://skillicons.dev/icons?i=docker,nginx,cloudflare,linux,githubactions,git,bash,vscode&theme=dark&perline=10" alt="Platform stack" />

<br/>

**No icon exists, still ship it daily:** `Hono` · `Drift` · `GetX` · `Typesense`
· `DigitalOcean` · `WhatsApp Cloud API` · `Let's Encrypt`

</div>

---

## GitHub

<div align="center">

<img height="170" src="https://github-stats-extended.vercel.app/api?username=SankalpPyFever333&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github&title_color=0080ee&icon_color=dba54d&text_color=8b949e&bg_color=00000000" alt="GitHub stats" />
<img height="170" src="https://streak-stats.demolab.com?user=SankalpPyFever333&hide_border=true&background=00000000&ring=0080ee&fire=dba54d&currStreakLabel=0080ee&sideNums=8b949e&currStreakNum=8b949e&dates=6e7681&sideLabels=8b949e" alt="Streak" />

<img height="150" src="https://github-stats-extended.vercel.app/api/top-langs/?username=SankalpPyFever333&layout=compact&hide_border=true&langs_count=8&title_color=0080ee&text_color=8b949e&bg_color=00000000" alt="Top languages" />

</div>

---

<div align="center">

<a href="https://www.linkedin.com/in/sankalp-pandey-108562217"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:sankalppandey696@gmail.com"><img src="https://img.shields.io/badge/Email-172a43?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/SankalpPyFever333"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

<img src="https://raw.githubusercontent.com/SankalpPyFever333/SankalpPyFever333/main/assets/footer.svg" width="100%" alt="" />

</div>
