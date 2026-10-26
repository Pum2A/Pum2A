<img src="assets/header.svg" alt="$ whoami — Dominik Gadzina, backend, Java and computer vision. Started on the frontend in 2022 with React, Next.js and Angular, then went looking for what happens behind the interface. Now: Java, system design and computer vision." width="100%">

<br>

<img src="assets/label-now.svg" alt="$ cat ./building-now" height="50">

<a href="https://github.com/Pum2A/screensort-releases/releases"><img src="assets/screensort.svg" alt="ScreenSort: a local-first Windows app that turns screenshot chaos into named, sorted copies. Local OCR and a vision model propose names and categories, you approve them in bulk. Java 25, Spring Boot 4, PostgreSQL, React 19, Tauri 2, FastAPI, RapidOCR, Florence-2. Zero uploads." width="100%"></a>

<a href="https://github.com/Pum2A/screensort-releases/releases"><img src="assets/screensort-library.png" alt="ScreenSort library: the whole folder on one screen with AI categories and bulk decisions" width="100%"></a>

<table>
<tr>
<td width="50%"><img src="assets/screensort-review.png" alt="Bulk review: every waiting proposal with a category pill per card"></td>
<td width="50%"><img src="assets/screensort-duplicates.png" alt="Duplicates: byte-identical files side by side"></td>
</tr>
<tr>
<td><sub><code>review</code> · every proposal on one screen, keys 1–5 set the category</sub></td>
<td><sub><code>duplicates</code> · keep one copy, the rest never reach the sorted folder</sub></td>
</tr>
</table>

```text
under the hood
├── background scan jobs + SHA-256 catalog in PostgreSQL
├── versioned decisions: a stale form never overwrites a newer one
├── verified copying: every file re-hashed before it is kept
├── Rust shell owns the Java, Python and database processes
├── signed in-app updates
└── CI: JUnit + Testcontainers · node:test · cargo test · pytest
```

`❯` [**download the Windows preview**](https://github.com/Pum2A/screensort-releases/releases) &nbsp;·&nbsp; <sub>source is private for now</sub>

<br>

<img src="assets/label-stack.svg" alt="$ cat stack.ts" height="50">

<img src="assets/stack.svg" alt="const stack = { backend: java, spring boot, postgresql, flyway, junit 5, testcontainers; vision: opencv, python, fastapi, rapidocr, florence-2; frontend: typescript, react, next.js, angular, tanstack query, tailwind; desktop: tauri, rust; ops: docker, github actions, git }" width="100%">

<br>

<img src="assets/label-projects.svg" alt="$ ls ~/projects" height="50">

<table>
<tr>
<td width="50%"><a href="https://github.com/Pum2A/BookSelf"><img src="assets/project-bookself.svg" alt="BookSelf: service booking platform. Next.js 15, React 19, Prisma. Live." width="100%"></a></td>
<td width="50%"><a href="https://github.com/Pum2A/DSA"><img src="assets/project-dsa.svg" alt="DSA: full-stack app with a Next.js front and a .NET back" width="100%"></a></td>
</tr>
<tr>
<td><a href="https://github.com/Pum2A/Foodify"><img src="assets/project-foodify.svg" alt="Foodify: recipes with auth and real-time data. Next.js, Firebase. Live." width="100%"></a></td>
<td><a href="https://github.com/Pum2A/ai-chat-app"><img src="assets/project-ai-chat.svg" alt="AI Chat App: chat that answers with language models. Next.js, TypeScript. Live." width="100%"></a></td>
</tr>
<tr>
<td><a href="https://github.com/Pum2A/angular-zadanie"><img src="assets/project-campaign.svg" alt="Campaign form: create and edit ad campaigns. Angular, TypeScript. Live." width="100%"></a></td>
<td><a href="https://github.com/Pum2A/minecraft-clone"><img src="assets/project-minecraft.svg" alt="Minecraft clone: Minecraft-style game experiment in C++" width="100%"></a></td>
</tr>
</table>

<br>

<img src="assets/label-contact.svg" alt="$ ping dominik" height="50">

```text
email     dominik.gadzina1@gmail.com
linkedin  linkedin.com/in/dominik-gadzina
web       dominikgadzina.vercel.app
```

[email](mailto:dominik.gadzina1@gmail.com) · [linkedin](https://www.linkedin.com/in/dominik-gadzina) · [portfolio](https://dominikgadzina.vercel.app/)
