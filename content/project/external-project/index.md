
---
title: Develop a cancer-drug response prediction model
summary: The model could accelerate drug discovery and precision medicine.
tags:
  - Deep learning; Drug response; Transfer learning; multi-modality fusion
date: "2022.06–2023.09"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: The framework of TransCDR
  focal_point: Smart
---

1. Used pre-trained models ChemBERTa and GIN, MLP to learn the drug’s structural information.
2. Applied MLP to learn multi-omics profiles of cell lines.
3. Fused multimodal features based on multi-head attention mechanisms. 
4. Transfer learning improves the model’s generalization to predict drug cell line response (IC50). 