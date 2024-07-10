---
title: CHIASM-Net: Artificial Intelligence-Based Direct Identification of Chiasmal Abnormalities in Albinism 
order: 50
image: chiasmnet.png
---

**Objective**: To establish a novel **Convolutional Neural Network (CNN)** capable of detecting congenital chiasmal malformations from anatomic MRI images of the brain \
**Data**:  T1-weighted brain images from [ABIDE](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4162310/), [CHIASM](https://www.nature.com/articles/s41597-021-01080-w), [COBRE](https://www.sciencedirect.com/science/article/pii/S1053811915004310?via%3Dihub), [HCP](https://www.humanconnectome.org/), [Mind-Brain-Body](https://pubmed.ncbi.nlm.nih.gov/30747911/), [MCIC](https://link.springer.com/article/10.1007/s12021-013-9184-3) datasets and neuroimaging data from study by [Ather et al.](https://onlinelibrary.wiley.com/doi/epdf/10.1002/hbm.24411), for a total of 32 MRI brain images of People with Albinism (PWA) and 1708 brain images from control group. \
**Methods**:  Deep Learning, Convolutional Neural Networks, Pytorch, TorchIO, U-Net, Explainable AI (XAI) \
**Relevance**: This [scientific article](https://iovs.arvojournals.org/article.aspx?articleid=2792909) demonstrated that CNNs can be used to detect structural chiasmal abnormalities, as observed in human albinism, using T1-weighted MRI images. This opens a new chapter in albinism diagnostics, where the assessment of optic chiasm's integrity does not require functional tests. Additionally, the demonstrated approach can be applied retrospectively to already acquired anatomical MRI brain images for the purpose of albinism diagnostics, even if images were acquired for different purposes. \

### Overview

We investigated whether optic chiasm malformations associated with human albinism can be detected in MRI brain images. For this purpose we developed CHIASM-Net, a new AI tool, to detect optic chiasm abnormalities in the anatomica MRI images of the brain. CHIASM-Net was trained on MRI scans from 1,708 healthy individuals and 32 with albinism. It achieved 85% accuracy in identifying optic chiasm abnormalities. Our study shows CHIASM-Net's potential to enhance albinism diagnosis by analyzing MRI scans of the brain.

### Resources

- [Publication in Investigative Ophthalmology & Visual Science](https://iovs.arvojournals.org/article.aspx?articleid=2792909)
- [Code on Github](https://github.com/rjpuzniak/CHIASM-Net)