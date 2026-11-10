<div align="center">

# Tiểu Luận Quản Lý & Quản Trị Doanh Nghiệp FPT

**Tiểu luận nghiên cứu học thuật về Quản lý, Quản trị công ty và Tác động của Trí tuệ Nhân tạo (AI) tại Tập đoàn FPT.**

[![LaTeX](https://img.shields.io/badge/LaTeX-2e-008080?logo=latex&logoColor=white)](https://www.latex-project.org/)
[![Build PDF](https://github.com/Tuannll/fpt-management-governance-essay/actions/workflows/build-pdf.yml/badge.svg)](https://github.com/Tuannll/fpt-management-governance-essay/actions/workflows/build-pdf.yml)
[![View PDF](https://img.shields.io/badge/PDF-Xem_Online-red.svg)](https://github.com/Tuannll/fpt-management-governance-essay/blob/pdf/main.pdf)
[![Status](https://img.shields.io/badge/Status-In_Progress-orange.svg)]()
[![Team](https://img.shields.io/badge/Team-2_Members-blue.svg)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[English](README.md) | **Tiếng Việt**

**[📄 Xem trực tiếp PDF](https://github.com/Tuannll/fpt-management-governance-essay/blob/pdf/main.pdf) • [🚀 Quick Start](#quick-start) • [✨ Cấu trúc bài tiểu luận](#essay-structure) • [❓ FAQ](#faq)**

</div>

---

<a id="essay-structure"></a>
## ✨ Cấu trúc bài tiểu luận

Nội dung tiểu luận bám sát yêu cầu chương trình môn "Khoa học Quản lý và Quản trị":

| Phần | Chủ đề | Nội dung cốt lõi |
|---|---|---|
| **Phần 1** | Tổng quan về Tập đoàn FPT | Lịch sử hình thành, các khối ngành (FPT Software, Telecom, IS, Education), sứ mệnh & giá trị cốt lõi. |
| **Phần 2** | Thực trạng hoạt động Quản lý | Sơ đồ cơ cấu tổ chức, vai trò TGĐ & các Phó TGĐ, cơ chế phối hợp mẹ - con, các điểm nghẽn vận hành và giải pháp cải thiện. |
| **Phần 3** | Thực trạng hoạt động Quản trị | Cơ cấu quản trị (ĐHĐCĐ, HĐQT, BKS), phân định ranh giới Quản trị vs Quản lý, đối chiếu chuẩn mực CG Code & OECD. |
| **Phần 4** | Tác động của AI đến Quản lý & Quản trị | Chiến lược AI Factory, tối ưu hiệu suất vận hành (đo lường năng suất, tự động hóa), hỗ trợ ra quyết định chiến lược, thách thức an ninh & đạo đức AI. |
| **Phần 5** | Kết luận và Kiến nghị | Tổng kết bài học kinh nghiệm về quản lý và quản trị cho doanh nghiệp Việt Nam. |

---

<a id="quick-start"></a>
## 🚀 Quick Start

### Yêu cầu môi trường

Cài đặt bản phân phối TeX hỗ trợ font tiếng Việt (T5/UTF-8):
- **Windows**: [MiKTeX](https://miktex.org/) hoặc [TeX Live](https://www.tug.org/texlive/)
- **Trình soạn thảo**: [VS Code](https://code.visualstudio.com/) kèm extension LaTeX Workshop, [TeXstudio](https://www.texstudio.org/), hoặc [Overleaf](https://www.overleaf.com/)

### Biên dịch tài liệu

```bash
# 1. Clone repository
git clone https://github.com/Tuannll/fpt-management-governance-essay.git
cd fpt-management-governance-essay

# 2. Biên dịch bằng pdflatex
pdflatex -synctex=1 -interaction=nonstopmode main.tex
pdflatex -synctex=1 -interaction=nonstopmode main.tex
```

> [!TIP]
> Biên dịch lệnh `pdflatex` 2 lần để hệ thống cập nhật đúng Mục lục (`main.toc`).

---

<a id="project-structure"></a>
## 📁 Cấu trúc thư mục

```text
├── main.tex           # File mã nguồn LaTeX chính (khung bìa + mục lục)
├── references.bib     # Danh mục tài liệu tham khảo BibTeX
├── figures/           # Chứa sơ đồ tổ chức, hình ảnh minh họa
├── chapters/          # Các chương nội dung dạng mô-đun
│   ├── 00_loi_mo_dau.tex
│   ├── 01_tong_quan_fpt.tex
│   ├── 02_thuc_trang_quan_ly.tex
│   ├── 03_thuc_trang_quan_tri.tex
│   ├── 04_tac_dong_ai.tex
│   └── 05_ket_luan.tex
├── .gitignore         # Bộ lọc bỏ qua file rác sinh ra khi biên dịch LaTeX
├── README.md          # Tài liệu dự án (Tiếng Anh)
└── README.vi.md       # Tài liệu dự án (Tiếng Việt)
```

---

<a id="faq"></a>
## ❓ FAQ

<details>
<summary><b>1. Tại sao lại chọn Tập đoàn FPT làm đối tượng nghiên cứu?</b></summary>
<br/>

FPT là tập đoàn công nghệ quy mô lớn nhất Việt Nam, có dữ liệu công khai minh bạch qua các Báo cáo thường niên và Báo cáo quản trị (HOSE: FPT), đồng thời tiên phong đầu tư AI (hợp tác NVIDIA, AI Factory).
</details>

<details>
<summary><b>2. Nhóm 2 người nên phân chia công việc như thế nào?</b></summary>
<br/>

Thành viên 1 phụ trách Tổng quan, Phân tích Quản lý (Management), thiết lập khung LaTeX. Thành viên 2 phụ trách Quản trị (Governance), Tác động AI, và tổng hợp tài liệu tham khảo.
</details>

<details>
<summary><b>3. Có thể viết trực tiếp trên Overleaf không?</b></summary>
<br/>

Được. Đẩy mã nguồn lên GitHub, sau đó kết nối repo trực tiếp vào Overleaf để 2 thành viên cùng soạn thảo theo thời gian thực.
</details>

---

<a id="tech-stack"></a>
## 🛠️ Công nghệ sử dụng

| Công nghệ | Vai trò |
|---|---|
| **LaTeX (pdfLaTeX)** | Soạn thảo và định dạng văn bản học thuật |
| **TikZ** | Tạo khung viền trang bìa chuẩn quy định |
| **Git / GitHub** | Quản lý phiên bản và phối hợp nhóm |

---

<a id="license"></a>
## 📄 Giấy phép (License)

Phát hành theo giấy phép mã nguồn mở MIT License.
