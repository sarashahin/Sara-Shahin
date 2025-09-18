# Sara Shahin — PhD Researcher in AI
**Simulation-Based - Unified spatio-temporal biodiversity mathematical modelling • Probabilistic & stochastic dynamics (IBM / ODE / PSD) • GPU acceleration • Medical imaging & robust ML**

[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--7847--6242-green)](https://orcid.org/0009-0000-7847-6242)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-sara--shahin-blue)](https://www.linkedin.com/in/sara-shahin-3a842929/)
[![GitHub followers](https://img.shields.io/github/followers/sarashahin?style=social)](https://github.com/sarashahin)

Hi — I’m **Sara**, a PhD student at **Queen Mary University of London**.  
I build **mathematical simulation-first AI** for ecosystems: from **individual-based models (IBM)** to **ODE** and **PSD(Probabilistic, Stochastic & Deterministic)** approximations, with GPU-accelerated pipelines for large spatio-temporal systems. I also ship applied ML in **medical imaging** and **wildlife biometrics**.

---
## 🎓 Education
- **PhD in Simulation-Based - Unified spatio-temporal biodiversity mathematical modelling with AI**, Queen Mary University of London — *Jan 2025 – Present*  
- **MSc in Artificial Intelligence (Distinction)**, Anglia Ruskin University — *Sep 2023 – Sep 2024*
- **BSc in Machine Learning & Artificial Intelligence (First Class Honours)**, Goldsmiths, University of London — *2020 – Mar 2023*

---

## 🧪 Research & Work Experience
- **Simulation-based inference for ecosystems** — multi-patch IBM, Lotka–Volterra ODEs, PSD approximations; invasion/assembly, dispersal kernels, oscillations, stable time-stepping, diagnostic guards, **CuPy/CUDA** acceleration.
- **Wildlife biometrics:** self-supervised features + metric learning for camera-trap **re-identification** (badgers), with a small GUI.
- **Medical imaging:** Attention-UNet segmentation + **ensemble defenses** improving robustness to corruption/adversarial noise.

---

## 📂 Selected Projects
> Click the repo names for code & instructions. Each includes a problem statement, quick-start commands, and figures.

### 1. [Metacommunity Simulator (IBM / ODE / PSD)]()
Multi-patch IBM with **infinite-pool assembly**, ODE and PSD(Probabilistic, Stochastic, Deterministic) baselines, dispersal kernels, invasion tracking, mosaics & trajectory panels. GPU mode with **CuPy**.  
**Key results:** PSD replicates IBM/ODE qualitative dynamics across body-mass regimes; non-local dispersal slows oscillations and alters invasion pressure.
**Repo:** *(private)* · **Figures:** mosaics, 3×2 trajectories.

### 2. [Badger AI — Wildlife Biometrics](https://github.com/sarashahin/Badger_AI)
Self-supervised features + metric learning for **individual re-identification** from camera trap images; Detectron2/YOLOv5 baselines; simple GUI.  
**Key results:** >90% same-individual retrieval on held-out data; robust to varied lighting and angle.

### 3. [Automate NART Grading](https://github.com/sarashahin/Automate-Grading-Test-NART)
Automates grading of **National Adult Reading Test (NART)** pronunciations with mel-spectrogram features, CNN/CRNN/Transformer models.  
**Key results:** Stable accuracy across speakers; detailed phoneme-level confusion analysis.

### 4. [Medical Imaging — Attention-UNet & Robustness](https://github.com/sarashahin/Breast_Cancer_UNet_Segmentatio)
Attention-UNet for ultrasound segmentation; robustness tests under noise/adversarial perturbations; ensemble defenses for detection.  
**Key results:** +4–6% Dice over vanilla UNet; ensembles improve corruption robustness by >10% mAP.

### 5. [Multimodal Fake News Detection](https://github.com/sarashahin/Multimodal-Fake-News-Detection)
Simple multimodal baseline: CNN for image, BERT for text, late fusion classification.  
**Key results:** +3–5% accuracy vs. text-only or image-only baselines.

---

## 📄 Publications & Manuscripts
- **Evaluation of Ensemble Learning for Mitigating Adversarial Attacks in Industrial Object Detection** — *TechRxiv preprint*, 15 May 2024. DOI: [10.36227/techrxiv.171561173.31420188/v1](https://doi.org/10.36227/techrxiv.171561173.31420188/v1)  
- **Distinct Paradigms of Metacommunity Theory Emerge from Probabilistic–Stochastic–Deterministic Approximation of Individual-Based Models** — *in preparation*.

---

## 🎓 Scholarships, Awards & Outreach
- 🏛 **Alan Turing Institute — Data Study Group (Sept 2025)**  
  Selected PhD researcher for a competitive, 2-week, industry-facing programme solving real-world data science challenges in a multidisciplinary team.

- 🌍 **Open Source Summit Europe 2025 — Scholarship Awardee**  
  Awarded a fully funded scholarship to attend the Open Source Summit Europe (Amsterdam, 25–27 Aug 2025), engaging with the global open-source community.

- 🧬 **Bertelsmann Scholarship** — Genomic Data Science Track  

- 👩‍💻 **Women in Computer Science & Engineering** — Sponsored Delegate (Milan, First Ascent)  

- 🤝 **Open-source contributions** — Documentation, tests, and benchmarks in ML ecosystems


---

## 🛠 Tech Stack
**Languages & Libraries:** Python (NumPy/CuPy, PyTorch, Keras), Numba, Matplotlib, scikit-learn  
**Tools:** DVC / LFS, pytest, ruff, mypy, GitHub Actions, Docker  
**Specialties:** Simulation, stochastic processes, time-series modelling, GPU acceleration

---

## 🚀 Quickstart Example
All repos ship a minimal config + one-command reproduction of main figures.

```bash
# Example: run a tiny IBM demo and plot a figure
python -m sim.run --config configs/rps_demo.yaml --out runs/demo
python analysis/make_panels.py runs/demo/output.npz

```

---


## 📌 Connect with Me

- 🌐 [LinkedIn](https://www.linkedin.com/in/sara-shahin-3a842929/)
- 📧 s.shahin@qmul.ac.uk
- 📊 [Kaggle](https://www.kaggle.com/sarashahin)
- 💼 [Download My CV](https://github.com/sarashahin/Sara-Shahin/blob/main/Profile.pdf)

---

## 📈 Ongoing

Currently developing generative and simulation-based biodiversity models using spatio-temporal dynamics with AI. Open to research collaborations and internship opportunities in AI, simulation, and sustainability.

---

⭐ Feel free to explore my repositories, follow for updates, or get in touch if you'd like to collaborate!






