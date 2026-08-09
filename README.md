# Module 3 Journal LaTeX Package

## Assignment

**Essential question:** What does meaningful communication look like for
students with complex needs?

**Blackboard destination:** Open the EDE448 course outline and select
Module 3 > Journal #3.

**Repository:** [pzg8794/EDE448-Module3-Journal](https://github.com/pzg8794/EDE448-Module3-Journal)

**Publication state:** Authorized GitHub/Overleaf working repository. The
paper remains under Piter's review and has not been submitted to Blackboard.

**Documented due date:** August 10, 2026, 11:59 PM EDT

## Review Status

This is an almost-ready review draft. It has not been submitted through this
workflow.

## Package Contents

- `main.tex` - Module 1/Module 2-themed journal entry point
- `sections/` - four journal sections
- `references.bib` - course, prior-work, TD Snap, EDU486, and placement sources
- `module3-journal-draft.md` - complete Markdown review draft and source trail

The paper connects Module 3 READ/MEDIA work, the posted TD Snap review and peer
reply work, the Communication Support Plan, EDE448 Modules 1--2, K--5 teaching
placement evidence, and EDU486 camp evidence through the Puzzle Plan and
EQUITAS lenses.

## Verification

- Compiled locally with TeX Live and BibTeX on August 9, 2026
- Five pages total in the local review copy
- No unresolved citations or references in the latest local build
- Build byproducts are ignored so Overleaf receives a clean source package

## Build

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

## Evidence Boundary

The paper uses de-identified public course records and composite learner
planning. It does not publish raw recordings, private disclosures, child media,
or claims about diagnosis or internal states that the available evidence cannot
support.
