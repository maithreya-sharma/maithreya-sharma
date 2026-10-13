# Hi, I'm Maithreya Sharma Mangalampalli 👋

**Angular Developer · Frontend Engineer** · Hyderabad, India

I'm an Angular developer with 4 years of experience building micro-frontend applications for a cloud-native healthcare claims platform. I specialize in drug utilization review (DUR) safety modules and complex rule-driven forms that manage thousands of records. I deliver features through an agentic AI SDLC on Claude Code, and back every change with manual testing, unit tests and code review.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maithreya-sharma-mangalampalli)

---

## 💼 Currently

**Software Engineer at SS&C Technologies** (since Oct 2022). I work on **DomaniRx**, a cloud-native pharmacy benefits management (PBM) and claims adjudication platform. I build the create, view and update screens for 14 clinical rule modules that decide claim eligibility from drug-usage safety checks.

---

## 🚀 Featured project

### [Formloom: drag-and-drop form builder](https://github.com/maithreya-sharma/formloom)

Design a form visually, add validation and show/hide rules, try it as a real Angular Reactive Form, and share it as a link. There's no backend.

- A **signal-based store** with undo/redo, where rapid edits merge into a single step
- **Dynamic typed Reactive Forms** generated at runtime from a JSON schema, with conditional fields that disable themselves when hidden
- **Angular CDK drag-and-drop**, a live schema linter, and validated JSON import/export
- Forms **compressed into share links** with the native `CompressionStream`
- **Jasmine/Karma** unit tests, a **Playwright** end-to-end test, and **GitHub Actions** CI/CD to GitHub Pages

[Live demo](https://maithreya-sharma.github.io/formloom/) · [Code](https://github.com/maithreya-sharma/formloom)

---

## 🏆 Highlights

- **🔼 Angular v20 → v21 upgrade.** I led the upgrade across 5 micro-frontend repositories. I migrated templates to the new control flow and subscriptions to `takeUntilDestroyed`, and aligned child-app dependencies with the host to prevent shared-library conflicts at runtime.
- **🧱 Base-class architecture.** I introduced an abstract base-class layer (`BaseCreateBlock`, `BaseUpdateBlock`, `BaseViewBlock`) that centralizes API calls, form setup and drawer handling. It's now the standard for every new rule module.
- **🗂️ Dynamic detail drawer.** One reusable component serves every rule module. It maps each record's JSON into labeled field–value blocks at runtime and stays in sync with form edits.
- **🤖 AI post-merge review agent.** I built this self-initiated tool on Claude Code with GitHub MCP. Every hour it checks merges on all 5 repositories against each module's functional flows. It caught 30+ bugs before QA.
- **⚡ Agentic SDLC.** I own the TRD-to-deployment stage on Claude Code. With it, comparable enhancements dropped from about 5 sprints to about 2 (roughly 60% faster), across 3 features and 50–60 bug fixes.
- **📦 Shared component library.** I moved duplicated components into the team's npm library, which 5 repositories consume.
- **📊 High-volume forms.** I build Reactive Forms with FormArrays and custom validators that handle thousands of limits per module. Pagination, virtual scrolling and RxJS-driven on-demand loading keep them fast.
- **✅ Quality.** I keep 80% unit-test coverage with Jasmine and Karma, have fixed 100+ bugs, and remediate SonarQube, ESLint and CodeQL issues.

---

## 🧰 Tech stack

**Core**
![Angular](https://img.shields.io/badge/Angular_v14--21-DD0031?style=flat&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat&logo=reactivex&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white)

Reactive Forms · New Control Flow (`@if` / `@for` / `@switch`) · Angular CLI · NgModules

**Architecture:** Micro-Frontend Architecture · Native Federation · Shared Component Libraries · REST API Integration

**UI**
![PrimeNG](https://img.shields.io/badge/PrimeNG-DD0031?style=flat)
![Angular Material](https://img.shields.io/badge/Angular_Material-3F51B5?style=flat&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Testing & quality**
![Jasmine](https://img.shields.io/badge/Jasmine-8A4182?style=flat&logo=jasmine&logoColor=white)
![Karma](https://img.shields.io/badge/Karma-56C5A8?style=flat&logo=karma&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat&logo=eslint&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat&logo=sonarqube&logoColor=white)
![CodeQL](https://img.shields.io/badge/CodeQL-2F363D?style=flat&logo=github&logoColor=white)

**Tooling**
![npm](https://img.shields.io/badge/npm-CB3837?style=flat&logo=npm&logoColor=white)
![esbuild](https://img.shields.io/badge/esbuild-FFCF00?style=flat&logo=esbuild&logoColor=black)
![PostCSS](https://img.shields.io/badge/PostCSS-DD3A0A?style=flat&logo=postcss&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**AI-assisted development**
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat&logo=githubcopilot&logoColor=white)

---

## 🌱 Currently learning

- **React.js**, building on my Angular and TypeScript foundation

---

## 🤝 How I work

- I take features from technical requirements all the way to deployment.
- I spot repeated patterns early and turn them into reusable code.
- I work closely with Product Owners, QA and fellow developers.
- I catch defects before they reach QA.

---

## 🎓 Education

- **B.Tech, Electronics & Communication Engineering**, Vignana Bharathi Institute of Technology (2019–2022)
- **Diploma, Electronics & Communication Engineering**, Government Institute of Electronics (2015–2019)

---

## 📫 Reach me

- LinkedIn: [maithreya-sharma-mangalampalli](https://www.linkedin.com/in/maithreya-sharma-mangalampalli)
- Open to Angular / frontend roles 🚀
