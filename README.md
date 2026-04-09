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

The content is based on firsthand experience using Moqups during BCIT coursework, supplemented by the official [Moqups documentation](https://moqups.com/). We structured the tasks around the steps that were most confusing when we first learned the tool.

### Contributors

| Member | Pages |
| :----- | :---- |
| Meiqi Zhao | Home, Work with UML Class Shapes, Connect Classes Using Lines, Troubleshooting |
| Ge Zheng | Create an Account, General Operations, Glossary |

---
 
Built with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).
