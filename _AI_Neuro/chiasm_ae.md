---
title: Deep Learning-Based Detection of Malformed Optic Chiasms From MRI Images
order: 20
image: chiasm_poc.jpg
---

**Objective**: To investigate whether Convolutional Neural Networks (CNNs) can detect structural differences between optic chiasms of controls and people with albinism (PWA) \
**Data**:  T1w MRI images from [CHIASM](https://www.nature.com/articles/s41597-021-01080-w) dataset (9 people with albinism, 9 controls) and [HCP](https://www.humanconnectome.org/) dataset (1065 controls) \
**Methods**:  Deep Learning, Convolutional Neural Networks, Pytorch, Autoencoders, TorchIO, U-Net \
**Relevance**: This [scientific article](https://www.frontiersin.org/articles/10.3389/fnins.2021.755785/full) demonstrated that optic nerve misrouting, as present in albinism, alters structural organization of the optic chiasm. Importantly, the resulting optic chiasm differences between controls and PWA can be detected with CNNs. This provides proof-of-concept for novel, anatomy-based method for albinism diagnostics.  

### Overview

We investigated if a Convolutional Neural Network (CNN) could help distinguish differences in optic chiasm between people with albinism (PWA) and controls. We trained the CNN to segment optic chiasm from T1-weighted image using images of healthy optic chiasm (coming from HCP dataset), and tested it on images of both controls and people with albinism (coming from CHIASM dataset). The CNN was able to accurately segment optic chiasm of controls, but performed significantly worse on people with albinism. Those results demonstrate that the CNN has potential to be used as a diagnostic tool for novel albinism diagnostics.

### Resources

- [Publication in Frontiers in Neuroscience](https://www.frontiersin.org/articles/10.3389/fnins.2021.755785/full)
- [Code on Github](https://github.com/rjpuzniak/Use-of-deep-learning-based-optic-chiasm-segmentation-for-investigating-visual-system-pathophysiology)
- [Weights of trained CNN](https://osf.io/4cvgq/)