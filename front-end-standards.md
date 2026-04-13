# Sifat's Frontend Web Development Standards 🚀✨
**Author**: Sifat  
**Origin**: While developing frontend projects with AI agents, I observed recurring layout and structural issues in the generated code. To address this, I created this "AI Skill"—a robust set of rules and protocols designed to guide AI agents toward producing durable, high-performance, and visually consistent frontend code.  
**Purpose**: A Universal AI Skill File for high-end web development, responsive durability, and automated DevOps.

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

---

## 3. **Performance & Animation Logic** ⚡
High quality with low overhead.
- **Semantic HTML5**: Always use strictly semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) for SEO and Accessibility.
- **Scroll Reveals**: Use the native `IntersectionObserver` API for "reveal-on-scroll" animations to avoid heavy JS scroll libraries.
- **Hardware Acceleration**: Use `transform` and `opacity` properties for transitions to ensure smooth rendering on low-power mobile devices.

---

## 4. **Bilingual "Zero-Reload" Strategy** 🇲🇽🇺🇸
- **Method**: Render the page with both languages present. Use a `data-lang` attribute on the `<html>` tag to toggle visibility via CSS (`.lang-en { display: none; }`).
- **UX**: Persist the selection using `localStorage` to ensure the preference is remembered upon return.

---

## 5. **DevOps & Deployment Automation** 🛰️
- **The Handshake**: For Git-to-cPanel workflows, use a secure PHP script to trigger a `uapi` pull and deploy sequence. Store tokens in a file safely outside the public web root.
- **Absolute Path Rule**: Within `.cpanel.yml`, always use Absolute Paths for file movement tasks, as environment variables do not persist across multiple task lines.
- **Cache-Busting**: Production assets must utilize version strings (e.g., `styles.css?v=2.4`) to bypass aggressive mobile browser caching and ensure users see updates instantly.

---
**Standard Created**: April 2026  
**Status**: Universal / Project-Agnostic
