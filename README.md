# Hi, I'm Dominik 👋

**Backend-minded developer who started on the frontend.** Java · Spring Boot · PostgreSQL · React/TypeScript

I started programming in **2022** with React, Next.js and Angular. Over time I got more curious about
what happens **behind the interface**: how data flows, how systems talk to each other, and how to solve
problems properly. That pulled me toward **backend development**. Today I mainly work with **Java**,
system design and computer vision, and I keep the frontend experience I gained along the way.

To me, languages are tools. What I care about is **understanding the problem and finding the right way to solve it**.

[📩 Email](mailto:dominik.gadzina1@gmail.com) · [💼 LinkedIn](https://www.linkedin.com/in/dominik-gadzina) · [🔗 Portfolio](https://dominikgadzina.vercel.app/)

---

## 🔭 Building now: ScreenSort

<a href="https://github.com/Pum2A/screensort-releases/releases"><img src="assets/screensort-library.png" alt="ScreenSort library: the whole folder on one screen with AI categories and bulk decisions"></a>

**A local-first Windows app that turns a folder of screenshot chaos into named, sorted copies.**
It reads every image with local OCR and a vision model, proposes a name and a category, and lets you
approve them one by one or in bulk. Then it writes a verified copy into category folders.
Nothing is uploaded, and the originals are never touched.

- **Java 25 + Spring Boot 4** backend: background scan jobs, SHA-256 catalog in PostgreSQL, Flyway migrations, versioned decisions, verified copying.
- **React 19 + TypeScript** UI in a **Tauri 2 (Rust)** shell: dense library, multi-select with a bulk bar, duplicate finder, signed in-app updates.
- **Python + FastAPI** service running **RapidOCR** and **Florence-2** on the CPU, started on demand by the desktop app.
- Tested with JUnit 5, Testcontainers, node:test, cargo test and pytest in CI.

<table>
<tr>
<td><img src="assets/screensort-review.png" alt="Bulk review with a category pill on every card"></td>
<td><img src="assets/screensort-duplicates.png" alt="Byte-identical duplicates compared side by side"></td>
</tr>
<tr>
<td align="center"><sub>Bulk review: keys 1–5 set the category</sub></td>
<td align="center"><sub>Duplicates: keep one copy, skip the rest</sub></td>
</tr>
</table>

👉 [**Download the Windows preview**](https://github.com/Pum2A/screensort-releases/releases) (the source code is private for now).

### Also exploring: RealityDiff

An image-based system that compares photos of the same place over time and detects what was
**added, removed or changed**. Built with Java, OpenCV, Spring Boot and PostgreSQL.

---

## 🧰 Tech stack

**Backend** &nbsp;
![Java](https://img.shields.io/badge/Java-191C1F?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-191C1F?style=flat-square&logo=springboot&logoColor=6DB33F)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-191C1F?style=flat-square&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-191C1F?style=flat-square&logo=flyway&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit_5-191C1F?style=flat-square&logo=junit5&logoColor=25A162)
![Testcontainers](https://img.shields.io/badge/Testcontainers-191C1F?style=flat-square&logo=testcontainers&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-191C1F?style=flat-square&logo=opencv&logoColor=white)
![Python](https://img.shields.io/badge/Python-191C1F?style=flat-square&logo=python&logoColor=FFD43B)

**Frontend** &nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-191C1F?style=flat-square&logo=typescript&logoColor=3178C6)
![React](https://img.shields.io/badge/React-191C1F?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-191C1F?style=flat-square&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-191C1F?style=flat-square&logo=angular&logoColor=DD0031)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-191C1F?style=flat-square&logo=tailwindcss&logoColor=06B6D4)

**Desktop & tools** &nbsp;
![Tauri](https://img.shields.io/badge/Tauri-191C1F?style=flat-square&logo=tauri&logoColor=FFC131)
![Rust](https://img.shields.io/badge/Rust-191C1F?style=flat-square&logo=rust&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-191C1F?style=flat-square&logo=docker&logoColor=2496ED)
![Git](https://img.shields.io/badge/Git-191C1F?style=flat-square&logo=git&logoColor=F05032)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-191C1F?style=flat-square&logo=githubactions&logoColor=2088FF)

---

## 📂 Earlier public projects

| Project | What it is | Stack |
| --- | --- | --- |
| [BookSelf](https://github.com/Pum2A/BookSelf) · [live](https://bookingfullstack.vercel.app/) | Service booking platform | Next.js 15, React 19, Prisma |
| [DSA](https://github.com/Pum2A/DSA) | Full-stack app split into a frontend and a backend | Next.js, React 19, .NET |
| [Foodify](https://github.com/Pum2A/Foodify) · [live](https://my-recipe-app-eta.vercel.app) | Recipe app with auth and real-time data | Next.js, Firebase |
| [AI Chat App](https://github.com/Pum2A/ai-chat-app) · [live](https://ai-chat-app-blond.vercel.app) | Chat that answers with AI language models | Next.js, TypeScript |
| [Campaign form](https://github.com/Pum2A/angular-zadanie) · [live](https://angular-zadanie-f54w.vercel.app) | Create and edit ad campaigns (recruitment task) | Angular, TypeScript |
| [Minecraft clone](https://github.com/Pum2A/minecraft-clone) | Minecraft-style game experiment | C++ |
