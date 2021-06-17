---
title: 'Finding Nano-Ötzi: Semi-Supervised Volume Visualization for Cryo-Electron Tomography'
collection: publications
permalink: /nano-oetzi
excerpt: 'Automatic visualization of Cryo-ET data using deep learning based 3D segmentation'
author: Dominik Engel
venue: 'arXiv (under review)'
citation: 'Nguyen, Ngan et al.'
code: ""
paperurl: "https://arxiv.org/abs/2104.01554"
preprint: ""
---


![DVAO Teaser](images/nano-oetzi-teaser.png)

### Abstract
Cryo-Electron Tomography (cryo-ET) is a new 3D imaging technique with unprecedented potential for resolving submicron structural detail. Existing volume visualization methods, however, cannot cope with its very low signal-to-noise ratio. In order to design more powerful transfer functions, we propose to leverage soft segmentation as an explicit component of visualization for noisy volumes. Our technical realization is based on semi-supervised learning where we combine the advantages of two segmentation algorithms. A first weak segmentation algorithm provides good results for propagating sparse user provided labels to other voxels in the same volume. This weak segmentation algorithm is used to generate dense pseudo labels. A second powerful deep-learning based segmentation algorithm can learn from these pseudo labels to generalize the segmentation to other unseen volumes, a task that the weak segmentation algorithm fails at completely. The proposed volume visualization uses the deep-learning based segmentation as a component for segmentation-aware transfer function design. Appropriate ramp parameters can be suggested automatically through histogram analysis. Finally, our visualization uses gradient-free ambient occlusion shading to further suppress visual presence of noise, and to give structural detail desired prominence. The cryo-ET data studied throughout our technical experiments is based on the highest-quality tilted series of intact SARS-CoV-2 virions. Our technique shows the high impact in target sciences for visual data analysis of very noisy volumes that cannot be visualized with existing techniques.

### Paper
currently under review
### [Open Access Preprint](https://arxiv.org/abs/2104.01554)
### Code
released upon acceptance

### Citation

```bibtex
@article{nguyen2021nano-oetzi,
  title={Finding Nano-\"Otzi: Semi-Supervised Volume Visualization for Cryo-Electron Tomography},
  author={Ngan Nguyen and Ciril Bohak and Dominik Engel and Peter Mindek and Ondřej Strnad and Peter Wonka and Sai Li and Timo Ropinski and Ivan Viola},
  year={2021},
  eprint={2104.01554},
  archivePrefix={arXiv},
}
```
