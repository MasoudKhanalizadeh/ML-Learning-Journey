# 🗺️ Machine Learning Journey — Roadmap (2h/day)

> Target: **Junior-to-solid ML foundations** with practical portfolio + publishable book (shallow/deep).  
> Cadence: ~**2 hours/day**, ~**5–6 days/week** → ~**10–12 h/week**.  
> Horizon: **~20–24 weeks** (adjust pace as needed).

---

## Phase 1 — Foundations (Weeks 1–4)

- [ ] **Week 1: Python & NumPy**
  - Arrays, vectorization, broadcasting, shapes/strides (shallow + deep appendix)
  - Notebook: `notebooks/week1/day1_numpy.ipynb`
  - Book: `parts/foundations/ch01_numpy_shallow.tex` + `deep/ch01_numpy_deep.tex`
- [ ] **Week 2: Pandas & Data Cleaning**
  - Series/DataFrame, missing data, joins, groupby, tidy data
  - Mini-project: clean a small CSV and profile it
- [ ] **Week 3: Visualization**
  - Matplotlib basics → layered charts, hist/kde, scatter matrix
  - Communicating insights (figures saved into `book/shared/figures/`)
- [ ] **Week 4: Probability & Linear Algebra refresher**
  - Distributions, expectation/variance, Bayes intuition
  - Linear algebra for ML (dot, norms, eig/SVD intuition)

**Deliverable:** PDF `pdfs/en/Foundations-v0.1.pdf` + 2–3 notebooks.

---

## Phase 2 — Classical ML (Weeks 5–10)

- [ ] **Week 5: Regression**
  - Linear/Polynomial regression, regularization (Ridge/Lasso), bias–variance
  - Metrics: MSE/MAE/R², cross-validation
- [ ] **Week 6: Classification (Logistic, k-NN)**
  - Thresholds, decision boundaries, calibration
  - Metrics: accuracy, precision/recall, F1, ROC-AUC, PR curves
- [ ] **Week 7: Trees & Ensembles**
  - Decision Trees, Random Forests, Gradient Boosting (XGBoost/LightGBM overview)
  - Feature importance & leakage pitfalls
- [ ] **Week 8: Model Validation & Experimentation**
  - Train/val/test, CV schemes, leakage, target encoding safely
  - Reproducibility, random seeds, experiment logs
- [ ] **Week 9: Feature Engineering**
  - Scaling/encoding, binning, interactions, text/categorical handling
  - Pipelines in scikit-learn
- [ ] **Week 10: Unsupervised Learning**
  - k-means, hierarchical, PCA/t-SNE/UMAP (intuition + limitations)

**Deliverable:** PDF `pdfs/en/Classical-ML-v0.1.pdf` + 4–6 notebooks + 1 small Kaggle-style project.

---

## Phase 3 — Deep Learning (Weeks 11–16)

- [ ] **Week 11: PyTorch Essentials**
  - Tensors, autograd, modules, optimizers; overfitting/regularization
- [ ] **Week 12: MLPs for Tabular/Numeric**
  - BatchNorm/Dropout, LR schedules; compare with classical baselines
- [ ] **Week 13: Computer Vision Basics**
  - CNNs, data augmentation, transfer learning; small image task
- [ ] **Week 14: NLP Basics**
  - Tokenization, embeddings, RNN/LSTM vs. modern encoders; simple text classifier
- [ ] **Week 15: Training Practices**
  - Checkpoints, early stopping, mixed precision, reproducibility
- [ ] **Week 16: Serving Basics**
  - Saving models, inference scripts, simple REST/CLI inference

**Deliverable:** PDF `pdfs/en/Deep-Learning-v0.1.pdf` + 3–5 notebooks + 1 mini CV or NLP project.

---

## Phase 4 — MLOps & Research (Weeks 17–20)

- [ ] **Week 17: Data & Experiment Tracking**
  - DVC or lightweight versioning; MLflow/Weights & Biases (concepts)
- [ ] **Week 18: Evaluation at Scale**
  - Robust metrics, error analysis, slicing (by cohort), fairness basics
- [ ] **Week 19: Deployment Mindset**
  - Packaging, environment lock, simple Docker; monitoring concepts
- [ ] **Week 20: Research Skills**
  - Reading papers efficiently, reproducing baselines, writing deep appendices

**Deliverable:** PDF `pdfs/en/MLOps-Research-v0.1.pdf` + 1 applied mini-project (end-to-end).

---

## Capstone (Weeks 21–24)

- [ ] Choose a problem (tabular / vision / NLP) with a small public dataset
- [ ] Build EDA → baseline classical → DL variant (if applicable)
- [ ] Track experiments, ensure reproducibility, write a **Shallow chapter + Deep appendix**
- [ ] Publish notebook + PDF; optional blog/site page

**Deliverable:** `pdfs/en/Capstone-v1.0.pdf` + repo links to code.

---

## Ongoing Habits (every week)

- [ ] 1–2 hrs **reading** (book section or survey/paper) → add notes to Deep appendix
- [ ] 3–5 hrs **coding** (notebooks or scripts)
- [ ] 1 **commit/day** goal; keep CHANGELOG updated
- [ ] After each chapter: build PDF → store under `pdfs/en/` and tag a release

---

## Repository Links in Book

- Near each code listing, include: `\CodeLink{<URL to file/folder>}{label}`  
- Global repo link in header via metadata: `\BookRepoURL`

---

## Milestones & Versions

- [ ] v0.1 — Foundations complete (PDF)  
- [ ] v0.2 — Classical ML (PDF)  
- [ ] v0.3 — Deep Learning (PDF)  
- [ ] v0.4 — MLOps & Research (PDF)  
- [ ] v1.0 — Capstone + full book PDF  
- [ ] v1.x — Translations (Farsi), website publish
