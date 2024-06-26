
<!-- <p align="center">
  <img src="docs/figs/logo.png" align="center" width="50%"> -->
  
  <h3 align="center"><strong>HA-Bins: Hierarchical Adaptive Bins for Robust Monocular Depth Estimation across Multiple Datasets</strong></h3>

  <p align="center">
    <a href="https://ruijiezhu94.github.io/ruijiezhu/">Ruijie Zhu</a>,</span>
    <a href="https://indu1ge.github.io/ziyangsong">Ziyang Song</a>,</span>
    <a href="https://github.com/lliu00">Li Liu</a>,
    <a href="https://github.com/Hevans123">Jianfeng He</a>,    <br>
    <a href="http://staff.ustc.edu.cn/~tzzhang/">Tianzhu Zhang</a><sup>*</sup>,
    <a href="https://dblp.org/pid/z/YongdongZhang.html">Yongdong Zhang</a>,
    <br>
    <sup>*</sup>Corresponding author.
    <br>
    Deep Space Exploration Laboratory/School of Information Science and Technology,
    <br>
    University of Science and Technology of China
    <br>
    <b>Accepted by TCSVT 2023</b>

</p>

<div align="center">
 <a href='https://ieeexplore.ieee.org/document/10325550'><img src='https://img.shields.io/badge/Paper-TCSVT-red'></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<!-- <a href='https://arxiv.org/abs/[]'><img src='https://img.shields.io/badge/arXiv-[]-b31b1b.svg'></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -->
 <a href='https://ruijiezhu94.github.io/HABins_TCSVT2023/'><img src='https://img.shields.io/badge/Project-Page-Green'></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <a href='https://github.com/RuijieZhu94/HABins?tab=Apache-2.0-1-ov-file'><img src='https://img.shields.io/badge/License-Apache 2.0-blue'></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

</div>


<p align="center">
<img src="assets/teaser.jpg" width="97%"/>
</p>

> Robust depth estimation by proposed hierarchical adaptive bins. Top: Input RGB Image from multiple datasets. Middle: Depth maps predicted by our model. Bottom: The cumulative probabilities on depth bins (bars) and the depth distribution of ground truth (splines). Note that we use the same parameters and weights of the model to predict the depth values of these images.

## News
- **27 Nov. 2023**: The [**project website**](https://ruijiezhu94.github.io/HABins_TCSVT2023/) was released.
- **14 Nov. 2023**: The extended paper [HA-Bins](https://ieeexplore.ieee.org/document/10325550) was accepted by **TCSVT 2023**. 
- **23 Oct. 2022**: We won **the second place**🥈 (MixBins_RVC) on Monocular Depth Estimation track in ECCV2022 workshop: [Robust Vision Challenge 2022](http://www.robustvision.net/leaderboard.php?benchmark=depth).


## Installation

Please refer to [get_started.md](docs/get_started.md#installation) for installation and [dataset_prepare.md](docs/dataset_prepare.md#prepare-datasets) for dataset preparation.

## Training and Inference

We provide [train.md](docs/train.md) and [inference.md](docs/inference.md) for the instruction of training and inference. 


## Bibtex

If you like our work and use the codebase or models for your research, please cite our work as follows.

```
@ARTICLE{zhu2023habins,
  author={Zhu, Ruijie and Song, Ziyang and Liu, Li and He, Jianfeng and Zhang, Tianzhu and Zhang, Yongdong},
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  title={HA-Bins: Hierarchical Adaptive Bins for Robust Monocular Depth Estimation Across Multiple Datasets}, 
  year={2024},
  volume={34},
  number={6},
  pages={4354-4366},
  doi={10.1109/TCSVT.2023.3335316}}
```

## Acknowledgment
This codabase is adapted from the [Monocular-Depth-Estimation-Toolbox](https://github.com/zhyever/Monocular-Depth-Estimation-Toolbox), an excellent depth estimation toolbox created by Zhenyu Li.
Please also consider citing it.

```
@misc{lidepthtoolbox2022,
  title={Monocular Depth Estimation Toolbox},
  author={Zhenyu Li},
  howpublished = {\url{https://github.com/zhyever/Monocular-Depth-Estimation-Toolbox}},
  year={2022}
}
```