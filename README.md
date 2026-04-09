# Moqups UML Class Diagram Guide

A practical learning resource for building UML Class Diagrams using Moqups, created for BCIT CST students learning object-oriented system design.

---

## About This Guide

This guide walks you through building a UML class diagram in Moqups from start to finish. The four tasks follow the order you would actually work through the process, so you can go step by step or jump to what you need. A glossary and troubleshooting section are included at the end for quick reference.

### Tasks Overview

| # | Task | Description |
| :- | :--- | :---------- |
| 1 | Create an Account| Sign up and get started with Moqups |
| 2 | General Operations | Create, share, and export documents |
| 3 | Work with UML Class Shapes| Create, style, organize, and delete shapes |
| 4 | Connect Classes Using Lines| Add, style, modify, and delete connectors |

---

## Project Structure

```
docs/
├── index.md                             # Home page
├── create-an-account.md                 # Task 1
├── general-operations.md                # Task 2
├── work-with-class-shapes.md            # Task 3
├── connect-classes-using-lines.md       # Task 4
├── glossary.md                          # Reference: key terms
└── troubleshooting.md                   # Reference: common issues
images/
└── *.png                                # Screenshots
videos/
└── *.gif                                # Step-by-step animations
mkdocs.yml
```

---

## Getting Started

**Prerequisite:** Python 3.8 or higher

```bash
pip install mkdocs mkdocs-material
mkdocs serve
```

Open `http://localhost:8000` in your browser to preview the guide locally.

---

## How We Built This

### Software Selection
 
We first used Moqups in our OOP class at BCIT. We liked it because it was easy to use and looked modern. This guide is based on our own experience with the tool, plus the official **Moqups documentation**. We focused on the parts that were confusing when we first started.
 
### Task Distribution
 
| Member | Pages |
|---|---|
| Meiqi Zhao | Home, Work with UML Class Shapes, Connect Classes Using Lines, Troubleshooting |
| Ge Zheng | Create an Account, General Operations, Glossary |
 
### Tools & Tech
 
- **Moqups** — the tool this guide is about
- **Material for MkDocs** — used to build the documentation site
- **Markdown** — used to write all the pages
- **GitHub Pages** — used to host the site
 
### Challenges
 
The hardest part was learning Moqups and writing about it at the same time. Some things, like connecting UML classes with the right lines, took a few tries to figure out. We also had to think carefully about how to explain each step clearly for beginners.
 
---

Built with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).
