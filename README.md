# Gamma-Ray Bursts: Observational Techniques and Data Analysis

This repository presents a full Python-based workflow for analyzing real gamma-ray data from high-energy missions such as **EGRET**, **BATSE**, and **Fermi GBM**. It is developed as a hands-on project for learning **observational techniques**, **data mining**, **sky visualization**, and **spectral analysis of GRBs** (Gamma-Ray Bursts).

📘 **Documentation** generated with Sphinx:  
👉 https://angelphysics.github.io/GammaRay-Bursts-ObservationalTechniques/

---

## 🛰️ Data Sources Covered

- **EGRET** (Energetic Gamma Ray Experiment Telescope)
- **BATSE** (Burst and Transient Source Experiment)
- **Fermi GBM** (Gamma-ray Burst Monitor)

---

## 📂 Structure and Key Sections

### 📦 Part 1: EGRET Analysis
- Vizier queries and catalog download
- Source type classification and coordinate handling
- Mollweide projection in galactic coordinates
- Interactive visualization using **PyWWT**
- Final sky map of classified sources

### 🌠 Part 2: BATSE Burst Exploration
- Burst catalog retrieval from Vizier
- Coordinate conversion and flux extraction
- Galaxy/extragalactic classification
- Integration with EGRET and joint visualization

### ⚡ Part 3: Fermi GBM GRB Case Study
- GRB selection and TTE data download (via HEASARC)
- Time tagging, binning and spectrum construction
- Prompt phase spectrum and S/N boosting
- **Spectral evolution analysis** (early vs late phase)
- Burst classification (long vs short)
