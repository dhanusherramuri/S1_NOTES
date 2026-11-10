# AGENTS.md

This repo contains semester notes across 5 subjects: AML, DSA, RTOS, ALA, CAWJ.

## Renaming convention (CRITICAL)

Many files already have a number prefix, but **not all**. To follow the user's order requirement, add a number + underscore prefix to any file that lacks one. Already-numbered files should not be renumbered.

**Subjects with inconsistent numbering:**

- `RTOS/PDFS/`: `Scheduling.ppt` and `Silberschatz 9th edition.pdf` lack number prefixes. All other PDFs use `NN_Title.pdf` format.
- `RTOS/LAB/`: `03_p_three-thread-blink-hse.html` and `03_stm32f103-buildsystem.html` have prefixes; `21_Lab_priority-inversion.html` has one. Any lab HTML without a prefix should get one.
- `AML/`: Lecture files vary; add numbers if needed for ordering.
- `CAWJ/`: Lecture PDFs use dates in filenames (e.g., `L1Introduction to OO.pdf`); these follow the existing convention and need no changes.
- `DSA/`: No number prefix convention; add numbers if ordering is desired.

**Rule**: `number_Title.ext` — the number indicates the intended processing order. Do not renumber files already following this pattern.

## Directory structure

- `AML/` — Advanced Machine Learning presentations and labs
- `DSA/` — Data Structures and Algorithms slides
- `RTOS/` — Real-Time Operating Systems lecture materials, labs, and PDFs
- `ALA/` — Advanced Linear Algebra and related PDFs
- `CAWJ/` — Computer Architecture and Java lectures