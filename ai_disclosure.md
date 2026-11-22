---
disclosure-default: ai-generated
models-used:
  - gemini-3-flash
providers:
  - Google
scope: |
  The single-file web application (index.html / show_stopwatch_web.html)—including HTML structure, Tailwind CSS styling, state machine timer logic, UK theatre pre-show/interval call tracking, and show report export—was AI-generated through iterative human prompting, feature specification, and review.
last-updated: 2026-11-22
---

# AI Disclosure

This repository follows the [ai-disclosure convention](https://github.com/ggfevans/ai-disclosure) (v0.1), combining the W3C AI Content Disclosure vocabulary with SPDX-style metadata.

## Summary of Provenance

* **Disclosure Level:** `ai-generated` *(AI-generated with human prompting and review)*
* **Model & Provider:** `gemini-3-flash` (Google)
* **Human Role:** Feature specification, domain workflow direction (UK theatre stage management calls, interval timing, and show report formatting), iterative testing, and review.
* **AI Role:** Generation of the single-file HTML/CSS/JavaScript application, offline `localStorage` persistence, drift-free delta timing engine, and print/export templates.

## Optional File-Level Header

If you would like to include a machine-readable SPDX-style comment at the very top of `index.html` (`show_stopwatch_web.html`), you can add:

```html
<!--
SPDX-AI-Disclosure: ai-generated
SPDX-AI-Model: gemini-3-flash
SPDX-AI-Provider: Google
SPDX-AI-Scope: Full single-file web app generated via iterative human prompting and review.
SPDX-AI-Date: 2026-11-22
-->
```