<p align="center">
  <img src="book/assets/ML_Learning_Journey.png" alt="ML Journey Logo" width="200"/>
</p>

# 📘 Machine Learning Journey

**Machine Learning Journey** is a **structured learning framework** for anyone who wants to finally start Machine Learning without confusion.  
It combines **theory + practice** in one place, so you don’t need scattered notes or separate projects.  

With a clear roadmap, 2h/day routine, and organized repo structure, you can:  
- Learn ML concepts step by step  
- Practice directly in Jupyter notebooks  
- Keep everything tracked and easy to review later  
- Gradually build your own personal ML playbook  

---

## ✨ Features

- **Structured learning path** → follow a phase-by-phase roadmap (2h/day)  
- **Theory + Practice together** → notebooks and reports stay connected  
- **Forkable & Reusable** → anyone can fork and start learning with this template  
- **LaTeX reports (optional)** → generate clean summaries if you want academic-style notes  
- **Automatic builds** → GitHub Actions builds PDFs for you  
- **Future-ready** → extend to bilingual docs or website if needed  

---

## 🚀 Structure

```
ML-Learning-Journey/
│
├── LICENSE             # MIT license for code
├── LICENSE-docs        # CC BY-NC-SA license for docs
├── README.md           # this file
├── CHANGELOG.md        # project history
├── ROADMAP.md          # detailed learning roadmap
│
├── .github/workflows/  # GitHub Actions for CI
│
├── book/               # (optional) LaTeX notes and reports
│   ├── assets/         # logos, covers, images
│   ├── config/         # colors, commands, metadata
│   ├── parts/          # shallow + deep chapters
│   ├── shared/         # code, diagrams, figures, tables
│   ├── templates/      # tex chapter templates
│   ├── main_en.tex
│   └── main_fa.tex
│
├── notebooks/          # Jupyter notebooks (main learning path)
│   ├── data/           # datasets
│   └── Phase1/         # phase-based learning
│       └── day1_numpy.ipynb
│
├── pdfs/               # official PDF builds
│   ├── en/main_en.pdf
│   └── fa/
│
├── scripts/            # helper scripts
│   └── build-pdf.ps1
│
└── site/               # reserved for future website
```

---

## 🛠️ How to Use

1. **Fork this repo** into your own GitHub  
2. Follow the [ROADMAP.md](./ROADMAP.md) step by step (2h/day suggested)  
3. Work inside `notebooks/` for practice (phase by phase)  
4. (Optional) Write weekly/phase reports in `book/` → auto-build to PDF  
5. Track your progress in `CHANGELOG.md` or a separate `PROGRESS.md`  

---

## 📌 Roadmap

- [x] Setup initial repository structure  
- [x] Add licenses, README, and logo  
- [ ] Phase 1: NumPy & Pandas basics  
- [ ] Phase 2: Classical ML algorithms  
- [ ] Phase 3: Deep Learning fundamentals  
- [ ] Phase 4: MLOps + Research practices  
- [ ] Build bilingual (English + Persian) versions  
- [ ] Publish as a website  

👉 See detailed roadmap here: [ROADMAP.md](./ROADMAP.md)

---

## 📜 Licenses

- **Code** → [MIT License](./LICENSE)  
- **Documentation/Reports** → [CC BY-NC-SA 4.0](./LICENSE-docs)  

---

## 📬 Contact

- Author: **Masoud Khanalizadeh Imani**  
- Email: masoud.khanalizadehimani@gmail.com  

---

## 🪙 Support This Project

If you find **Machine Learning Journey** useful, you can support by:

- ⭐ Starring this repository on GitHub  
- 🐦 Sharing it with your network  
- ☕ For Iran: [coffeete.ir/masoud.khanalizadehimani](http://www.coffeete.ir/masoud.khanalizadehimani)  
- ☕ International: [buymeacoffee.com/masoudkhanalizadeh](https://buymeacoffee.com/masoudkhanalizadeh)  

Your support motivates me to keep improving this framework and eventually release a polished ML playbook for free.  
