# 🧾 PROMPT: PRODUCTION-GRADE README GENERATION — V1.0

---

## 🎯 Objective

Create a file named **`README.md`** in the root folder of this project.

Write the full content of the **`README.md`** using the following guidelines.

Act as a **professional software documentarian** and **senior developer**.

Your task is to create a complete, production-ready, visually styled, and storytelling-driven `README.md` for the current software project — one that conveys technical details clearly while maintaining an engaging, cohesive, and professional tone.

> ⚠️ Output only the final README.md file contents — no summaries, suggestions, commentary, or extra text.
> The README.md must be fully copy-pasteable and ready to publish.

---

## ⚙️ Step 0 — Context & Hard Constraints

-   Perform a **full project-wide analysis** before writing: inspect every source file, configuration, workflow, Dockerfile, documentation, and dependency manifest.
-   Do **not** generate or assume any information not verifiably found in the codebase.
-   Maintain a **professional, narrative-driven tone** focused on purpose, value, and impact.
-   Output must use **Markdown syntax** exclusively.
-   The README must explicitly highlight **problems solved** and **time saved** in the Description, Features, and Usage sections.
-   The **Installation section** must include **only real installation methods** found in the repository — no assumptions or fabrications.

---

## 🔍 Step 1 — Deep Codebase Analysis (Mandatory)

Before generating the README, extract and understand:

1. **Project Type** – CLI, web app, SDK, library, or data pipeline
2. **Tech Stack & Frameworks** – languages, frameworks, and runtime environments
3. **Key Features & Modules** – all core components, services, or endpoints
4. **Architecture & Execution Flow** – how the system starts, runs, and connects its parts
5. **Folder Structure & Assets** – actual directory hierarchy with short annotations
6. **Dependencies & Environment Variables** – required packages, OS/runtime details, and configs
7. **Automation Tools & Scripts** – CI/CD, Dockerfiles, Makefiles, setup scripts, and utilities

✅ **Do not proceed** until full technical and architectural context is extracted.

---

## 🧱 Step 2 — README.md Generation Framework (Storytelling)

### Markdown Styling Rules

| Element     | Usage                  | Style             | Alignment |
| ----------- | ---------------------- | ----------------- | --------- |
| `#`         | Project Title          | H1 (~32px)        | Left      |
| `##`        | Section Headers        | H2 (~24px)        | Left      |
| `###`       | Subsection Titles      | H3 (~18px)        | Left      |
| Paragraphs  | Descriptive text       | ~14–16px          | Left      |
| Code Blocks | CLI/config/sample code | Monospace (~14px) | Left      |
| Lists       | Features, steps        | Bulleted `-`      | Left      |

**Formatting Notes:**

-   Include **one blank line** between sections and code blocks
-   Use **fenced code blocks** with syntax highlighting (`bash`, `json`, etc.)
-   **Wrap lines** at 100–120 characters
-   Incorporate **badges, emojis, and visual cues** for readability

---

## 🧭 Step 3 — Required README Sections

### 1. 🏷️ Project Title

-   H1, sentence case, concise, and descriptive
-   Example: # EcoTrack – Sustainable Living Tracker

### 2. 🏅 Badges (Optional)

-   Place directly below the title (e.g., build, coverage, version)

### 3. 📝 Description

-   2–3 paragraphs telling the **story of the project**:
-   Why it exists (the problem it solves)
-   Who benefits from it (target users)
-   How it delivers value
-   Maintain a professional, narrative-driven tone — no first-person language

### 4. ✨ Features

-   Use a **bullet list** starting with strong action verbs
-   For each feature, describe the **problem it solves** or **time it saves**
-   Add short context or narrative when appropriate to show real-world impact

### 5. 🖼️ Demo / Screenshots (Optional)

-   Embed **images, GIFs, or live demo links**
-   Include short captions to describe the visual flow or impact

### 6. ⚙️ Installation

-   Only describe **verified** installation methods, tools, or scripts found in the codebase.
-   Include:
-   Prerequisites (languages, versions, tools)
-   Verified setup commands (`npm install`, `pip install`, `docker-compose up`, etc.)
-   Existing helper scripts (`make setup`, `setup.sh`)
-   Verified environment setup steps (`.env`, migrations)
-   Real troubleshooting notes if available
-   Provide fenced code blocks for each command sequence
-   If multiple installation methods exist, document each exactly as implemented

### 7. 🚀 Usage

-   Explain usage in a **natural, narrative flow** — how users run, interact, and view results
-   Include sample **commands**, **screenshots**, or **CLI examples**

### 8. 🔧 Configuration (If Applicable)

-   Clearly describe environment variables and configuration files
-   Provide examples in fenced code blocks

### 9. 🗂️ Folder Structure

-   Present a **Markdown tree** of the actual directory structure
-   Optionally include brief comments describing key folders

### 10. 🤝 Contributing

-   Describe the **GitHub workflow** as a story — how new contributors can fork, branch, commit, and push changes
-   Reference `CONTRIBUTING.md` if available

### 11. 📄 License

-   Declare the project license and provide a link to the license file

### 12. 👤 Author

| Name              | GitHub                                             | LinkedIn                                                             |
| ----------------- | -------------------------------------------------- | -------------------------------------------------------------------- |
| **NgnPhamGiaHuy** | [@NgnPhamGiaHuy](https://github.com/NgnPhamGiaHuy) | [Nguyen Pham Gia Huy](https://www.linkedin.com/in/nguyenphamgiahuy/) |

### 13. 🙏 Acknowledgements (Optional)

-   Credit inspirations, open-source libraries, or collaborators

---

## 🧠 Step 4 — Execution Rules

1. Analyze **all project files** to establish real context.
2. Identify each feature or workflow that **solves a problem** or **saves time**.
3. Craft the README as a **storytelling document** emphasizing purpose and value.
4. Include **only real installation commands and files** found in the repo.
5. Output must be **only the final `README.md`** — formatted, clean, and production-ready.

---

## ✅ Step 5 — Quality & Verification

-   Each command must correspond to a real file or path in the repository.
-   Avoid fabricated or placeholder scripts.
-   When describing time savings, use verifiable or conservative phrasing.
-   Include **three concrete examples** showing "before" (manual) vs "after" (automated) workflows.
-   If tests exist, add a **Testing** subsection describing:
-   How to run unit/integration tests
-   How to interpret test results

---

## 📦 Final Output Requirements

-   Output must contain **only** the final, production-ready `README.md` content.
-   No additional explanations, commentary, or metadata.
-   The resulting file should be **immediately publishable** and **compliant with professional documentation standards**.
