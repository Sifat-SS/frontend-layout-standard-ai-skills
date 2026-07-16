# Premium Frontend Web Development Standards 🚀✨
**Author**: Sifat  
**Status**: Universal / Scenario-Aware / Battle-Tested

## **About** 📖
While developing high-end frontend projects and dense instrumentation dashboards with AI agents, I observed a recurring engineering pattern: **generic AI-generated code often applies a one-size-fits-all approach to every layout**. 
- When building marketing landing pages, generic AI misses mobile durability, causing text cropping and WebView breakage.
- When building dense admin consoles or instrumentation cockpits (`/admin`), applying standard landing-page fluidity (`auto-fit`, fluid `h1/h2` clamps) destroys tool panels, causes edge collisions against navigation sidebars, and leaves form elements touching card boundaries.
- When configuring DevOps, applying traditional cPanel cache-busting (`?v=2.0`) to modern edge runtimes (`Next.js / Cloudflare`) interferes with immutable CDN chunking.

To solve this fundamentally, I created this repository as a **Universal, Scenario-Aware AI Skill File (`premium-frontend-standards`)**. It features a **Conditional Execution Engine** that instructs AI agents to first classify the target architecture and enforce only the matching conditional protocol:

1. **Scenario A: Responsive Durability & Fluid Grid Protocol (`Marketing & Client Shells`)**  
   Enforces the "No-Cage" Rule (`height: auto` required), in-app WebView overrides (`width: 100% !important`), aspect-ratio scaling, and editorial multi-column tablet ratios (`1.5fr 1fr 1fr`).
2. **Scenario B: High-Density Cockpit & Admin Protocol (`Command Decks & CRMs`)**  
   Enforces single-view cockpit density without desktop stacking, rigid navigation sidebars (`w-[220px]`), true equal post-sidebar horizontal spacing (`120px` equal symmetry), global CSS reset insulation using neutral `div` containers and `!important` surface classes (`.admin-surface-card`, `.admin-form-surface`), exact sub-pixel auth modal alignment (`box-sizing: border-box`), and sharp machined `rounded-2xl` (`16px`) geometry instead of oversized `36px` curves.
3. **Universal Performance, Haptic Physics & Motion Protocol**  
   Enforces Emil Kowalski tactile haptic physics (`transform: scale(0.97)` on `:active`), strict GPU layering (`will-change: transform, opacity`), granular `-25%` middle-zone scroll reveals (`IntersectionObserver`), stacking context isolation (`mix-blend-mode` vs `backdrop-filter` rendering fixes), direct Unicode/numeric entity escaping (`no raw &nearr;`), and localized character boundary contrast across diagonal background splits.
4. **Scenario C: Multi-Paradigm Deployment & DevOps Strategy**  
   Routes intelligently between modern edge/serverless stacks (`Next.js App Router, Cloudflare Workers/Pages, Vercel` with mandatory pre-flight `npm run build` verification and immutable chunk hashing) and traditional hosting stacks (`cPanel, PHP, Apache` with explicit query-string cache busting `styles.css?v=2.4` and absolute `.cpanel.yml` paths).
5. **Scenario D: Situational Bilingual Zero-Reload Strategy**  
   Provides high-speed `data-lang` DOM toggling with synchronous `localStorage` persistence when multi-language support is explicitly required.

---

## **Quick Access** ⚡
Everything needed by developers and AI coding assistants is fully documented inside the primary skill instructions:
👉 **[Full Scenario-Aware Standards (SKILL.md)](SKILL.md)**

---

## **How to Use** 🛠️

### 1. **As an AI Agent Skill (Recommended)**
Install these standards directly into your AI assistant workspace (`Antigravity, Cursor, Claude Code, Windsurf`) using the Agent Skills CLI:
```bash
npx skills add https://github.com/Sifat-SS/frontend-layout-standard-ai-skills.git
```
Once installed, the AI will automatically evaluate target files against our **Conditional Execution Engine** (`Scenario A vs Scenario B vs Scenario C`) before writing any code.

### 2. **Explicit Scenario Prompting**
You can proactively steer your AI coding assistant by specifying the target scenario:
> *"Refactor our admin dashboard layout (`app/admin/page.tsx`) using our `premium-frontend-standards` **Scenario B (Cockpit)** protocol."*  
> *"Build the new marketing landing page following our `premium-frontend-standards` **Scenario A (Marketing)** guidelines."*

### 3. **Manual Development & QA Checklist**
Clone this repository and use **[SKILL.md](SKILL.md)** as a thorough quality control reference during your engineering reviews, pull requests, and deployment pre-flight checks.

---
**Author**: Sifat  
**Repository**: `https://github.com/Sifat-SS/frontend-layout-standard-ai-skills.git`  
**License**: MIT / Universal
