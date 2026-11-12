<!-- README.md -->

<p align="center">
  <img src="https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif" alt="Hi" />
  <h1>Hi, I’m Fahim Arif</h1>
</p>

<!-- TOC -->
- [About Me](#about-me)
- [Tech Stack](#tech-stack)
  - [🗄️ Back‑end & Data](#back-end--data)
  - [☁️ Cloud & DevOps](#cloud--devops)
  - [🎬 Streaming & Media](#streaming--media)
  - [🖥️ Front‑end](#front-end)
- [Building Now](#building-now)
- [Selected Work](#selected-work)
- [Learning Now](#learning-now)
- [Resume](#resume)
- [Contact Me](#contact-me)
<!-- /TOC -->

---

## About Me
I’m **Fahim Arif**, a backend‑leaning full‑stack engineer with **7+ years** of experience building backend services and full‑stack products in **Node.js and TypeScript**, including **3 years on a large video streaming platform**. I design REST APIs, data models and service integrations on **PostgreSQL, Redis and AWS**, and I debug production issues end to end, from API data defects to DRM, ad‑insertion and adaptive‑streaming failures.

Based in Dhaka, Bangladesh. Fully remote for 7 years, with 4+ hours of overlap with US Eastern.

---

## Tech Stack

### 🗄️ Back‑end & Data
- <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" alt="Node.js" width="24" align="middle" /> **Node.js**
- <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nestjs-colored.svg" alt="NestJS" width="24" align="middle" /> **NestJS** (also Express)
- <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" alt="TypeScript" width="24" align="middle" /> **TypeScript**
- <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" alt="Python" width="24" align="middle" /> **Python** (Django)
- <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="24" align="middle" /> **PostgreSQL** (Prisma), MySQL, MongoDB
- <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" alt="Redis" width="24" align="middle" /> **Redis**, BullMQ

### ☁️ Cloud & DevOps
- <img src="https://www.vectorlogo.zone/logos/amazon/amazon-tile.svg" alt="AWS" width="24" align="middle" /> **AWS** (EC2, S3, Lambda, RDS, Cognito, CloudFront)
- <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" width="24" align="middle" /> **Docker**, Docker Compose
- **CI/CD:** Azure DevOps

### 🎬 Streaming & Media
- **Players:** Shaka Player, hls.js
- **Protocols:** HLS, DASH
- **DRM:** FairPlay, Widevine
- **AWS Media:** MediaPackage, MediaTailor, CloudFront CDN
- **Also:** EPG systems

### 🖥️ Front‑end
- <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" alt="React" width="24" align="middle" /> **React.js**, Redux
- <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nextjs-colored.svg" alt="Next.js" width="24" align="middle" /> **Next.js**

---

## Building Now

### 🚀 [vod-platform-api](https://github.com/fahim-arif/vod-platform-api)

A video‑on‑demand backend, built in the open.

**Stack:**  
NestJS • PostgreSQL (Prisma) • Redis • BullMQ • Docker Compose

**Design decisions:**  
- Hybrid catalog: movies and series, seasons with their own metadata, episodes as children
- Separate playable assets per title (trailers, alternate cuts)
- Availability windows by region, plan and licensing period
- Soft unpublish instead of hard delete, to preserve watch history

---

## Selected Work

### 🎬 FreeCast (contract, 2023 to 2026)

A large video streaming platform. I worked across the Python backend, the API layer and the playback stack.

- Optimized slow Django endpoints with query optimization, indexing, N+1 fixes, Redis caching and pagination, cutting response times from a few seconds to a few hundred milliseconds.
- Traced a catalog API defect that served mismatched titles under a live network filter and delivered the fix spec to the backend team.
- Designed an auth token hardening plan: access tokens in memory, bearer‑token origin allowlisting, and backend‑issued HttpOnly refresh‑token cookies.
- Resolved two production playback failures at the protocol level: a DASH ad‑insertion stall (codec‑string mismatch between AWS MediaPackage and MediaTailor manifests) and a Safari FairPlay DRM failure (EME/MediaKeys state corruption).
- Reworked VOD package and entitlement resolution for a subscription package launch.

---

## Learning Now
- System design
- PostgreSQL performance
- Redis and queues
- AWS Solutions Architect Associate (in progress)

---

## Resume
📄 [Download my resume (PDF)](Fahim_Arif_Resume.pdf)

---

## Contact Me
- 🔗 [LinkedIn](https://www.linkedin.com/in/fahim-arif/) • [GitHub](https://github.com/fahim-arif)
- ✉️ fahim.cuet77@gmail.com

Open to remote backend and full‑stack roles worldwide.
