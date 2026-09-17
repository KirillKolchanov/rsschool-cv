# Kirill Kolchanov

**Frontend/Mobile (React/React Native) developer**

## Contacts

- **Location:** Warsaw, Poland (access to labor market)
- **Email:** [kirill.ko.work@gmail.com](mailto:kirill.ko.work@gmail.com)
- **LinkedIn:** [@kirillkolchanov](https://www.linkedin.com/in/kirillkolchanov/)
- **GitHub:** [KirillKolchanov](https://github.com/KirillKolchanov)

## About Me

Frontend Developer with 4 years of experience building scalable web and mobile applications with **React, React Native, TypeScript**, and **Next.js**. Experienced in **FinTech**, **Healthcare**, and **enterprise AI platforms**, developing complex user interfaces, API integrations, data-heavy applications, and cross-platform solutions.

Strong focus on **performance optimization, state management, testing, accessibility,** and **scalable frontend architecture**. Experienced working in large TypeScript monorepos, integrating enterprise authentication, real-time APIs, and AI-powered features.

## Skills

- **Languages & Core:** TypeScript, JavaScript, HTML5, CSS3/SASS
- **Frameworks & UI:** React, React Native, Next.js, Tailwind CSS, Fluent UI, Material UI
- **State & Data:** TanStack Query, Redux Toolkit, Zustand, Axios, GraphQL, REST APIs, WebSockets
- **Tooling & Architecture:** Vite, Webpack, Monorepos (npm workspaces), Storybook, VS Code Extensions, Docker
- **Testing & CI/CD:** Vitest, Playwright, Jest, React Testing Library, GitHub Actions, GitLab CI/CD
- **Performance & Security:** Code-Splitting, SWR Caching, Startup Parallelization, Auth.js/OAuth, Vercel AI SDK
- **Cloud & Infrastructure:** AWS, Docker

## Code Example

Codewars kata: convert dash/underscore delimited words into camel casing. The first word should be capitalized only if the original word was capitalized.

```js
function toCamelCase(str) {
  return str.replace(/[-_](\w)/g, (_, char) => char.toUpperCase());
}
```

## Experience

### Web Application Development

#### AI Platform | React 19, TypeScript, Playwright
*Akvelon (for Microsoft) · May 2026 – Now*

Enterprise AI platform for scientific research. The goal is to give researchers a single environment – a **web shell** and a **VS Code-based IDE** – where they can run AI-assisted investigations, manage **AI agents** and work with scientific data. Working in a large TypeScript **monorepo** shared by the web app, the extension and internal SDK packages.

- **VS Code Extension & Webviews:** Engineered agent management/chat UI in React & Fluent UI v9; migrated legacy code to typed components.
- **Data & State:** Handled high-volume datasets using cursor-based pagination, SWR caching, and shared internal API clients.
- **Performance:** Cut startup latency through webview parallelization, bundle splitting, and resource caching.
- **Enterprise Auth:** Integrated Azure & MSAL/Entra ID for multi-tenant auth and dynamic RBAC UI states.
- **Testing & CI/CD:** Enforced ≥85% test coverage (Jest, Playwright); set up ESLint/CodeQL gates in Azure DevOps.
- **Observability:** Added App Insights monitoring and telemetry; conducted peer code reviews.

#### Healthcare Quality Platform | Next.js, React, TypeScript
*W-hoch2 (short-term contract) · Apr 2025 – Apr 2026*

- **Engineered and launched** a high-performance healthcare platform using **Next.js 16, React 19, TypeScript**, and **Tailwind CSS**, serving institutional data with advanced filtering, drag-and-drop comparison tools, and interactive benchmark visualizations.
- **Optimized data retrieval and routing** by integrating **RESTful APIs** with server-side pagination and robust error handling, implementing URL state synchronization to ensure seamless shareable views and user state retention.
- **Architected a multi-language localization system** (DE/FR/IT) utilizing automatic detection (cookies, domains, browser locale) with server-side initialization, driving improved **SEO** performance and global accessibility.
- **Championed web accessibility and production readiness** by implementing comprehensive **ARIA** attributes, keyboard navigation focus states, and automated testing via **Storybook a11y**, alongside customized print utilities for structured reporting.

#### GenAI Platform | Next.js, TypeScript, Redux, Jest, RTL, OpenAI API
*Verses AI · Jan 2023 – Jan 2024*

Gen-UI is an R&D platform built to showcase active inference-based autonomous agents operating across virtual worlds, real-world physical environments, and video game simulations.

- Wrote robust **unit and integration test suites** using **Jest** and **React Testing Library** for critical UI components and complex business logic, presenting detailed test coverage metrics directly to stakeholders to enforce rigorous quality standards.
- Translated complex **Figma** design systems into pixel-perfect, responsive UI updates while maintaining absolute visual consistency, with a primary focus on high-stakes AI chat components and critical-path robot control interfaces.
- Engineered and scaled a custom **API request architecture** to seamlessly integrate backend microservices, guaranteeing fault-tolerant data flow and low-latency communication for real-time robot task management and performance analytics.

#### A-Infinity (FinTech App) | React, TypeScript, Redux, Jest, RTL
*Andersen Lab · Mar 2021 – Feb 2022*

- Engineered core credit and deposit modules for a **high-traffic FinTech banking app** using **React, TypeScript, Redux Toolkit,** and **RTK Query**, ensuring performant state management and robust API caching.
- Built scalable, maintainable UI components using semantic **HTML5** and **SASS** with strict adherence to the **BEM** methodology.
- Architected complex multi-step form workflows utilizing **React Hook Form** and **Zod** for bulletproof client-side validation, integrated seamlessly with a Java backend to guarantee secure data handling and clear user feedback.
- Collaborated closely with QA and Product teams to resolve critical production bugs, implemented secure user authentication workflows, and delivered regular sprint demonstrations to key stakeholders.

### Mobile Application Development

#### Courier Companion App | React Native, TypeScript, Redux
*Chapman Freeborn OBC (short-term contract) · Feb 2024 – Mar 2025*

- Upgraded the OBC Courier Companion app across **iOS** and **Android** from **React Native 0.72** through **0.73** to **0.74**, modernizing the core codebase and native dependencies.
- Modernized native location tracking by migrating from legacy packages to **@react-native-community/geolocation**, updating background and foreground services to maintain reliable cross-platform tracking.
- Authored and applied custom native compatibility patches for **react-native-navigation** on **Android** and **react-native-share-menu** on **iOS** to ensure stable builds post-migration.

#### MedCare (Healthcare App) | React Native, TypeScript, React Navigation
*Andersen Lab · Mar 2022 – Dec 2022*

- Developed core features for a Canadian healthcare clinic cross-platform mobile app, including authentication, user profiles, subscription management, and structured in-app navigation using **TypeScript** and **React Navigation**.
- Implemented robust data validation for complex user inputs using **React Hook Form**, ensuring seamless cross-platform functionality across **iOS** and **Android**.
- Integrated critical mobile capabilities including push notifications, real-time geolocation services, and deep linking to optimize user engagement and retention.

## Education

- **Vistula University** – Bachelor's in Project Management (2023)
- **RS School** – Fullstack Engineering course

## Languages

- **English** – B2
- **Polish** – B1
- **Russian** – native
- **Belarusian** – native
