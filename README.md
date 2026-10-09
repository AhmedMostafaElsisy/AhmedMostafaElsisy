<div align="center">

# Hi, I'm Ahmed Mostafa 👋

### Flutter Developer & AI Engineer · Mobile Engineer @ iDen2 · Founder of [Mudawy](https://mudawy.com) · Mobile Security

<p>
  <a href="https://ahmedmostafa-dev.vercel.app"><img src="https://img.shields.io/badge/Portfolio-AhmedOS-c6f432?style=for-the-badge&logo=vercel&logoColor=black&labelColor=0b1220" alt="Portfolio: AhmedOS"></a>
  <a href="https://www.linkedin.com/in/ahmed-mostafa-cc/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ahmedmostafacc@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Cairo,_Egypt-1f2937?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Cairo, Egypt">
  <img src="https://img.shields.io/badge/Open_to-Remote-22c55e?style=for-the-badge" alt="Open to remote">
</p>

</div>

---

## 🧑‍💻 About Me

I build **secure, high-performance cross-platform apps** for iOS and Android with Flutter. I have **4+ years** in the field and **15+ production apps** across fintech, digital identity, real estate, logistics, and e-commerce.

- 🔐 Right now I'm building an **identity wallet** at **[Iden2](https://iden2.com)**. The work covers encrypted offline-first credential storage, Android hardening, and Remote Config-driven UI.
- 🩺 On the side, I founded and build **[Mudawy (مُداوي)](https://mudawy.com)**, a clinic management product for doctors in Egypt. It has an offline-first desktop app and a multi-tenant SaaS web version, and I own it end to end.
- 🏗️ I care about **Clean Architecture**, **testability** (I took a codebase from 0% to 80%+ coverage), and **fully automated releases** with Fastlane and GitHub Actions.
- 👥 I've led a team of 4 developers, set coding standards, and mentored junior engineers.
- 🏆 My graduation project placed in the **Top 10 globally** at the **Google Solution Challenge**.

---

## 🩺 Building: Mudawy (مُداوي)

<a href="https://mudawy.com"><img src="https://img.shields.io/badge/mudawy.com-Live-0ea5e9?style=for-the-badge" alt="mudawy.com"></a>
<a href="https://app.mudawy.com"><img src="https://img.shields.io/badge/Web_App-app.mudawy.com-14b8a6?style=for-the-badge" alt="app.mudawy.com"></a>

**Clinic management for solo doctors in Egypt.** It's Arabic-first (RTL) with full English support. I designed and built every piece of it:

| Product | What it is | Stack |
| --- | --- | --- |
| 🖥️ **Desktop app** | Offline-first doctor + reception stations on one codebase. Patient data stays on an encrypted local database. Reception syncs over the clinic LAN, with pairing codes and an offline queue that syncs later. Windows installers are built in CI. | Flutter Desktop, Drift/SQLite, BLoC, go_router |
| ☁️ **Web SaaS** | Multi-tenant monthly-subscription version with tenant isolation through PostgreSQL row-level security. Covers the patient queue, visits, prescriptions, appointments, billing, and Excel imports. | NestJS + Fastify, Drizzle, PostgreSQL, React 19, TanStack, Tailwind, Turborepo |
| 🛡️ **Admin console** | One staff console for managing customers of both products: accounts, pricing, requests, leads, audit log, background jobs. | React + Vite, OpenAPI → orval client |
| 🌐 **Landing site** | Marketing site with an interactive modular-pricing configurator and a leads flow. | Next.js, shadcn/ui, next-intl, Supabase, Vercel |

**Highlights:** a modular pricing model (core module plus add-ons, priced by term), contracts shared from zod through OpenAPI to a typed client, pure domain rules with 100% test coverage, and golden UI tests for light and dark themes.

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=flutter,dart,kotlin,androidstudio,firebase,githubactions&perline=6" alt="Mobile stack" /><br/>
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,nestjs,postgres,sqlite,mysql,supabase,tailwind,docker,vercel&perline=11" alt="Web stack" />
</p>

| Area | Tools |
| --- | --- |
| **Mobile** | Flutter, Dart, Kotlin, Android SDK |
| **Architecture** | Clean Architecture, BLoC, Provider, SOLID, Design Patterns |
| **Security** | FlutterSecureStorage, Android Keystore, Encrypted Local Storage, Secure Credential Management |
| **Testing** | Unit & Widget Testing, `flutter_test`, lcov, 80%+ coverage |
| **CI/CD** | GitHub Actions, Fastlane, Android & iOS release pipelines, PR gating |
| **Web & Backend** | TypeScript, React, Next.js, NestJS, Drizzle ORM, PostgreSQL (RLS), zod/OpenAPI |
| **Data & Cloud** | REST APIs, Firebase, Remote Config, Supabase, SQLite/Drift, MySQL, Socket.io, Docker, Vercel |
| **Workflow** | Git, Agile/Scrum, Claude Code, Cursor |

---

## 💼 Experience

**Mobile Engineer** · [iDen2](https://iden2.com) (Remote) · _Jun 2025 – Present_
> Identity Wallet, a secure platform for managing digital identity
- Raised unit test coverage from **0% to 80%+** across core modules, which cut regression bugs by **60%+**.
- Built an **encrypted offline-first credential store** (FlutterSecureStorage + Android Keystore) that eliminated all redundant API calls.
- Found and fixed **critical Android security vulnerabilities** that could expose sensitive data.
- Refactored the whole codebase to **Clean Architecture** and built a **Remote Config-driven rendering engine**, so credential fields can change without a new release.
- Automated Android and iOS production releases with **Fastlane + GitHub Actions**. Releases now need no manual steps.

**Senior Flutter Developer** · Nuwas · _Oct 2023 – Jun 2025_
- Shipped 3 production apps: **Nuwas** (AI machine diagnostics with ML inference), **Kera** (real estate lifecycle), and **K-Wealth** (real-time stock trading).
- Led a team of 4 developers, set coding standards, wrote the technical docs, and mentored 2 juniors.

**Mid-Level → Junior Flutter Developer** · Queen Tech Solutions · _Oct 2021 – Oct 2023_
- Shipped **11+ Flutter apps** across e-commerce, transportation, and service booking using Firebase, BLoC, and Provider. Also reviewed code for 3 junior developers.

---

## 🚀 Featured Work

| Project | Domain | Highlights |
| --- | --- | --- |
| 🩺 **[Mudawy](https://mudawy.com)** | HealthTech SaaS | Founder. Offline-first Flutter desktop app, multi-tenant NestJS/React web app, admin console, landing site |
| 🪪 **Iden2 Wallet** | Digital Identity | Encrypted offline-first storage, Keystore, dynamic Remote Config UI |
| 📈 **K-Wealth** | Fintech | Real-time market feeds, portfolio tracking, live trading |
| 🤖 **Nuwas** | AI / Industrial | ML-powered machine fault diagnosis with guided repair flows |
| 🏠 **Kera** | Real Estate | Rentals, sales, and maintenance requests in one app |
| 🏋️ **Himma & Rashatak** | Fitness (freelance) | Member and coach roles in one shared codebase, scheduling, messaging |
| 🦉 **E-Owl** | EdTech / ML | Facial emotion recognition to track student engagement, Google Solution Challenge Top 10 |

<sub>More: Shiprex (shipping) · Aram (HR) · My Suez (e-commerce & tracking) · InNeed (service booking) · Omda / PMC / Motamayez (transport & tracking)</sub>

---

## 🏆 Achievements

- 🌍 **Top 10 globally**, Google Solution Challenge Demo Day
- 🥇 **1st place**, Ministry of Higher Education Science Clubs Competition
- 🏅 **Top 15 of 400+ teams**, Edu Hackathon
- 🚀 **Phase 2 qualifier**, Dell Envision the Future Competition

---

## 🎓 Education

**B.Sc. Computer Science**, Future Academy, Higher Future Institute for Specialized Technological Studies (2021)

---

<div align="center">

### 📫 Let's build something together

[Portfolio](https://ahmedmostafa-dev.vercel.app) · [LinkedIn](https://www.linkedin.com/in/ahmed-mostafa-cc/) · [ahmedmostafacc@gmail.com](mailto:ahmedmostafacc@gmail.com)

</div>
