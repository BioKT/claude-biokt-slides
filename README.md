# Claude Code for Biomolecular Simulation & Computational Chemistry

Beamer slides for a seminar on Claude Code, covering general concepts and the BioKT lab configuration.

## Contents

- `claude-biokt-slides.tex` — LaTeX source
- `claude-biokt-slides.pdf` — compiled slides

## Structure

**Prelude** — Live demo: `/dft-homo-lumo` on guanidinium

**Part I: General Concepts**
- What Claude Code is (and is not)
- Installation, interfaces, and operating modes
- `CLAUDE.md`, skills, memory, session management
- Cost, privacy, and honest caveats

**Part II: The BioKT Lab Configuration**
- Scientific standards and compute infrastructure
- Skills library: QM, MD, and enhanced sampling workflows
- Daily workflow in practice

**Closing** — Takeaways and a caution on outsourcing scientific judgment

## Building

```bash
pdflatex claude-biokt-slides.tex
pdflatex claude-biokt-slides.tex  # run twice for cross-references
```

Requires a standard TeX Live installation with the Metropolis beamer theme and Fira Sans fonts.

## Author

David De Sancho  
University of the Basque Country (UPV/EHU) & DIPC
