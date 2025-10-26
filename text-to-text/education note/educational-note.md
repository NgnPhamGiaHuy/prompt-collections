# 📚 PROMPT: COMPREHENSIVE EDUCATIONAL NOTE GENERATION — V1.0

---

## 🌟 Objective

Generate a **complete, self-contained educational note** optimized for clarity, mastery, and deep understanding.

Your task is to read all variables defined in the `section, apply them to the framework in the`, and produce the full structured output.

If the topic list is extensive, split the response into **sequential generations (Part 1, Part 2, etc.)** until all topics and subtopics are fully covered.

> ⚠️ Output only the final generated note content — no summaries, explanations, or meta-commentary.

---

## ⚙️ Step 0 — Context & Input Variables

Read the following variables before generation:

```python
{{TOPIC}}:                # The main subject or domain area
{{AUDIENCE_LEVEL}}:       # e.g., “Beginner”, “Intermediate”, “Advanced”, “Non-technical professionals”, etc.
{{PRIMARY_GOAL}}:         # e.g., “Build strong conceptual understanding”, “Prepare for certification”, etc.
{{DOMAIN_OR_CONTEXT}}:    # e.g., “Computer Science”, “Economics”, “Design”, “Biology”, etc.
{{EXPRESSION_MODE}}:      # e.g., “Technical with code examples”, “Conceptual with real-world cases”, etc.
```

---

## 🧠 Step 1 — Role & Purpose

1. **ROLE:** Act as a **world-class expert and educator** in `{{DOMAIN_OR_CONTEXT}}`, skilled at transforming complex knowledge into structured, engaging, and insightful educational content.

2. **GOAL:** Generate a **comprehensive educational note** on `{{TOPIC}}`, designed for learners at the `{{AUDIENCE_LEVEL}}` level and aligned with the `{{PRIMARY_GOAL}}`.\
   Adapt depth, tone, and examples to ensure clarity, retention, and relevance within the `{{EXPRESSION_MODE}}`.

---

## 🧩 Step 2 — Coverage Strategy

If `{{TOPIC}}` contains multiple subtopics or key areas:

1. Identify and list all **subtopics** before coverage (e.g., “Subtopic 1: X”, “Subtopic 2: Y”).

2. Cover them in **batches of 2–3 subtopics per generation** using the structure in Step 3.

3. At the end of each generation, indicate coverage progress clearly:

    > ✅ Covered up to Subtopic X.\
    > Continue with next generation starting from Subtopic Y.

4. Continue iteratively until **every subtopic is covered in depth**.

5. End with a **Final Summary** confirming 100% coverage and conceptual synthesis.

---

## 🧱 Step 3 — Content Structure & Composition Framework

Each **Topic or Subtopic** must follow this structure exactly:

### ## Part 0 — Executive Summary & Conceptual Map

-   **TL;DR Summary:**\
    A 3–5 sentence explanation of what the topic is and why it matters.

-   **Mental Model Map:**\
    Provide a visual or text-based conceptual hierarchy showing relationships among subtopics or key ideas (e.g., bullet tree, Mermaid diagram, or ASCII layout).

---

### ## Part 1 — Deep Dive into Core Concepts

Each subtopic must include six structured subsections:

1. **Definition & Context**

    - Simple explanation (layman’s terms)
    - Technical or scholarly definition
    - Brief origin, motivation, or background

2. **Mechanism or Core Principle**

    - Step-by-step explanation of how or why it works
    - Optional visual (Mermaid, ASCII diagram, or structured outline)
    - Comparison with related theories or mechanisms

3. **Key Properties, Features, or Edge Cases**

    - 5–10 essential facts or properties
    - Common exceptions, boundary cases, or nuances

4. **Examples & Analogies**

    - At least one intuitive real-world analogy
    - Practical examples consistent with `{{EXPRESSION_MODE}}` (e.g., code, formula, case study, or scenario)

5. **Relevance & Use Cases**

    - 2–3 real-world applications or industry scenarios
    - Highlight professional roles or fields using this concept

6. **Best Practices & Common Mistakes**

    - Key professional or academic best practices
    - 2–3 common misconceptions and corrective guidance

---

### ## Part 2 — High-Yield Revision Aids

-   **Glossary Table** — `Term | Clear Definition | When to Use vs. Avoid`
-   **Conceptual Contrasts Table** — Comparing related techniques, concepts, or models
-   **Mnemonics & One-Liners** — Concise recall aids or summary phrases

---

### ## Part 3 — Evaluation & Reflection

-   **Common Questions & Model Answers**

    -   10–15 core technical or conceptual questions with ideal responses

-   **Misconceptions or Debate Points**

    -   3–5 common misunderstandings, clarified with expert reasoning

---

### ## Part 4 — Practical Application & Extended Learning

-   **Real-World Implementations**

    -   3–5 concrete examples from systems, frameworks, or studies

-   **Related Concepts (“See Also”)**

    -   5–10 related ideas with one-line descriptions

-   **Further Learning Resources (Optional)**

    -   Books, research papers, or courses for deeper study

---

## 🦦 Step 4 — Style & Formatting Rules

| Element          | Guideline                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------- |
| **Tone**         | Authoritative, engaging, and educational — precise yet clear                                      |
| **Format**       | Use Markdown exclusively (headings, tables, code blocks)                                          |
| **Adaptability** | Tailor explanations, examples, and tone to match `{{AUDIENCE_LEVEL}}` and `{{DOMAIN_OR_CONTEXT}}` |
| **Length**       | \~1,000–1,500 words per subtopic (short) or ≥2,500 words total for comprehensive notes            |
| **Avoid**        | Filler, redundancy, conversational chatter, or incomplete logic                                   |

---

## 🔍 Step 5 — Quality Verification & Self-Correction

After each generation:

1. Verify appropriate **depth and complexity** for `{{AUDIENCE_LEVEL}}`.

2. Confirm all required sections are complete and in sequence.

3. Ensure **accuracy and domain alignment** with `{{DOMAIN_OR_CONTEXT}}`.

4. End with a **progress summary**:

    > ✅ Covered Subtopics: [List].\
    > Continue with next generation starting from: [Remaining list].

5. Stop **only** when all subtopics are fully covered.

---

## 🧭 Step 6 — Example Continuation Logic

If `{{TOPIC}}` includes:

```
Photosynthesis
Cellular Respiration
Enzymes
ATP Production
```

Then generate in sequence:

-   **Part 1 →** Photosynthesis & Cellular Respiration
-   **Part 2 →** Enzymes & ATP Production
-   **Final →** “✅ All subtopics covered.”

---

## 📦 Final Output Requirements

-   Output must contain **only** the generated educational content.
-   The structure, formatting, and coverage must be **immediately publishable** and **academically or professionally sound**.
-   Each generation must remain **self-contained and coherent**, ensuring continuity across parts.
