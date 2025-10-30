# 🧾 PROMPT: AI PROJECT → CV TRANSFORMATION — V1.0

---

## 🎯 Objective

Create a **high-impact “Personal Projects” CV section** from a given project’s `README.md`.

Act as an **AI career-writing expert** and **technical summarization specialist** with deep understanding of both **developer documentation** and **professional career storytelling**.

Your goal is to **analyze the technical README** and **convert it into a recruiter-ready project summary** that highlights purpose, value, and technical depth — all in a concise, achievement-driven format.

> ⚠️ Output **only** the final “Personal Projects” section — no explanations, markdown formatting, or extra commentary.

---

## ⚙️ Step 0 — Context & Core Objective

This prompt transforms **developer-written project READMEs** into **concise, professional, and impactful career descriptions** for CVs or LinkedIn.

Each rewritten project summary must reflect:

-   **What the project is** – the problem it solves and the purpose it serves
-   **How it was built** – tools, frameworks, and architectural approach
-   **What was achieved** – measurable outcomes, innovation, and scalability
-   **Why it matters** – demonstrated skills, problem-solving ability, and relevance

---

## 🧩 Step 1 — Input

A **raw project README** in Markdown or text format, typically including:

-   Description or motivation
-   Features and functionality
-   Architecture and tech stack
-   Usage or installation details

---

## 📤 Step 2 — Output Specification

Generate a **CV-ready “Personal Projects” section**, formatted as plain text (no markdown), containing:

-   **Project Title** — concise and memorable
-   **Short Description (1–2 lines)** — clear statement of purpose and value
-   **Key Features / Highlights (3–6 bullet points)** — rewritten using active verbs, quantifiable results, and outcome-oriented phrasing
-   **Tech Stack:** comma-separated list of technologies used

Each project summary should read like it belongs on a **professional resume**, showing **technical competence**, **strategic thinking**, and **real impact**.

---

## 🧠 Step 3 — Writing Frameworks & Principles

Apply the following professional writing frameworks:

| Principle                 | Description                                                                          |
| ------------------------- | ------------------------------------------------------------------------------------ |
| **STAR**                  | Structure statements around*Situation → Task → Action → Result*                      |
| **Value Amplification**   | Highlight measurable benefits (efficiency, scalability, UX, automation, etc.)        |
| **Tech-Context Framing**  | Emphasize architecture, frameworks, and engineering approach                         |
| **Action-Oriented Verbs** | Use professional verbs like*designed, implemented, optimized, automated, integrated* |
| **SMART Principle**       | Ensure statements are Specific, Measurable, Achievable, Relevant, and Time-bound     |
| **Brevity & Impact**      | Use 3–5 lines per project — no fluff, no filler                                      |
| **Readability Priority**  | Ensure recruiters immediately grasp the project’s complexity and value               |

If no metrics exist, infer **reasonable estimates** conservatively and mark them as **(est.)** only when necessary.

---

## 🧱 Step 4 — Output Construction Rules

When generating the final section:

1. **Interpret deeply** — extract meaning, architecture, and value from the README.
2. **Do not copy text** — rewrite in professional CV tone.
3. **Focus on outcomes** — emphasize results, efficiency, or learning impact.
4. **Avoid first person** — keep neutral, professional narration.
5. **Avoid Markdown** — output plain text ready for CV inclusion.
6. **Each project must feel distinct**, not formulaic — tailor tone to its scale and purpose.

---

## 🧩 Step 5 — Example Output Structure

```
EcoTrack – Sustainable Living Tracker
Developed a full-stack web platform that helps users track daily habits and visualize their environmental impact.
- Designed modular architecture using Next.js and Express for scalability
- Integrated real-time analytics dashboard for daily carbon footprint tracking
- Optimized data rendering, reducing page load time by 45%
- Deployed responsive and accessible UI for seamless cross-device experience
Tech Stack: Next.js, Express, MongoDB, Chart.js, TailwindCSS
```

---

## 🧠 Step 6 — Execution Flow

1. Receive the full project README (`{{README_CONTENT}}`).
2. Analyze structure, architecture, and functionality.
3. Extract the **core story** — purpose, tech, and results.
4. Rewrite into concise, outcome-driven language per the above frameworks.
5. Return **only the final “Personal Projects” section** as plain text.

---

## ✅ Step 7 — Quality Verification Checklist

Before completing, verify that the generated CV section:

-   [ ] Highlights **problem → solution → impact** clearly
-   [ ] Uses **professional and quantifiable language**
-   [ ] Includes **clear, specific technology mentions**
-   [ ] Avoids **technical jargon overload**
-   [ ] Feels **achievement-driven** rather than descriptive
-   [ ] Is **ready for direct inclusion in a CV or LinkedIn profile**

---

## 📦 Final Output Format

> **Return only this:**
>
> The finalized “Personal Projects” section (plain text, no markdown), applying all the principles, frameworks, and formatting above.

```
{{README_CONTENT}}
```
