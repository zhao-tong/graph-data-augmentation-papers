## Graph Data Augmentation Papers

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/zhao-tong/graph-data-augmentation-papers?color=yellow)  ![Forks](https://img.shields.io/github/forks/zhao-tong/graph-data-augmentation-papers?color=blue&label=Fork)

This repository contains a list of papers on the **Graph Data Augmentation**, we categorize them based on their learning objectives and tasks.

We will try to make this list updated. If you found any error or any missed paper, please don't hesitate to open an issue or pull request.

## Materials

### Survey Paper

[**Graph Data Augmentation for Graph Machine Learning: A Survey**](https://arxiv.org/pdf/2202.08871.pdf). 

[Tong Zhao](https://tzhao.io/), [Wei Jin](http://cse.msu.edu/~jinwei2/), [Yozen Liu](https://scholar.google.com/citations?user=i3U2JjEAAAAJ&hl=en&authuser=2), [Yingheng Wang](https://isjakewong.github.io/), [Gang Liu](https://liugangcode.github.io/), [Stephan Günneman](https://www.in.tum.de/daml/team/guennemann/), [Neil Shah](https://nshah.net/), and [Meng Jiang](http://www.meng-jiang.com/).

#### If you find this repository helpful for your work, please kindly cite our paper.

```bibtex
@article{zhao2022graph,
  title={Graph Data Augmentation for Graph Machine Learning: A Survey},
  author={Zhao, Tong and Jin, Wei and Liu, Yozen and Wang, Yingheng and Liu, Gang and Günneman, Stephan and Shah, Neil and Jiang, Meng},
  journal={IEEE Data Engineering Bulletin},
  year={2023}
}
```

### Tutorials

- SDM 2023: [Augmentation Methods for Graph Learning](https://github.com/zhao-tong/SDM2023_Graph_Data_Augmentation_Tutorial)

## Graph data augmentation for (semi-)supervised learning

### Node-level tasks

* **Half-Hop: a Graph Upsampling Approach for Slowing Down Message Passing**, in *ICML* 2023. [\[pdf\]](https://openreview.net/pdf?id=lXczFIwQkv)

* **Local Augmentation for Graph Neural Networks**, in *ICML* 2022. [\[pdf\]](https://arxiv.org/pdf/2109.03856.pdf)

* **Training Robust Graph Neural Networks with Topology Adaptive Edge Dropping**, in *arXiv* 2021. [\[pdf\]](https://arxiv.org/pdf/2106.02892.pdf)

* **FairDrop: Biased Edge Dropout for Enhancing Fairness in Graph Representation Learning**, in *arXiv* 2021. [\[pdf\]](https://arxiv.org/pdf/2104.14210.pdf) [\[code\]](https://github.com/ispamm/FairDrop)

* **Topological Regularization for Graph Neural Networks Augmentation**, in *arXiv* 2021. [\[pdf\]](https://arxiv.org/pdf/2104.02478.pdf)

* **Semi-Supervised and Self-Supervised Classification with Multi-View Graph Neural Networks**, in *CIKM* 2021. [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3459637.3482477)

* **Metropolis-Hastings Data Augmentation for Graph Neural Networks**, in *NeurIPS* 2021. [\[pdf\]](https://proceedings.neurips.cc/paper/2021/file/9e7ba617ad9e69b39bd0c29335b79629-Paper.pdf)

* **Action Sequence Augmentation for Early Graph-based Anomaly Detection**, in *CIKM* 2021. [\[pdf\]](https://arxiv.org/pdf/2010.10016.pdf) [\[code\]](https://github.com/DM2-ND/Eland)

* **Data Augmentation for Graph Neural Networks**, in *AAAI* 2021. [\[pdf\]](https://www.aaai.org/AAAI21Papers/AAAI-10012.ZhaoT.pdf) [\[code\]](https://github.com/zhao-tong/GAug)

* **Automated Graph Representation Learning for Node Classification**, in *IJCNN* 2021. [\[pdf\]](https://ieeexplore.ieee.org/document/9533811)

* **Mixup for Node and Graph Classification**, in *The WebConf* 2021. [\[pdf\]](https://wangywust.github.io/Paper/2021mix.pdf)  [\[code\]](https://github.com/vanoracai/MixupForGraph)

* **Heterogeneous Graph Neural Network via Attribute Completion**, in *The WebConf* 2021. [\[pdf\]](https://dl.acm.org/doi/abs/10.1145/3442381.3449914)

* **FLAG: Adversarial Data Augmentation for Graph Neural Networks**, in *arXiv* 2020. [\[pdf\]](https://arxiv.org/pdf/2010.09891.pdf) [\[code\]](https://github.com/devnkong/FLAG)

* **GraphMix: Improved Training of GNNs for Semi-Supervised Learning**, in *arXiv* 2020. [\[pdf\]](https://arxiv.org/pdf/1909.11715.pdf) [\[code\]](https://github.com/vikasverma1077/GraphMix)

* **Robust Graph Representation Learning via Neural Sparsification**, in *ICML* 2020. [\[pdf\]](http://proceedings.mlr.press/v119/zheng20d/zheng20d.pdf)

* **DropEdge: Towards Deep Graph Convolutional Networks on Node Classification**, in *ICLR* 2020. [\[pdf\]](https://openreview.net/pdf?id=Hkx1qkrKPr) [\[code\]](https://github.com/DropEdge/DropEdge)

* **Graph Structure Learning for Robust Graph Neural Networks**, in *KDD* 2020. [\[pdf\]](https://arxiv.org/pdf/2005.10203.pdf) [\[code\]](https://github.com/ChandlerBang/Pro-GNN)

* **Measuring and Relieving the Over-smoothing Problem for Graph Neural Networks from the Topological View**, in *AAAI* 2020. [\[pdf\]](https://arxiv.org/pdf/1909.03211.pdf)

* **Diffusion Improves Graph Learning**, in *NeurIPS* 2019. [\[pdf\]](https://proceedings.neurips.cc/paper/2019/file/23c894276a2c5a16470e6a31f4618d73-Paper.pdf) [\[code\]](https://github.com/klicperajo/gdc)

### Graph-level tasks

* **Data-Centric Learning from Unlabeled Graphs with Diffusion Model**, in *NeurIPS* 2023. [\[pdf\]](https://arxiv.org/pdf/2303.10108.pdf) [\[code\]](https://github.com/liugangcode/data_centric_transfer)

* **Automated Data Augmentations for Graph Classification**, in *ICLR* 2023. [\[pdf\]](https://arxiv.org/pdf/2202.13248.pdf)

* **Semi-Supervised Graph Imbalanced Regression**, in *KDD* 2023. [\[pdf\]](https://arxiv.org/pdf/2305.12087.pdf) [\[code\]](https://github.com/liugangcode/SGIR)

* **G-Mixup: Graph Data Augmentation for Graph Classification**, in *ICML* 2022. [\[pdf\]](https://arxiv.org/pdf/2202.07179.pdf) [\[code\]](https://github.com/ahxt/g-mixup)

* **Graph Rationalization with Environment-based Augmentations**, in *KDD* 2022. [\[pdf\]](https://arxiv.org/pdf/2206.02886.pdf) [\[code\]](https://github.com/liugangcode/GREA)

* **Graph Augmentation Learning**, in *arXiv* 2022. [\[pdf\]](https://arxiv.org/pdf/2203.09020)

* **GAMS: Graph Augmentation with Module Swapping**, in *arXiv* 2022. [\[pdf\]](https://www.scitepress.org/Papers/2022/108224/108224.pdf)

* **Graph Transplant: Node Saliency-Guided Graph Mixup with Local Structure Preservation**, in *AAAI* 2022. [\[pdf\]](https://arxiv.org/pdf/2111.05639.pdf)

* **ifMixup: Towards Intrusion-Free Graph Mixup for Graph Classification**, in *arXiv*, 2021. [\[pdf\]](https://arxiv.org/pdf/2110.09344.pdf)

* **Mixup for Node and Graph Classification**, in *The WebConf* 2021. [\[pdf\]](https://wangywust.github.io/Paper/2021mix.pdf)  [\[code\]](https://github.com/vanoracai/MixupForGraph)

* **MoCL: Data-driven Molecular Fingerprint via Knowledge-aware Contrastive Learning from Molecular Graph**, in *KDD* 2021. [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467186)  [\[code\]](https://github.com/illidanlab/MoCL-DK)

* **FLAG: Adversarial Data Augmentation for Graph Neural Networks**, in *arXiv* 2020. [\[pdf\]](https://arxiv.org/pdf/2010.09891.pdf) [\[code\]](https://github.com/devnkong/FLAG)

* **GraphCrop: Subgraph Cropping for Graph Classification**, in *arXiv* 2020. [\[pdf\]](https://arxiv.org/pdf/2009.10564.pdf)

* **M-Evolve: Structural-Mapping-Based Data Augmentation for Graph Classification**, in *CIKM* 2020 [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3340531.3412086) and *IEEE TNSE* 2021. [\[pdf\]](https://arxiv.org/pdf/2007.05700.pdf)

### Edge-level tasks

* **Knowledge Graph Completion with Counterfactual Augmentation**, in *TheWebConf* 2023. [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3543507.3583401)

* **Learning from Counterfactual Links for Link Prediction**, in *ICML* 2022. [\[pdf\]](https://arxiv.org/pdf/2106.02172.pdf) [\[code\]](https://github.com/DM2-ND/CFLP)

* **Adaptive Data Augmentation on Temporal Graphs**, in *NeurIPS* 2021. [\[pdf\]](https://proceedings.neurips.cc/paper/2021/file/0b0b0994d12ad343511adfbfc364256e-Paper.pdf)

* **FLAG: Adversarial Data Augmentation for Graph Neural Networks**, in *arXiv* 2020. [\[pdf\]](https://arxiv.org/pdf/2010.09891.pdf) [\[code\]](https://github.com/devnkong/FLAG)

## Graph data augmentation with self-supervised learning objectives

### Contrastive learning

* **Spectral Augmentation for Self-Supervised Learning on Graphs**, in *ICLR* 2023. [\[pdf\]](https://arxiv.org/pdf/2210.00643.pdf)

* **Graph Self-supervised Learning with Accurate Discrepancy Learning**, in *NeurIPS* 2022. [\[pdf\]](https://proceedings.neurips.cc/paper_files/paper/2022/file/5b175f9e93873e3a10a6ce43dbb82e05-Paper-Conference.pdf) [\[code\]](https://github.com/DongkiKim95/D-SLA)

* **Augmentations in Hypergraph Contrastive Learning: Fabricated and Generative**, in *NeurIPS* 2022. [\[code\]](https://github.com/weitianxin/HyperGCL)

* **Learning Graph Augmentations to Learn Graph Representations**, in *arXiv* 2022. [\[pdf\]](https://arxiv.org/pdf/2201.09830.pdf) [\[code\]](https://github.com/kavehhassani/lg2ar)

* **Fair Node Representation Learning via Adaptive Data Augmentation**, in *arXiv* 2022. [\[pdf\]](https://arxiv.org/pdf/2201.08549.pdf)

* **Large-Scale Representation Learning on Graphs via Bootstrapping**, in *ICLR* 2022. [\[pdf\]](https://arxiv.org/pdf/2102.06514.pdf) [\[code\]](https://github.com/Namkyeong/BGRL_Pytorch)

* **Augmentations in Graph Contrastive Learning: Current Methodological Flaws & Towards Better Practices**, in *The WebConf* 2022. [\[pdf\]](https://arxiv.org/pdf/2111.03220.pdf)

* **Contrastive Self-supervised Sequential Recommendation with Robust Augmentation**, in *arXiv* 2021. [\[pdf\]](https://arxiv.org/pdf/2108.06479.pdf)

* **Collaborative Graph Contrastive Learning: Data Augmentation Composition May Not be Necessary for Graph Representation Learning**, in *arXiv* 2021. [\[pdf\]](https://arxiv.org/pdf/2111.03262.pdf)

* **Molecular Graph Contrastive Learning with Parameterized Explainable Augmentations**, in *BIBM* 2021. [\[pdf\]](https://www.biorxiv.org/content/10.1101/2021.12.03.471150v1.full.pdf)

* **Self-Supervised GNN that Jointly Learns to Augment**, in *NeurIPS Workshop* 2021. [\[pdf\]](https://www.researchgate.net/profile/Zekarias-Kefato/publication/356997993_Self-Supervised_GNN_that_Jointly_Learns_to_Augment/links/61b75d88a6251b553ab64ff4/Self-Supervised-GNN-that-Jointly-Learns-to-Augment.pdf)

* **InfoGCL: Information-Aware Graph Contrastive Learning**, in *NeurIPS* 2021. [\[pdf\]](https://proceedings.neurips.cc/paper/2021/file/ff1e68e74c6b16a1a7b5d958b95e120c-Paper.pdf)

* **Adversarial Graph Augmentation to Improve Graph Contrastive Learning**, in *NeurIPS* 2021. [\[pdf\]](https://proceedings.neurips.cc/paper/2021/file/854f1fb6f65734d9e49f708d6cd84ad6-Paper.pdf) [\[code\]](https://github.com/susheels/adgcl)

* **Graph Contrastive Learning with Adaptive Augmentation**, in *The WebConf* 2021. [\[pdf\]](https://arxiv.org/pdf/2010.14945.pdf) [\[code\]](https://github.com/CRIPAC-DIG/GCA)

* **Semi-Supervised and Self-Supervised Classification with Multi-View Graph Neural Networks**, in *CIKM* 2021. [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3459637.3482477)

* **Graph Contrastive Learning Automated**, in *ICML* 2021. [\[pdf\]](https://arxiv.org/pdf/2106.07594.pdf) [\[code\]](https://github.com/Shen-Lab/GraphCL_Automated)

* **Graph Data Augmentation based on Adaptive Graph Convolution for Skeleton-based Action Recognition**, in *ICCSNT* 2021. [\[pdf\]](https://ieeexplore.ieee.org/abstract/document/9615451)

* **Sub-graph Contrast for Scalable Self-Supervised Graph Representation Learning**, in *ICDM* 2020. [\[pdf\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9338425) [\[code\]](https://github.com/yzjiao/Subg-Con)

* **Contrastive Multi-View Representation Learning on Graphs**, in *ICML* 2020. [\[pdf\]](https://arxiv.org/pdf/2006.05582.pdf) [\[code\]](https://github.com/kavehhassani/mvgrl)

* **Graph Contrastive Learning with Augmentations**, in *NeurIPS* 2020. [\[pdf\]](https://proceedings.neurips.cc/paper/2020/file/3fe230348e9a12c13120749e3f9fa4cd-Paper.pdf) [\[code\]](https://github.com/Shen-Lab/GraphCL)

* **Deep Graph Contrastive Representation Learning**, in *GRL+ Workshop @ICML* 2020. [\[pdf\]](https://arxiv.org/pdf/2006.04131.pdf) [\[code\]](https://github.com/CRIPAC-DIG/GRACE)

* **Deep Graph Infomax**, in *ICLR* 2019. [\[pdf\]](https://arxiv.org/pdf/1809.10341.pdf) [\[code\]](https://github.com/PetarV-/DGI)

### Consistency learning

* **NodeAug: Semi-Supervised Node Classification with Data Augmentation**, in *KDD* 2020. [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403063)

* **Graph Random Neural Network for Semi-Supervised Learning on Graphs**, in *NeurIPS* 2020. [\[pdf\]](https://proceedings.neurips.cc/paper/2020/file/fb4c835feb0a65cc39739320d7a51c02-Paper.pdf) [\[code\]](https://github.com/THUDM/GRAND)

## Acknowledgement

This page is contributed and maintained by [Tong Zhao](https://tzhao.io/) (tzhao2@nd.edu), [Gang Liu](https://scholar.google.com/citations?hl=en&user=zdF3vTYAAAAJ) (gliu7@nd.edu), and [Yingheng Wang](https://isjakewong.github.io/) (jakewyh@163.com).
