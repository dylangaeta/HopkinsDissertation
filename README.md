# JHU PhD Dissertation Template

LaTeX template meeting Johns Hopkins University PhD dissertation formatting requirements.

## Usage

1. Replace placeholders in:
   - `frontmatter/cover.tex`: Title, author, date
   - `frontmatter/abstract.tex`: Your abstract (≤350 words)
   - `chapter*/chapter*.tex`: Your content

2. Compile:
   ```bash
   pdflatex main.tex
   bibtex main
   pdflatex main.tex
   pdflatex main.tex
   ```

## Structure

```
├── main.tex
├── preamble.sty
├── frontmatter/
│   ├── cover.tex
│   ├── abstract.tex
│   ├── acknowledgments.tex
│   ├── committee.tex
│   ├── toc.tex
├── introduction/, chapter1/, chapter2/, chapter3/, conclusion/
├── appendix/
│   ├── appendix1/
│   └── appendix2/
└── backmatter/
    ├── dissertation.bib
    └── cv.pdf
```

## Features

- JHU-compliant formatting (sans serif, margins, spacing, page numbers)
- PDF/A support
- Mathematical notation
- Figure/table formatting with examples throughout
- Bibliography management
- Complete dissertation structure with Introduction, Chapters, and Conclusion.

Based on: https://www.library.jhu.edu/library-services/electronic-theses-dissertations/formatting-requirements/
