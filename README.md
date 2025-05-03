# Identifying Phenotypic Characteristics of Seal DNA Methylation Using Bayesian Neural Networks

This repository contains the official implementation of the experiments presented in our IEEE Access paper:

> **"Identifying Underlying Phenotypic Characteristics of Seal DNA Methylation Data and Distinguishing Between Seal Species Using Machine Learning"**

## 📄 Abstract

Bayesian Neural Networks (BNNs) were applied to high-dimensional DNA methylation data to distinguish between different tissue types and seal species, including the North Elephant Seal, Hawaiian Monk Seal, and Weddell Seal. Our study demonstrates that BNNs can effectively identify species-specific and tissue-specific epigenetic signatures, offering a probabilistic approach to modeling uncertainty in complex biological datasets.

---

## 🧬 Key Contributions

- ✅ **Tissue Classification**: Differentiates muscle and skin tissue within North Elephant Seals with 83.89% accuracy.
- ✅ **Species Identification**: Achieves 100% classification accuracy when distinguishing between seal species (NES, HMS, WED).
- ✅ **BNNs Architecture**: Integrates variational inference with dropout and ReLU activations for uncertainty quantification.
- ✅ **Data Preprocessing**: Uses scaffold-based methylation proportions, PCA visualization, and normalization pipelines.

---

## 📁 Project Structure
methylation-tissue-classification/ ├── scripts/ │ └── methylation_journal_all_code_for_bnns.py ├── data/ │ └── README.md # Dataset privacy note ├── requirements.txt ├── .gitignore └── README.md


---

## 📂 Dataset Access

The dataset is not included in this repository due to privacy restrictions. It contains bisulfite-sequenced whole-genome methylation profiles from 24 seal samples.

- Species included: NES, HMS, WED
- Tissues: Muscle and skin
- Features: ~369,000 scaffold positions


## 🚀 Getting Started

Install the required Python packages:

```bash
pip install -r requirements.txt

python scripts/methylation_journal_all_code_for_bnns.py

