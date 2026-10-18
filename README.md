# Topology

> Point-set topology lecture notes and 22 weeks of fully worked homework, following C. McMullen's *Topology* (Harvard Math 131), written in Chinese Markdown with inline LaTeX.

## Sources

The notes follow two published sources, and every entry cites where it comes from:

- **C. McMullen, *Topology*, Harvard Math 131, Fall 2013** — the main text (90 pp., included in `textbooks/topology.pdf`). Section numbering follows McMullen directly, which is why the notes start at §2 and currently skip §8–§10.
- **Introduction to Topology: Exercises (Beijing Institute of Technology, Yichao Huang, 2024)** — a 47-page exercise collection (`textbooks/Topology2024_Anon.pdf`) supplying the homework problems.

Entries end with a citation such as `（教材 §3）` (textbook) or `（题集 §3.3）` (exercise set).

## Repository structure

```
topology/
├── cn/
│   ├── notes.md              # Chinese lecture notes (single file)
│   └── homework/
│       └── week1.md … week22.md
├── en/                       # English version — not started yet (empty)
└── textbooks/
    ├── topology.pdf                  # McMullen, Harvard Math 131 (90 pp.)
    ├── Topology2024_Anon.pdf         # BIT exercise collection (47 pp.)
    ├── Topology2024_Exam.pdf / ExamB / ExamC
    └── Topology2025A_Exam.pdf / 2025B_Exam.pdf
```

## The notes

`notes.md` is a single file organized into seven parts (299 lines, **133 entries** — the highest definition density of the note repositories, mostly short definitions):

- §2 Foundations of set theory
- §3 Topological spaces and continuous functions
- §4 Connectedness
- §5 Compactness
- §6 Metric spaces, completeness, and the Baire category theorem
- §7 Normal spaces and compactifications
- §11 Quotient spaces and topological constructions

Sections §8–§10 (algebraic topology, covering spaces) have not been written yet.

## The homework

Each `homework/weekN.md` follows the series-wide format:

1. **Toolbox** — a blockquote restating the definitions/theorems needed;
2. **Problems** — the assigned exercises;
3. **Solutions** — complete worked proofs ending with `$\blacksquare$`.

## Past exams

`textbooks/` also includes five Chinese past exam papers (2024 A/B/C and 2025 A/B), useful for self-assessment.

## Language status

- `cn/` — complete, authoritative.
- `en/` — the directory exists but contains nothing yet; the English translation has not started.

## The `textbooks/` folder

All PDFs are **external reference material** (textbook, exercise sets, exams). None are compiled from the notes, and there is no build system — the notes are plain Markdown meant to be read directly.

## Related repositories

Other course-notes repositories in the same series: [abstract-algebra](https://github.com/wenje-ma/abstract-algebra), [advenced-algebra](https://github.com/wenje-ma/advenced-algebra), [real-analysis](https://github.com/wenje-ma/real-analysis), and the full list on the [profile page](https://github.com/wenje-ma).
