# Sifat's Frontend Web Development Standards 🚀✨
**Author**: Sifat  
**Origin**: While developing frontend projects with AI agents, I observed recurring layout and structural issues in the generated code. To address this, I created this "AI Skill"—a robust set of rules and protocols designed to guide AI agents toward producing durable, high-performance, and visually consistent frontend code.  
**Purpose**: A Universal AI Skill File for high-end web development, responsive durability, and automated DevOps.

> [!IMPORTANT]
> **Tablet Testing Disclaimer**: While these protocols have been battle-tested on multiple mobile and desktop environments, they have **not yet been validated on actual tablet hardware**. Some layout behaviors (like orientation shifts) may require refinement. If you test these standards on a tablet and find issues, your feedback and suggested updates are highly encouraged!

---

## **Why to use this?** 🏆
This repository provides a battle-tested blueprint for creating "Premium" web experiences. It eliminates decision fatigue and prevents common technical pitfalls by:
- **Ensuring Responsive Durability**: Solving layout breakage in restrictive environments like Instagram and Facebook in-app browsers.
- **Guaranteeing Visual Integrity**: Preventing asset cropping and premature column stacking on mobile.
- **Standardizing Performance**: Using native APIs and hardware-accelerated transitions for a buttery-smooth feel.
- **Automating Reliability**: Providing a foolproof DevOps strategy for Git-to-cPanel deployments.

## **How to use this?** 🛠️
1. **As an AI Context**: Copy the content of this README and paste it into the system prompt or context of your AI assistant (e.g., Antigravity, ChatGPT, Claude) to ensure it generates high-end, standards-compliant code.
2. **AI Agent Link Injection**: Copy the URL of this repository and pass it to a web-capable AI agent, instructing it to: *"Follow the frontend standards at [this URL] for all code generation in this project."*
3. **Cloning for Local Reference**: Clone this repository to keep a local "Source of Truth" for your development team:
   ```bash
   git clone https://github.com/Sifat-SS/sifat-frontend-standards.git
   ```
4. **As a Developer Checklist**: Reference the protocols during the build process to verify that your layout, bilingual logic, and deployment scripts meet "Premium" requirements.
5. **In CI/CD Configurations**: Use the deployment rules in Section 5 to configure your `.cpanel.yml` and handle cache-busting effectively.

---

## 1. **Responsive Durability Protocol** 📱
Always prioritize "Content Integrity" on mobile devices.
- **The "No-Cage" Rule**: Avoid setting fixed `height` values within media queries for primary containers. Use `height: auto` or `min-height` to allow containers to scale naturally with their content.
- **In-App Browser Fix**: In grid-based layouts on mobile, use `width: 100% !important` and `height: 100% !important` to override restrictive defaults in mobile browsers (e.g., Instagram/Facebook).
- **Asset Scaling**: 
    - Use `object-fit: cover` for interactive galleries to maintain grid symmetry.
    - Use `object-fit: contain` and `height: auto` for promotional banners with text to prevent information loss via cropping.

---

## 2. **Layout & Grid Integrity** 🗺️
Maintain the "Premium" feel by preventing premature stacking.
- **Medium Screen Breakpoints**: Maintain the "Premium" multi-column feel on tablets (1024px/768px) by adjusting grid ratios rather than premature stacking. 
    - *Example*: Use specific `fr` ratios like `1.5fr 1fr 1fr` to keep footers and feature blocks side-by-side.
- **Padding Discipline**: Ensure containers provide a standard comfortable gutter on mobile to prevent text from touching screen edges. 
    - *Recommendation*: A minimum of `20px` is the baseline for premium spacing.
- **Typography Reset Integrity**: AI Agents must always reset `button, input, select, textarea` to `font-family: inherit` and `color: inherit` to prevent system fonts from breaking the design language.
- **The Dash-Density Rule**: For dashboard layouts, prioritize a "Single-View" experience. Utilize `flex-wrap` and dynamic scaling to ensure the entire interface remains visible at 100% zoom on a standard 1080p display (avoiding vertical scroll for primary tasks).
    - *Example Logic*: Use ratios like `1fr minmax(0, 3fr)` for sidebar/content balance.

---

## 3. **Performance & Animation Logic** ⚡
High quality with low overhead.
- **Semantic HTML5**: Always use strictly semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) for SEO and Accessibility.
- **Scroll Reveals**: Use the native `IntersectionObserver` API for "reveal-on-scroll" animations to avoid heavy JS scroll libraries.
- **Hardware Acceleration**: Prioritize GPU-friendly properties (`transform`, `opacity`) for all transitions. Force GPU layering on critical animated elements (using `will-change`) to ensure smooth rendering on low-power mobile devices.
- **Tactile Feedback Protocol**: Implement high-end haptic-lite interaction logic. All primary interactive elements must utilize subtle hardware-accelerated transformations (e.g., `scale(0.98)`) for immediate active-state feedback.

---

## 4. **Bilingual "Zero-Reload" Strategy** (Situational) 🌍
**Note**: Only implement this protocol if a project explicitly requires multi-language support. Do not apply for single-language builds.
- **Method**: Render the page with both languages present. Use a `data-lang` attribute on the `<html>` tag to toggle visibility via CSS (`.lang-en { display: none; }`).
- **UX**: Persist the selection using `localStorage` to ensure the preference is remembered upon return.

---

## 5. **Automated Deployment & DevOps** 🛰️
- **The Handshake Protocol**: For Git-to-Server workflows, utilize an automated deployment sequence (e.g., a secure PHP pull script or GitHub Action). Store all sensitive tokens/secrets safely outside the public web root.
- **Environment Integrity**: When configuring deployment tasks (e.g., in `.cpanel.yml` or CI scripts), use **Absolute Paths** for all file movements to ensure persistence across environment lines.
- **Cache-Busting Strategy**: Production assets must utilize version strings to bypass aggressive browser caching.
    - *Example*: Use `styles.css?v=2.4` to ensure users see updates instantly without manual hard-reloads.

---

## 6. **Component Architectural Standards** 🧱
Maintain a "Zero-Style-Bloat" codebase through pattern standardization.
- **Global Utility Logic**: Identify and codify recurring premium design patterns into **Global Utility Classes** (e.g., glassmorphism, depth/shadows, modal backdrops). This ensures interaction parity and reduces technical debt.
    - *Standard Classes*: Use descriptive names like `.premium-card` (for depth/lift) and `.modal-overlay` (for backdrops).
- **Depth & Dimension Protocol**: Interactive overlays and modals should utilize centralized fixed positioning and background isolation (e.g., `backdrop-filter: blur(4px)`) to keep task focus sharp.

---
**Standard Created**: April 2026  
**Status**: Universal / Project-Agnostic
