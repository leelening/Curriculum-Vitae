# Curriculum-Vitae

[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)](https://www.latex-project.org/)
[![PDF](https://img.shields.io/badge/PDF-Available-red)](https://github.com/leelening/Curriculum-Vitae/blob/main/CV_English.pdf)

Professional CV/Resume repository for Lening Li (郦乐宁).

## Overview

This repository contains the LaTeX source files for my professional curriculum vitae and resume, available in both English and Chinese.

## 📄 Documents

| Document | File | Description |
|----------|------|-------------|
| **English CV** | [`CV_English.pdf`](./CV_English.pdf) | Full academic and professional CV |
| **Chinese CV** | [`cv_Chinese.pdf`](./cv_Chinese.pdf) | 中文履历 |
| **Resume** | [`Resume.pdf`](./Resume.pdf) | Condensed one-page resume |

## Tech Stack

- **Typesetting**: LaTeX
- **Document Class**: Custom `resume.cls`
- **Bibliography**: BibTeX
- **Build Tool**: pdfLaTeX/XeLaTeX

## Features

- ✅ Professional academic CV format
- ✅ Multiple language support (English/Chinese)
- ✅ BibTeX integration for publications
- ✅ Clean, modern typography
- ✅ Easy to customize and extend

## Building from Source

### Prerequisites

- LaTeX distribution (TeX Live or MiKTeX)
- `resume.cls` class file (included)

### Build Instructions

```bash
# Clone the repository
git clone https://github.com/leelening/Curriculum-Vitae.git
cd Curriculum-Vitae

# Build English CV
pdflatex CV_English.tex
bibtex CV_English
pdflatex CV_English.tex
pdflatex CV_English.tex

# Build Chinese CV
xelatex cv_Chinese.tex

# Build Resume
pdflatex Resume.tex
```

## Project Structure

```
.
├── CV_English.tex       # English CV source
├── CV_English.pdf       # English CV output
├── cv_Chinese.tex       # Chinese CV source
├── cv_Chinese.pdf       # Chinese CV output
├── Resume.tex           # Resume source
├── Resume.pdf           # Resume output
├── resume.cls           # Custom LaTeX class
└── refs.bib             # Bibliography references
```

## Sections Included

- **Contact Information**: Email, phone, location
- **Research Interests**: Reinforcement Learning, Optimal Control, Game Theory, Formal Methods
- **Education**: Carnegie Mellon University (MBA), WPI (Ph.D., M.S.)
- **Professional Experience**: Symbotic, Berkshire Grey, Harvard University
- **Publications**: Journal papers, conference papers, arXiv preprints
- **Teaching Experience**: Graduate courses at WPI
- **Honors & Awards**: Academic achievements
- **Skills**: Programming languages, tools, frameworks

## About the Author

**Lening Li**
- Robotic Lab Advisor at Harvard University
- Senior Software Engineer at Symbotic
- Ph.D. in Robotics Engineering (WPI)
- MBA Candidate at Carnegie Mellon University

## License

Feel free to use the LaTeX template for your own CV, but please customize the content for your own use.

## Contact

- Email: leningli@outlook.com
- GitHub: [@leelening](https://github.com/leelening)
- Website: [leelening.github.io](https://leelening.github.io)
