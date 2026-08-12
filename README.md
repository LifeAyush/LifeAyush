<p align="center">
  <img src="https://repository-images.githubusercontent.com/588181932/e36ec678-7984-4cdd-8e4c-a3932772ff8e" alt="banner" width="100%" />
</p>

<h1 align="center">
  Hi, I'm Ayush Patil
  <img src="https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif" width="28" alt="" />
</h1>

<p align="center">
  <strong>Founding Engineer @ Breathe</strong><br/>
  Product + ops automation · IIT Roorkee · Ex-Anakin (YC)
</p>

<p align="center">
  I ship production SaaS and the internal systems that keep a startup running —<br/>
  product modules, data pipelines, AI-assisted workflows, and realtime clients.
</p>

<p align="center">
  <a href="mailto:ayushypatil.work@gmail.com">
    <img src="https://img.shields.io/badge/Email-ayushypatil.work@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/lifeayush/">
    <img src="https://img.shields.io/badge/LinkedIn-lifeayush-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/LifeAyush">
    <img src="https://img.shields.io/badge/GitHub-LifeAyush-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/Based_in-Bengaluru,_India-0A66C2?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
</p>

---

### Right now

- **Breathe** — Founding Engineer on ESG & Zero; building **Supplier Intelligence**; engineering ops automation (CRM, partner workflows, revenue pipeline, reporting)
- **Before** — Anakin (YC S21): AWS data pipelines (200K+ products), account systems at ~10 ms / 3–4K TPS
- **Open to** — collaborating with founders & engineers on product, systems, and AI-in-production problems

---

## Featured projects

<details>
<summary><strong>Falcon</strong> — High-performance L7 reverse proxy & API gateway (Go)</summary>
<br/>

Lightweight reverse proxy for dynamic config, API management, and modern load balancing.

- Layer 7 load balancing: Round Robin, Weighted Round Robin, randomized distribution
- Rate-limiting middleware to protect backends under heavy / abusive traffic
- Dynamic upstream updates via REST — no downtime, no reload
- API Gateway path-based routing + centralized request management
- TOML config; high concurrency via Go goroutines & channels
- Open-source alternative aimed at Nginx Plus–class capabilities

`Go` · `Load Balancing` · `API Gateway` · `System Design`

<!-- <p><a href="https://github.com/LifeAyush/YOUR-FALCON-REPO">Repository →</a></p> -->
</details>

<details>
<summary><strong>MiniPerplexity</strong> — Search-grounded AI chat · 100+ users</summary>
<br/>

Perplexity-style assistant: real-time web search + LLMs → concise answers with sources.

- Cloudflare AI (Llama 70B) + Google & Bing Search APIs for cited, grounded responses
- FastAPI + Pydantic backend; Clerk auth; token-bucket rate limiting
- React + TypeScript + Tailwind UI — dark mode, responsive, dynamic loading states
- Product loop: retrieval → generation → visible citations (not a bare chatbot wrapper)

`LLM` · `FastAPI` · `React` · `TypeScript` · `Cloudflare AI` · `RAG`

<!-- <p><a href="https://github.com/LifeAyush/YOUR-MINIPERPLEXITY-REPO">Repository →</a></p> -->
</details>

<details>
<summary><strong>Pixle Pro</strong> — Browser video editor with a custom JS rendering engine</summary>
<br/>

Canva-like web app for video: compose 2D/3D on canvas, then compile a real video.

- Canvas pipeline for 2D & 3D objects — place, transform, animate on a live preview
- JS scene/timeline engine computing positions, layers, and frame state while editing
- Frame capture → stitch into output video; audio aligned on the same timeline
- Codec / container–oriented export path from individual frames
- Auth + multi-user collaboration over sockets; concurrency-aware updates for performance

`JavaScript` · `Canvas` · `Video Rendering` · `WebSockets` · `Frontend Engineering`

<!-- <p><a href="https://github.com/LifeAyush/YOUR-PIXLE-REPO">Repository →</a></p> -->
</details>

<details>
<summary><strong>TechShila</strong> — Competition platform · scoring engine · live leaderboards</summary>
<br/>

Full-stack platform for IIT Roorkee’s inter-hostel tech meet.

- Problem statements, submissions, evaluation, and real-time ranking
- Scoring engine: category-aware evaluation, validation, instant feedback
- Individual + hostel leaderboards with efficient state updates & DB sync
- React frontend; Node.js + Express APIs; caching for event-day traffic spikes

`System Design` · `Node.js` · `Express` · `React` · `Real-Time`

</details>

<details>
<summary><strong>Thomso</strong> — Fest website & app technical suite · 1M+ hits</summary>
<br/>

Technical suite for IIT Roorkee’s flagship cultural fest — web + app surfaces.

- Led React frontend with a team of 7 (3 senior, 4 junior); reviews & architecture
- Redux state layer restructured for modular features across clients
- Custom hooks for API, auth, and GSAP animations
- Razorpay ticketing with token auth + payment callbacks
- Lazy loading, code splitting, interceptors & retry logic under fest-week load

`React` · `Redux` · `Razorpay` · `GSAP` · `Team Leadership`

</details>

<details>
<summary><strong>KuramaVerse</strong> — Multiplayer poker · sockets · game engine · Web3</summary>
<br/>

Realtime poker platform with wallet login, in-platform currency, and hosted events.

- Web3 wallet auth; deposit into Kurama coin for play
- NFT collection–hosted events with prizes (NFTs, staking boosts, privileges)
- Socket rooms: max 6 players/table; actions fan out to room subscribers
- Scaled to 100+ concurrent rooms with isolated per-table state
- Poker engine: dealing, pots, stakes/raises, live win% from hole cards + board
- Custom JS motion + GSAP timelines for table/game feedback

`WebSockets` · `Game Engine` · `System Design` · `Web3` · `GSAP`

</details>

<details>
<summary><strong>IITR Chemical Engineering Website</strong> — Dept site migration (Chakra CMS)</summary>
<br/>

Departmental pages during IIT Roorkee’s official site migration.

- Chakra CMS pages with responsive, mobile-first layouts
- Academic, research, and faculty content structured with faculty/mentor collaboration
- Navigation, readability, and cross-platform performance polish

`Chakra CMS` · `UI/UX` · `Responsive Design`

</details>

---

## Languages & tools

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="36" alt="Python" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="36" alt="TypeScript" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="36" alt="JavaScript" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" height="36" alt="Go" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="36" alt="React" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="36" alt="Django" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="36" alt="Node.js" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="36" alt="PostgreSQL" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="36" alt="Redis" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="36" alt="Docker" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" height="36" alt="AWS" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="36" alt="Git" />
</p>

---

## Contact

<p align="left">
  <a href="mailto:ayushypatil.work@gmail.com">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&style=for-the-badge" height="32" alt="Gmail" />
  </a>
  <a href="https://www.linkedin.com/in/lifeayush/">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&style=for-the-badge" height="32" alt="LinkedIn" />
  </a>
  <a href="https://github.com/LifeAyush">
    <img src="https://img.shields.io/static/v1?message=GitHub&logo=github&label=&color=181717&logoColor=white&style=for-the-badge" height="32" alt="GitHub" />
  </a>
</p>

<p align="center">
  <sub>Building in public · systems, AI, and product that ships</sub>
</p>
