# Data & Stats Analysis Portfolio
### Nadine Radwan — Molecular & Cell Biology / Marine Biology, AUC

I spend most of my time extracting clean signal out of messy biological systems — pulling DNA off
a calcified sea star, coaxing a sugarcane sample through acclimatization, reading a gel to see if
a PCR actually worked. This portfolio is the same instinct pointed at data instead of tissue: three
independent statistics projects that all ask a version of the same question — **how much of what
looks complicated is actually just a few real signals in disguise?**

---

## 🐧 The Projects

| # | Project | Question | Headline Result |
|---|---|---|---|
| 1 | [**Discriminant Analysis**](./project1-discriminant-analysis) | Given the species labels, how well do four body measurements separate Adelie, Chinstrap, and Gentoo penguins? | **98.5%** leave-one-out accuracy (FLDA); a single BACON-flagged outlier changes nothing |
| 2 | [**Clustering Analysis**](./project2-clustering) | Hide the species labels entirely — does the same three-group structure still emerge from the geometry alone? | **96.8%** agreement with true species (Ward hierarchical clustering), with *zero* label access during clustering |
| 3 | [**PCA & MDS**](./project3-pca-mds) | Thirteen correlated body measurements — what's the real, intrinsic dimensionality underneath them? | **3 dimensions** explain ~80% of variance, confirmed by 4 independent methods (classical PCA, robust PCA, classical MDS, MDS post-outlier-removal) |

Projects 1 and 2 are a matched pair on the same dataset (Palmer Penguins) — one supervised, one not
— designed to cross-check each other. Project 3 takes the dimensionality question to a different
dataset (`fat`, 252 adult men) and asks it from four angles instead of two.

All analysis is in **R**, run inside Jupyter notebooks via the `IRkernel`. Each notebook is fully
self-contained — data description, methods, results, and a written conclusion — so you can open any
one of them without needing the others.

---

## 🔧 Methods & Tools

`R` · `MASS` (LDA) · `nnet` (multinomial logistic regression) · `robustbase` / `robustX` (BACON
outlier detection) · `DescTools` (Hotelling's T²) · `clue` (Hungarian matching for cluster
evaluation) · `faraway` (dataset) · hierarchical & k-means clustering · classical & robust PCA ·
classical MDS

---

## About Me

I'm a dual-degree student at the **American University in Cairo**, majoring in **Molecular & Cell
Biology** and **Marine Biology**, with minors in **Chemistry** and **Applied Probability &
Statistics**. Recent work spans DNA extraction and PCR on sea star specimens for Dr. Arthur Bos'
lab, large-scale plant tissue culture (1,000+ sorghum embryos plated) for Dr. Walid Fouad's lab,
and — on the applied side — co-building **Proteus**, an AI-powered marine engagement platform that
took **2nd place** at the Capgemini AI Hackathon.

I'm also a **PADI Advanced Open Water & Enriched Air diver**, which is either a fun fact or the
most literal way possible to say I like collecting my own data underwater.

📧 radwan.nadine@gmail.com
🔗 [linkedin.com/in/nadine-radwan-47240828a](https://linkedin.com/in/nadine-radwan-47240828a)
