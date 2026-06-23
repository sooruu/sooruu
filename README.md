<div align="center">

# Hi, I'm Sourabh 👋

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&pause=900&color=3FCF8E&center=true&vCenter=true&width=580&lines=System+architect+%26+designer;I+ship+the+schema+and+the+pixels;Clean%2C+fast%2C+production+web;Vibe+coder%2C+and+proud+of+it." alt="roles" />
</a>

<p>
  <a href="https://sourabhyadav.com">
    <img src="https://img.shields.io/badge/Portfolio-sourabhyadav.com-3FCF8E?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d1117" alt="Portfolio" />
  </a>
  <a href="https://instagram.com/sooourabh_">
    <img src="https://img.shields.io/badge/@sooourabh__-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117" alt="Instagram" />
  </a>
  <img src="https://img.shields.io/badge/Gandhinagar,_Gujarat-0d1117?style=for-the-badge&logo=googlemaps&logoColor=3FCF8E" alt="Location" />
</p>

<i>I design and build production web platforms end to end — architecture, data model, performance, and the last pixel.</i>

</div>

---

### 🏗️ How I build

- **Schema first.** The database and its RLS policies are the source of truth — not the UI, not the API.
- **Cache like the bill depends on it.** ISR, on-demand revalidation, and edge middleware keep pages instant and infra cheap.
- **Performance is a feature.** Core Web Vitals and query latency are measured and budgeted, never guessed.
- **One pair of hands.** I own the architecture *and* the design — fewer handoffs, tighter results.
- **Vibe coder, and proud of it.** I lean on the tools, keep the judgment, and ship.

### 🗺️ A system I run in production

```mermaid
flowchart LR
    U(["Visitors"]) --> CDN["Cloudflare CDN"]
    CDN --> APP["Next.js App Router<br/>RSC · ISR · edge middleware"]
    APP -->|"RLS-guarded"| DB[("Postgres · Supabase")]
    APP --> AUTH["Supabase Auth"]
    APP --> R2[("Cloudflare R2<br/>assets · documents")]
    APP --> SRCH["Search<br/>Postgres FTS · Pagefind"]
    WK["Cloud Run worker<br/>document pipeline"] --> R2
    WK --> DB
```

<sub>A real, running stack: edge-cached pages, row-level-secured data, object storage, and a scale-to-zero worker for heavy jobs.</sub>

### 🧰 Stack I reach for

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <br/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
</p>

### 🛠️ What I'm building

A **forensic-science journal, community, and library** on the web — a layered platform
(content, community, library, authority) built to scale to a million readers. End to end:
schema and RLS, editorial tooling, search, performance, and design.

> 🔭 **Currently:** pushing the platform's edge performance and SEO authority toward its first big traffic milestone.

### 📈 Activity

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=sooruu&theme=dark&hide_border=true&background=0d1117&stroke=3FCF8E&ring=3FCF8E&fire=3FCF8E&currStreakLabel=3FCF8E&sideLabels=9f9f9f&dates=6b6b6b&currStreakNum=ffffff&sideNums=ffffff" alt="contribution streak" />
</div>

---

<div align="center">
  <sub>Most of my work lives in private repos — the graph is quieter than the keyboard.</sub>
  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=sooruu&style=flat-square&color=3FCF8E&label=Profile+views" alt="profile views" />
</div>
