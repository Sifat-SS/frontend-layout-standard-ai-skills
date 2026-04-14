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
- **Medium Screen Breakpoints**: Use specific `fr` ratios (e.g., `1.5fr 1fr 1fr`) at the 1024px/768px breakpoints to keep Footer and Feature columns side-by-side as long as readability allows.
- **Padding Discipline**: Ensure `container` classes provide a minimum `20px` gutter on mobile to prevent text from touching the screen edges.
- **Typography Reset Integrity**: AI Agents must always reset `button, input, select, textarea` to `font-family: inherit` and `color: inherit`. This prevents mismatched system fonts from breaking the brand's visual language.
- **The Dash-Density Rule**: For dashboard layouts, prioritize a "Single-View" experience. Use `flex-wrap` and dynamic scaling (ratios like `1fr minmax(0, 3fr)`) ensure the entire interface is visible at 100% browser zoom on a standard 1080p display without vertical scrolling.

---

## 3. **Performance & Animation Logic** ⚡
High quality with low overhead.
- **Semantic HTML5**: Always use strictly semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) for SEO and Accessibility.
- **Scroll Reveals**: Use the native `IntersectionObserver` API for "reveal-on-scroll" animations to avoid heavy JS scroll libraries.
- **Hardware Acceleration**: Use `transform` and `opacity` properties for transitions. Force GPU layering on critical animated elements using `will-change: transform`.
- **Tactile Feedback Protocol**: Implement high-end haptic-lite interaction standards. All primary buttons and interactive cards must utilize a hardware-accelerated `:active { transform: scale(0.98); }` state for immediate user feedback.

---

## 4. **Bilingual "Zero-Reload" Strategy** (Situational) 🌍
**Note**: Only implement this protocol if a project explicitly requires multi-language support. Do not apply for single-language builds.
- **Method**: Render the page with both languages present. Use a `data-lang` attribute on the `<html>` tag to toggle visibility via CSS (`.lang-en { display: none; }`).
- **UX**: Persist the selection using `localStorage` to ensure the preference is remembered upon return.

---

## 5. **DevOps & Deployment Automation** 🛰️
- **The Handshake**: For Git-to-cPanel workflows, use a secure PHP script to trigger a `uapi` pull and deploy sequence. Store tokens in a file safely outside the public web root.
- **Absolute Path Rule**: Within `.cpanel.yml`, always use Absolute Paths for file movement tasks, as environment variables do not persist across multiple task lines.
- **Cache-Busting**: Production assets must utilize version strings (e.g., `styles.css?v=2.4`) to bypass aggressive mobile browser caching and ensure users see updates instantly.

---

## 6. **Component Architectural Standards** 🧱
Maintain a "Zero-Style-Bloat" codebase.
- **Standardized Utilities**: Avoid inline-style repetition for recurring premium elements. Codify `.premium-card` (glassmorphism/hover-lift) and `.modal-overlay` (fixed backdrop-blur) in the global CSS to ensure interaction parity across different features.
- **Modal Logic**: Modals should always utilize a centralized `inset-0` fixed overlay with `backdrop-filter: blur(4px)` to isolate the user task from background noise.

---
**Standard Created**: April 2026  
**Status**: Universal / Project-Agnostic
