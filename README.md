# DEI-Kriteriologie

> **Transparency notice:** This project was conceptualized and built with the assistance of [Claude Opus 4](https://www.anthropic.com/claude) (Anthropic), including agentic development workflows via **Claude Code**. AI was used throughout — from domain knowledge acquisition and requirements analysis to prototype scaffolding and documentation. This README itself was drafted with AI assistance.

---

## Overview

**DEI-Kriteriologie** is a high-fidelity prototype for the systematic evaluation of external Diversity, Equity & Inclusion (DEI) training courses. It was developed as part of an internship project at **DATEV eG** and serves a dual purpose:

1. **Practical experimentation** with Claude Code as an agentic development environment
2. **A functional evaluation tool** for standardizing internal DEI course assessments

The tool enables colleagues at DATEV eG to assess external DEI course offerings against internally defined quality standards — bringing structure, reproducibility, and transparency to a previously informal process.

---

## Background & Motivation

Organizations increasingly procure external DEI training to foster inclusive workplace cultures. However, the quality of such offerings varies significantly. This project addresses the lack of a standardized, criteria-based evaluation framework by:

- Eliciting internal stakeholder requirements as a baseline for assessment
- Systematically mapping the DEI domain, including sub-areas such as disability inclusion and digital accessibility
- Translating qualitative quality expectations into a structured, software-assisted evaluation workflow

---

## Project Scope (Internship at DATEV eG)

This prototype was developed within the following workstreams:

### 1. Criteria Development (Kurskriteriologie)
Design of a systematic evaluation model for DEI course content from external providers, grounded in DATEV's internal quality standards. This included stakeholder interviews to surface implicit requirements and translate them into explicit, weighted criteria.

### 2. Requirements Analysis & Market Research
Internal stakeholder requirements were gathered through structured elicitation to establish the evaluation foundation. Parallel market research contextualized the criteria against common course formats and provider landscape.

### 3. Domain Knowledge Acquisition
Systematic coverage of defined DEI sub-domains (e.g. unconscious bias, accessibility, intersectionality, inclusive leadership). Subject-matter expertise from the **Digital Accessibility (Digitale Barrierefreiheit)** department was integrated to ensure quality and domain accuracy.

### 4. Model Visualization
The evaluation model was visually prepared in **Conceptboard** for stakeholder alignment and iterative refinement — enabling collaborative review across departments before implementation.

### 5. Software Prototype — Course Evaluation Tool
An independent end-to-end development of a **High-Fidelity Prototype** (HTML, CSS, JavaScript) for a digital DEI course evaluation tool. The prototype supports:
- Structured, criteria-based scoring of external course offerings
- Standardized internal review by non-technical colleagues
- Reproducible documentation of evaluation outcomes

---

## Technical Architecture

### Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **No backend / serverless:** Prototype runs entirely in the browser

### AI-Assisted Development Techniques

| Technique | Application in this Project |
|---|---|
| **RAG (Retrieval-Augmented Generation)** | Domain knowledge about DEI sub-areas was retrieved and grounded in internal documentation and stakeholder input before being embedded into evaluation logic |
| **Multimodal Input** | Conceptboard diagrams and visual model drafts were used as context for further AI-assisted iteration |
| **Agentic Coding (Claude Code)** | End-to-end scaffolding, iterative refinement, and testing of the prototype via CLI-based agentic workflows |
| **Prompt Engineering** | Structured prompts were used to elicit domain expertise, generate criteria taxonomies, and validate evaluation rubrics |

---

## Features

- Criteria-based scoring interface for DEI course evaluation
- Weighted assessment across multiple quality dimensions
- Summary view with aggregated scores and qualitative remarks
- Designed for use by non-technical internal reviewers
- Accessible UI informed by Digital Accessibility standards

---

## Limitations & Scope

This is an **experimental prototype** built within the scope of an internship. It is not a production-grade application. Known limitations:

- No persistent data storage (session-only)
- No authentication or multi-user support
- Criteria weights are currently hardcoded; configurability is a potential next step
- Evaluation criteria reflect DATEV-internal standards and may require adaptation for other organizational contexts

---

## Reflections on AI-Assisted Development

This project was an explicit experiment in working *with* AI as a development partner. Key learnings:

- **Claude Code** significantly accelerated prototype development, especially for boilerplate-heavy frontend scaffolding
- **RAG-style workflows** (feeding internal documents and stakeholder notes as context) improved the relevance and grounding of generated content
- **Multimodal context** (feeding Conceptboard visuals into the model) helped bridge the gap between design artifacts and implementation
- AI assistance is most effective when paired with clear domain expertise and human review — particularly in a sensitive area like DEI

---

## License

This project is released under the **BSD 2-Clause License** and is intended for use by any organization with a DEI team or function. While the evaluation criteria and quality standards reflected in this prototype are grounded in **DATEV eG's internal values**, the tool itself is designed to be adaptable to other organizational contexts with comparable DEI commitments.

See [LICENSE](./LICENSE) for the full license text.
