### Similarity-Sensitivity-of-Neighborhood-Image-Embeddings

This study investigates how neighborhood size (k) influences similarity-based groupings within image embedding spaces. Using open-source image datasets and ResNet embeddings, we empirically quantify how local neighborhood structure changes relative to a full 𝑁 × 𝑁 similarity baseline, characterizing the sensitivity of unsupervised similarity search to k-limited neighborhood construction.


# Environment Setup (Miniconda)

This project uses a dedicated conda environment for reproducibility.  
Follow the steps below to install Miniconda, create the environment, and install all dependencies.

---

## 1. Install Miniconda
Download the installer for your OS:  
https://docs.conda.io/en/latest/miniconda.html  
Follow the installation instructions, then restart your terminal.

---

## 2. Create and activate the environment
```bash
conda create -n similarity-exp python=3.10 -y
conda activate similarity-exp
```

## 3. Install dependancies 
```bash
pip install requirements.txt
```