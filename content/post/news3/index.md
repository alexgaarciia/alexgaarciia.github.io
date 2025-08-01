---
title: "From GANs to the Leaning Tower: Our Paper Goes to ONDM 2025"
summary: Our latest research paper has been accepted at ONDM 2025 in Pisa! 
date: 2023-10-25
authors:
  - admin
# tags:
#   - Hugo
#   - Hugo Blox
#   - Markdown
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

I'm excited to share that our new research paper has been accepted for presentation at the 2025 International Conference on Optical Network Design and Modeling (ONDM), held this year in Pisa.

This work explores the use of Conditional Tabular GANs (CTGANs) to generate synthetic traffic matrices for wide area networks, enabling more flexible and realistic simulation environments in network research.

### TL;DR

In this work, we investigate whether synthetic traffic data — generated using GAN-based models — can be used as a reliable substitute for real network measurements in large-scale simulations. We compare a custom-built GAN and an off-the-shelf CTGAN from the SDV library, both trained on traffic matrices from the Abilene topology, rescaled to 2025 demand levels.

We evaluate the synthetic data on statistical similarity metrics (achieving over 80% quality scores) and test its realism by analyzing link load behavior in simulated topologies. While both models produce high-quality results, CTGANs outperform in preserving statistical structure and generating more balanced traffic. 

### Links to paper and code

You can find both the paper and the code open to the research community:

📄 **Paper**: [CTGANs for Generating Synthetic Traffic Matrices in Wide Area Networks](https://ieeexplore.ieee.org/document/11029340)

💻 **Code repository**: [SyntheticTrafficRouting](https://github.com/alexgaarciia/SyntheticTrafficRouting) on GitHub
