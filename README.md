# Etymology + Data Science

*A Computational Survey of Word Origins*

A 12-chapter Quarto ebook covering the full stack of computational historical linguistics: from the 19th-century comparative method to modern transformer-based proto-language reconstruction.

---

## Read Online

**[https://altustd.github.io/etymology-data-science/](https://altustd.github.io/etymology-data-science/)**

---

## Contents

**Preface**

**Part I: Foundations**
- Chapter 1 — What Is Etymology? A Data Perspective
- Chapter 2 — The Comparative Method
- Chapter 3 — Representing Language as Data

**Part II: Core Algorithms**
- Chapter 4 — Sequence Alignment & Phonetic Distance
- Chapter 5 — Cognate Detection
- Chapter 6 — Phylogenetic Inference: Language Family Trees

**Part III: Advanced Techniques**
- Chapter 7 — Proto-Language Reconstruction
- Chapter 8 — Semantic Drift & Word Meaning Change
- Chapter 9 — Borrowing Detection & Language Contact
- Chapter 10 — LLMs & Modern Etymology
- Chapter 11 — Etymology as Knowledge Graphs

**Part IV: Synthesis**
- Chapter 12 — Capstone Project

**Appendices**
- A: Linguistic Glossary
- B: Tools & Resources

---

## Run Locally

```bash
pixi install
pixi run render-all    # HTML + PDF → docs/
pixi run preview       # live preview
```

## Tech Stack

Quarto · pixi · Python 3.12 · pandas · NumPy · scikit-learn · LingPy · Gensim · NetworkX · SciPy · Transformers
