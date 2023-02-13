---
title: 'Finding Nano-Ötzi: Semi-Supervised Volume Visualization for Cryo-Electron Tomography'
collection: publications
permalink: /nano-oetzi
author: Dominik Engel
paperauthors: 'Ngan Nguyen*, Ciril Bohak*, <b>Dominik Engel</b>, Peter Mindek, Ondřej Strnad, Peter Wonka, Sai Li, Timo Ropinski, Ivan Viola'
sharedfirst: true
venue: 'IEEE Transactions on Visualization and Computer Graphics'
citation: 'Ngan Nguyen et al.: "Finding Nano-Ötzi: Semi-Supervised Volume Visualization for Cryo-Electron Tomography"in <i>IEEE Transactions on Visualization and Computer Graphics</i> (2022).'
code: "https://github.com/nanovis/nano-oetzi"
paperurl: "https://ieeexplore.ieee.org/document/9806341"
preprint: "https://arxiv.org/abs/2104.01554"
---


![Nano-Oetzi Teaser](images/nano-oetzi-teaser.png)

### Abstract
Cryo-Electron Tomography (cryo-ET) is a new 3D imaging technique with unprecedented potential for resolving submicron structural detail. Existing volume visualization methods, however, cannot cope with its very low signal-to-noise ratio. In order to design more powerful transfer functions, we propose to leverage soft segmentation as an explicit component of visualization for noisy volumes. Our technical realization is based on semi-supervised learning where we combine the advantages of two segmentation algorithms. A first weak segmentation algorithm provides good results for propagating sparse user provided labels to other voxels in the same volume. This weak segmentation algorithm is used to generate dense pseudo labels. A second powerful deep-learning based segmentation algorithm can learn from these pseudo labels to generalize the segmentation to other unseen volumes, a task that the weak segmentation algorithm fails at completely. The proposed volume visualization uses the deep-learning based segmentation as a component for segmentation-aware transfer function design. Appropriate ramp parameters can be suggested automatically through histogram analysis. Finally, our visualization uses gradient-free ambient occlusion shading to further suppress visual presence of noise, and to give structural detail desired prominence. The cryo-ET data studied throughout our technical experiments is based on the highest-quality tilted series of intact SARS-CoV-2 virions. Our technique shows the high impact in target sciences for visual data analysis of very noisy volumes that cannot be visualized with existing techniques.

### [Paper](https://ieeexplore.ieee.org/document/9806341)
### [Open Access Preprint](https://arxiv.org/abs/2104.01554)
### [Code](https://github.com/nanovis/nano-oetzi)

### Citation

```bibtex
@article{nguyen2021nano-oetzi,
  title={Finding Nano-\"Otzi: Semi-Supervised Volume Visualization for Cryo-Electron Tomography},
  author={Ngan Nguyen and Ciril Bohak and Dominik Engel and Peter Mindek and Ondřej Strnad and Peter Wonka and Sai Li and Timo Ropinski and Ivan Viola},
  year={2022},
  doi={10.1109/TVCG.2022.3186146}
}
```
