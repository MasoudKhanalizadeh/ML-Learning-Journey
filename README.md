<p align="center">
  <img src="assets/cover.png" alt="ML Journey Cover" width="640"/>
</p>

# 📘 Machine Learning Journey

**Machine Learning Journey** is both:
- a **personal learning path** (daily 2h practice → notes + coding), and  
- a **book project** (shallow explanations + deep dives, publishable as PDF and later as a website).  

From fundamentals to advanced research, with **code**, **notebooks**, and **academic reports**.

---

## ✨ Features

- **Two-layer content:**  
  - *Shallow* → concise but complete overview  
  - *Deep* → detailed technical deep dive with references  
- **Linked coding practice:** Jupyter notebooks connected to each chapter  
- **LaTeX book system:** clean structure, multilingual-ready (English, Persian)  
- **Automatic builds:** via `latexmk` locally and GitHub Actions in CI/CD  
- **Future website integration:** book can be published as a static site  

---

## 🚀 Structure

```
ML-Learning-Journey/
│
├── LICENSE             # MIT license for code
├── LICENSE-docs        # CC BY-NC-SA license for book/docs
├── README.md           # this file
├── CHANGELOG.md        # project history
│
├── book/               # LaTeX source of the book
│   ├── main_en.tex     # main entry (English)
│   ├── main_fa.tex     # reserved for Farsi (future)
│   ├── config/         # metadata, colors, commands
│   ├── i18n/           # strings for multilingual support
│   ├── frontmatter/    # title page, publisher info
│   ├── parts/          # chapters (shallow + deep)
│   ├── references/     # refs.bib for citations
│   ├── glossary/       # abbreviations, glossary
│   ├── index/          # keywords for index
│   ├── templates/      # shallow/deep chapter templates
│   └── shared/         # figures, code snippets, diagrams, tables
│
├── notebooks/          # Jupyter notebooks for practice
│   ├── week1/
│   └── data/
│
├── pdfs/               # official build outputs (PDFs)
│   ├── en/
│   └── fa/
│
├── site/               # reserved for future website build
└── scripts/            # build scripts (local + CI)
```

---

## 🛠️ Build Instructions

### Local Build (Windows PowerShell)
```powershell
cd book
latexmk -pdf -outdir=../pdfs/en main_en.tex
```
Output: `pdfs/en/ML-Journey-v0.1.pdf`

### GitHub Actions (CI/CD)
Whenever you `git push`, GitHub automatically builds the PDF and makes it available as an artifact.

---

## 📌 Roadmap

- [x] Setup initial repository structure  
- [x] Add licenses and README  
- [ ] Week 1: NumPy & Pandas  
- [ ] Week 2: Classical ML algorithms  
- [ ] Week 3: Deep Learning basics  
- [ ] Part IV: MLOps + Research practices  
- [ ] Build bilingual (English + Persian) versions  
- [ ] Publish as a website  

---

## 📜 Licenses

- **Code** → [MIT License](./LICENSE)  
- **Documentation/Book** → [CC BY-NC-SA 4.0](./LICENSE-docs)  

---

## 📬 Contact

- Author: **Masoud Khanalizadeh Imani**  
- Email: masoud.khanalizadehimani@gmail.com  

---

## 🪙Support This Project

If you find **Machine Learning Journey** useful, please consider supporting its development:

- ⭐ Star this repository on GitHub  
- 🐦 Share it with your network  
- ☕ Iran: [coffeete.ir/masoud.khanalizadehimani](http://www.coffeete.ir/masoud.khanalizadehimani)  
- ☕ International: [buymeacoffee.com/masoudkhanalizadeh](https://buymeacoffee.com/masoudkhanalizadeh)  

Your support helps me continue building this journey and expand it into a book + website.  
