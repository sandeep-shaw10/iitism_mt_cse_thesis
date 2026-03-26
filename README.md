# 🎓 IIT (ISM) MTech CSE Thesis Template (2025)

A LaTeX template for MTech CSE thesis at Indian Institute of Technology (ISM), Dhanbad.

🔗 [View on Overleaf](https://www.overleaf.com/read/qbsrrprbqtzb#1157aa)

---

## 📦 What’s inside
- 📄 Title Page, Declaration, Certificates  
- 📚 Chapter-wise structured files  
- 🧾 Header and Footer formatting  
- 🔗 Hyperlink configuration  

---

## ⚙️ How to use
#### 1. Open `config.tex`
#### 2. Update your details:
   - 👤 Name  
   - 🎫 Roll Number  
   - 📌 Thesis Title  
   - 👨‍🏫 Guide  

```tex
% --- rest of the configuration

% --- Thesis Metadata Variables ---
\newcommand{\mysalutation}{Mr}
\newcommand{\myname}{Sam Placeholder}
\newcommand{\myrollno}{24XX0000}
\newcommand{\myday}{4}
\newcommand{\mymonth}{May}
\newcommand{\myyear}{2025}
\newcommand{\mythesistitle}{Blockchain-Based Framework for Employee Experience Certificate Verification}
\newcommand{\myguide}{Prof. Md Alice Rastogi}
\newcommand{\myhod}{Prof. Tulsi Das Khan}
\newcommand{\mydept}{Department of Computer Science and Engineering}
\newcommand{\myinst}{Indian Institute of Technology (Indian School of Mines), Dhanbad}
\newcommand{\myHouse}{23/1/A/H/17 M.G.Road}
\newcommand{\myTown}{Kharagpur}
\newcommand{\myDistrict}{Paschim Medinipur}
\newcommand{\myState}{West Bengal, 7XXXXX}
```
#### 3. Compile `main.tex`

---

## 📁 Project Structure
```txt
.
├── 1_titlepage
│   └── main.tex
│
├── 2_declaration
│   ├── 1_final_version.tex
│   ├── 2_student.tex
│   ├── 3_classified_data.tex
│   ├── 4_english_check.tex
│   └── 5_copyright_consent.tex
│
├── 3_frontsection
│   ├── abbreviations.tex
│   ├── abstract.tex
│   └── acknowledgements.tex
│
├── 4_chapters
│   ├── 1_introduction.tex
│   ├── 2_literature.tex
│   ├── 3_methodology.tex
│   ├── 4_result.tex
│   └── 5_conclusion.tex
│
├── 5_backsection
│   ├── reference.tex
│   └── report.tex
│
├── assets
│   ├── fonts
│   ├── images
│   ├── logos
│   └── pdf
│
├── custom
│   ├── commands.tex
│   └── packages.tex
│
├── config.tex
├── main.tex
└── README.md
```

## 👨‍💻 Author
Template for IIT (ISM) CSE students. \
Feel free to use and modify.