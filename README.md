<p align="center">
  <a href="https://crowncode.higginsd.com"><img src="assets/hero.svg" width="100%" alt="CrownCode AI: AI websites, built with royal precision. Animated cover with the gold crown radiating light beside a browser window that assembles a website block by block under a gold selection frame." /></a>
</p>

<h1 align="center">CrownCode AI</h1>

<p align="center"><strong>An AI website builder that turns a guided brand intake into a polished, deployable website draft, then refines it with you.</strong></p>

<p align="center">
  <a href="https://crowncode.higginsd.com"><img src="assets/btn-open.svg" height="44" alt="Try the builder" /></a>&nbsp;
  <a href="https://www.higginsd.com/work/crowncode-ai"><img src="assets/btn-case.svg" height="44" alt="Case study" /></a>&nbsp;
  <a href="https://davishiggins.com"><img src="assets/btn-dh.svg" height="44" alt="Davis Higgins" /></a>
</p>

<p align="center"><sub>Live · A Higgins Digital product · Designed and built by Davis Higgins</sub></p>

---

## See it in motion

<p align="center">
  <img src="assets/demo.gif" width="880" alt="Screen recording of the CrownCode AI builder: filling in Business Basics for a sample roofing company and continuing to the Brand Direction step." />
</p>

<p align="center"><sub>Real capture of the live builder with a fictional sample business. <a href="assets/demo.png">Static frame</a></sub></p>

## What it does

- **A guided intake, not a blank prompt box.** A step-by-step flow captures the business, the brand direction, the site structure, and the content a strong first draft needs.
- **A complete website package.** Each build delivers the strategy, sitemap, design system, page-by-page copy, starter code, and a plain-English guide to taking the site live.
- **Revisions that refine.** Ask for changes and CrownCode updates the existing draft instead of starting over.

## Why I built it

The opening days of a website project repeat the same work every time: turning a rough brand idea into a first structured draft. It's necessary, but it's the least valuable part of a build, because it happens before anyone has anything concrete to react to.

CrownCode shortens that beginning. It produces a polished first draft fast, and a person directs and refines it from there.

## What I built

- Product design, the guided intake, and the result and revision experiences
- The generation and revision engine behind every website package
- Starter designs for the most common kinds of business websites
- CrownCode's own navy-and-gold identity, deliberately distinct from the studio's

<details>
<summary><strong>How it's put together</strong></summary>

<br />

```mermaid
flowchart TB
    I[Guided brand intake] --> E[CrownCode generation engine]
    E --> R[Website package<br/>strategy · design · pages · code]
    R --> V[Revision request]
    V --> E
```

| Decision | Why |
|---|---|
| **Structure in, structure out** | Every build follows the same shape, so the interface can present it cleanly and a revision can target exactly the part that needs to change. |
| **Generation stays on the server** | The engine never runs in the browser, and every request is validated before work begins. |
| **Fail clearly, never halfway** | If a build can't be completed, the user gets a clear message instead of a half-finished package. |

</details>

## Screens

<table>
  <tr>
    <td width="62%"><img src="assets/screenshot-home.png" alt="CrownCode AI homepage: 'AI websites, built with royal precision' beside a gold crown, with Start Building and See How It Works buttons." /></td>
    <td rowspan="2" width="38%" align="center"><img src="assets/screenshot-mobile.png" width="300" alt="CrownCode AI homepage on a phone." /></td>
  </tr>
  <tr>
    <td><img src="assets/screenshot-builder.png" alt="CrownCode AI builder, step 1 (Business Basics), with fields for name, industry, location, description, target customer, and main goal." /></td>
  </tr>
</table>

<sub>Homepage · Intake, step one · Homepage on mobile</sub>

## Technology

| Layer | Technology |
|---|---|
| App | Next.js, TypeScript, Tailwind CSS |
| Motion | Framer Motion |
| Hosting | Vercel |

---

<p align="center">
  <a href="https://crowncode.higginsd.com"><img src="assets/btn-open.svg" height="44" alt="Try the builder" /></a>&nbsp;
  <a href="https://github.com/DavisHiggins"><img src="assets/btn-more.svg" height="44" alt="More of my work" /></a>
</p>

<p align="center"><sub>© 2026 Davis Higgins. All rights reserved. CrownCode AI and its crown mark belong to Higgins Digital.</sub></p>
