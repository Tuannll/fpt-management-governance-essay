<div align="center">

# FPT Management & Corporate Governance Essay

**Academic research essay on Management, Corporate Governance, and the Impact of Artificial Intelligence at FPT Corporation.**

[![LaTeX](https://img.shields.io/badge/LaTeX-2e-008080?logo=latex&logoColor=white)](https://www.latex-project.org/)
[![Build PDF](https://github.com/Tuannll/fpt-management-governance-essay/actions/workflows/build-pdf.yml/badge.svg)](https://github.com/Tuannll/fpt-management-governance-essay/actions/workflows/build-pdf.yml)
[![View PDF](https://img.shields.io/badge/PDF-View_Online-red.svg)](https://github.com/Tuannll/fpt-management-governance-essay/blob/pdf/main.pdf)
[![Status](https://img.shields.io/badge/Status-In_Progress-orange.svg)]()
[![Team](https://img.shields.io/badge/Team-2_Members-blue.svg)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**English** | [Tiếng Việt](README.vi.md)

**[📄 View PDF Online](https://github.com/Tuannll/fpt-management-governance-essay/blob/pdf/main.pdf) • [🚀 Quick Start](#quick-start) • [✨ Essay Structure](#essay-structure) • [❓ FAQ](#faq)**

</div>

---

<a id="essay-structure"></a>
## ✨ Essay Structure

The essay follows standard university requirements for the "Management Science & Corporate Governance" curriculum:

| Section | Topic | Core Contents |
|---|---|---|
| **Part 1** | Overview of FPT Corporation | History, business units (FPT Software, Telecom, IS, Education), mission & core values. |
| **Part 2** | Operational Management | Management chart, CEO & Deputy CEOs, parent-subsidiary coordination, operational bottlenecks, proposed improvements. |
| **Part 3** | Corporate Governance | Governance structure (General Meeting of Shareholders, Board of Directors, Supervisory Board), governance vs. management distinction, CG Code & OECD compliance. |
| **Part 4** | AI Impact on Governance & Management | AI Factory, operational efficiency (productivity tracking, automation), strategic decision-making support, cybersecurity & ethical risks. |
| **Part 5** | Conclusion & Recommendations | Summary and governance lessons for Vietnamese enterprises. |

---

<a id="quick-start"></a>
## 🚀 Quick Start

### Prerequisites

Install a TeX distribution supporting UTF-8 and Vietnamese fonts:
- **Windows**: [MiKTeX](https://miktex.org/) or [TeX Live](https://www.tug.org/texlive/)
- **Editor**: [VS Code](https://code.visualstudio.com/) with LaTeX Workshop extension, or [TeXstudio](https://www.texstudio.org/), or [Overleaf](https://www.overleaf.com/)

### Compilation

```bash
# 1. Clone repository
git clone https://github.com/Tuannll/fpt-management-governance-essay.git
cd fpt-management-governance-essay

# 2. Compile via pdflatex
pdflatex -synctex=1 -interaction=nonstopmode main.tex
pdflatex -synctex=1 -interaction=nonstopmode main.tex
```

> [!TIP]
> Run `pdflatex` twice to generate and update the Table of Contents (`main.toc`).

---

<a id="project-structure"></a>
## 📁 Project Structure

```text
├── main.tex           # Master LaTeX source file with preamble & cover page
├── references.bib     # Bibliography file
├── figures/           # Organization charts, diagrams, and figures
├── chapters/          # Individual modular chapters
│   ├── 00_loi_mo_dau.tex
│   ├── 01_tong_quan_fpt.tex
│   ├── 02_thuc_trang_quan_ly.tex
│   ├── 03_thuc_trang_quan_tri.tex
│   ├── 04_tac_dong_ai.tex
│   └── 05_ket_luan.tex
├── .gitignore         # LaTeX build artifact exclusions
├── README.md          # Project documentation (English)
└── README.vi.md       # Project documentation (Tiếng Việt)
```

---

<a id="faq"></a>
## ❓ FAQ

<details>
<summary><b>1. Why choose FPT Corporation as the case study?</b></summary>
<br/>

FPT is Vietnam's leading technology corporation with publicly audited annual reports, a transparent governance model (HOSE: FPT), and active investments in AI (NVIDIA partnership, AI Factory).
</details>

<details>
<summary><b>2. How is work divided between the 2 team members?</b></summary>
<br/>

Member 1 focuses on Overview, Management Analysis, and LaTeX formatting. Member 2 focuses on Corporate Governance, AI Impacts, and Reference Synthesis.
</details>

<details>
<summary><b>3. Can we write directly on Overleaf?</b></summary>
<br/>

Yes. Push `main.tex` and assets to GitHub, then link the repository directly with Overleaf.
</details>

---

<a id="tech-stack"></a>
## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| **LaTeX (pdfLaTeX)** | Document typesetting and academic formatting |
| **TikZ** | Cover border and decorative formatting |
| **Git / GitHub** | Version control and collaborative editing |

---

<a id="license"></a>
## 📄 License

Distributed under the MIT License.
