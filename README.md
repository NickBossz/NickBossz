# Nicolas Mateus

**Full-stack developer from Brazil.**<br />
I build computer-vision tooling, AI agent infrastructure and product web apps.

## About me

- 🔬 Currently building **MangaLens** — you give it a manga/anime character and describe in plain language what you want cut out, and it hands back each part as its own layer. Runs entirely on your machine, no cloud.
- 🛰️ Before that, **[AgentScope](https://github.com/NickB0ss/agentscope)** — an observability platform for AI agents, tracking prompts, responses, execution flow, tool calls, token usage, cost and errors.
- 📈 The rest tends to land in **finance** (portfolio trackers for the Brazilian stock market) or **product web apps**.
- 🧰 Day to day that means **Python** for anything with a model in it, **TypeScript + React** on the front, **Node/Bun** behind it, **PostgreSQL / Supabase / MongoDB** underneath.
- 🦈 Built a *Sharks from Space* entry for the 2025 Space Apps Challenge.
- 📫 Reach me at **nicolasmateusdecastrosilva@gmail.com**

---

## Things I've built

### MangaLens *(main project — private for now)*
Cutting a character into animatable layers is hours of manual rotoscoping in Photoshop. MangaLens does it from a sentence: *"separate the hair into strands and the accessory on the neck"* comes back as one mask per part, ready to import into After Effects, Premiere or DaVinci.

Under the hood it's a pipeline of open-vocabulary detection (Grounding DINO) into pixel-level segmentation (SAM), with alpha matting to clean up the edges and Canny edge detection to split a single mask into instances — individual hair strands, for example. Everything runs locally, including hardware profiles so it works on a 4GB GPU and not just a 12GB one.

`Python` `FastAPI` `PyTorch` `ONNX Runtime` `Transformers` `OpenCV`

### [AgentScope](https://github.com/NickB0ss/agentscope)
Observability for AI agents. Bun monorepo with web app, API, worker, shared contracts, database package, telemetry helpers and a Node.js SDK, running on Postgres behind Docker Compose.

`Bun` `TypeScript` `PostgreSQL` `Docker`

### [InvestHub](https://github.com/NickB0ss/investhub) · [live](https://investhub-navigator.vercel.app)
Portfolio tracker for Brazilian stocks. Average price, profit/loss and ROI computed per position, real-time market data, operation history and JWT auth on a serverless API.

`React` `TypeScript` `Vite` `TanStack Query` `Express` `MongoDB`

### [ecommerce-hair](https://github.com/NickB0ss/ecommerce-hair) · [live](https://ecommerce-hair-frontend.vercel.app)
Decoupled e-commerce monorepo: an Express + Supabase REST API, a React storefront, and a separate React 19 admin panel for products, categories and users.

`React` `TypeScript` `Express` `Supabase` `Tailwind`

### [nutri4kids](https://github.com/NickB0ss/nutri4kids-one-landing-page) · [live](https://nutri4kids-one-landing-page.vercel.app)
Single-page landing built for a nutrition brand.

`TypeScript` `React` `Tailwind`

A few other things live in private repos: an AI sales assistant and a video summarizer, both Python.

---

## Tech I reach for

<div>
  <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="PyTorch" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg">
  <img align="center" alt="FastAPI" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg">
  <img align="center" alt="OpenCV" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg">
  <img align="center" alt="TypeScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg">
  <img align="center" alt="JavaScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg">
  <img align="center" alt="React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="Node.js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
  <img align="center" alt="Bun" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bun/bun-original.svg">
  <img align="center" alt="PostgreSQL" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg">
  <img align="center" alt="Supabase" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/supabase/supabase-original.svg">
  <img align="center" alt="MongoDB" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg">
  <img align="center" alt="Tailwind CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg">
  <img align="center" alt="Docker" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg">
  <img align="center" alt="Git" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg">
</div>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs?username=NickB0ss&layout=compact&langs_count=8&hide_title=true&hide_border=true&card_width=340&bg_color=00000000&text_color=e6edf3" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=NickB0ss&layout=compact&langs_count=8&hide_title=true&hide_border=true&card_width=340&bg_color=00000000&text_color=1f2328" alt="Most used languages" />
</picture>

---

*"Get excited."* — **Senku Ishigami**

<sub>Senku doesn't wait for the world to be ready — he builds the thing from scratch until it exists. Same idea here.</sub>
