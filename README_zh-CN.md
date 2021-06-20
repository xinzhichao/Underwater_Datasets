# 水下场景数据集 Underwater Datasets  

 [![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE) [![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)

[English](README.md) | 简体中文

本仓库主要用来整理水下场景的数据集，尽可能详细的包含现有开源的水下数据集，如果您发现您知道的开源的水下数据集没有包含在我们的仓库中，并且如果您愿意分享它，您可以提一个issues方便我们将数据集进行添加，或者通过邮箱和我们进行联系：

@xinzhichao xinzhichao@stu.ouc.edu.cn. 

@liuxiaoyan 

- - -
- - -
## 1.Underwater Datasets(no depth)

**此部分的水下场景数据集不包含图像对应的深度图**

- **EUVP dataset**
  - EUVP dataset：  [EUVP dataset](http://irvlab.cs.umn.edu/resources/euvp-dataset)
  - Paper： [Fast Underwater Image Enhancement for Improved Visual Perception](https://ieeexplore.ieee.org/document/9001231)
  - Code：[Github](https://github.com/xahidbuffon/FUnIE-GAN)
    - 数据集介绍

- **underwater_imagenet dataset**
  - Underwater_imagenet dataset： [Underwater_imagenet](https://drive.google.com/file/d/1LOM-2A1BSLaFjCY2EEK3DA2Lo37rNw-7/view)
  - Paper： [Enhancing Underwater Imagery using Generative Adversarial Networks(UGAN)](https://arxiv.org/abs/1801.04011)
  - Code：[Github](https://github.com/cameronfabbri/Underwater-Color-Correction)
    - 数据集介绍


- **UIEBD dataset**
  - UIEBD dataset 
    - [UIEB Raws](https://drive.google.com/file/d/12W_kkblc2Vryb9zHQ6BfGQ_NKUfXYk13/view) 
    - [UIEB References](https://drive.google.com/file/d/1cA-8CzajnVEL4feBRKdBxjEe6hwql6Z7/view)
  - Paper： [An Underwater Image Enhancement Benchmark Dataset and Beyond(Water-Net)](https://arxiv.org/pdf/1901.05495.pdf)
  - Homepage：[Homepage](https://li-chongyi.github.io/proj_benchmark.html) 
  - 数据集介绍：详细数据集介绍请查看作者官方的Homepage，需要注意的是这个数据集是用来进行水下图像复原的，所以提供了成对的两个数据集，一个为raw一个为对应的标签数据集references。

- **SUIM dataset**
  - SUIM dataset [SUIM dataset](https://drive.google.com/drive/folders/10KMK0rNB43V2g30NcA1RYipL535DuZ-h) 
  - Paper： [Semantic Segmentation of Underwater Imagery: Dataset and Benchmark](https://arxiv.org/pdf/2004.01241.pdf)
  - Homepage：[Homepage](http://irvlab.cs.umn.edu/resources/suim-dataset) 
  - 数据集介绍：
  此数据集是水下分割数据集，包含已经标注好的分割标签，对于数据集的详细介绍请看Homepage的详细介绍。

- **RUIE benchmark dataset**
  - RUIE benchmark dataset [RUIE benchmark dataset](https://github.com/dlut-dimt/Realworld-Underwater-Image-Enhancement-RUIE-Benchmark) 
  - Paper： [Real-world Underwater Enhancement: Challenges, Benchmarks, and Solutions(RUIE-Net)](https://arxiv.org/abs/1901.05320) 
  - 数据集介绍：

- **U-45 dataset**
  - U-45 dataset [U-45 dataset](https://github.com/IPNUISTlegal/underwater-test-dataset-U45-) 
  - Paper： [A Fusion Adversarial Underwater Image Enhancement Network with a Public Test Dataset](https://arxiv.org/abs/1906.06819) 
  - 数据集介绍：
  
- **Water-GAN dataset**
  - Water-GAN dataset [Water-GAN dataset](https://github.com/kskin/data) 
  - Paper： [WaterGAN: Unsupervised Generative Network to Enable Real-time Color Correction of Monocular Underwater Images](https://arxiv.org/abs/1702.07392) 
  - Code：[Github](https://github.com/kskin/WaterGAN/)
  - 数据集介绍：

- **SQUID dataset**
  - SQUID dataset [SQUID dataset](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html) 
  - Paper： [Underwater Single Image Color Restoration Using Haze-Lines and a New Quantitative Dataset](https://arxiv.org/abs/1811.01343) 
  - Code：[Github](https://github.com/danaberman/underwater-hl)
  - 数据集介绍：

- **Virtual periscope dataset**
  - Virtual periscope dataset [Virtual periscope dataset](http://webee.technion.ac.il/~yoav/research/random_distort.html) 
  - Paper： [Triangulation in Random Refractive Distortions](https://ieeexplore.ieee.org/abstract/document/7448905) 
  - 数据集介绍：

- **Color correction dataset**
  - Color correction dataset [Color correction dataset](https://web.whoi.edu/singh/underwater-imaging/datasets/color-correction/) 
  - 数据集介绍：

- **Color restoration dataset**
  - Data: [Color restoration dataset](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html) 
  - Paper： [Underwater Single Image Color Restoration Using Haze-Lines and a New Quantitative Datasett](https://arxiv.org/abs/1811.01343) 
  - Code：[Github](https://github.com/danaberman/underwater-hl)
  - 数据集介绍：

- **TURBID dataset**
  - Data: [TURBID dataset](http://amandaduarte.com.br/turbid/) 
  - Paper： [A dataset to evaluate underwater image restoration methods](https://ieeexplore.ieee.org/abstract/document/7485524) 
  - 数据集介绍：
- **OceanDark dataset**
  - Data: [OceanDark dataset](https://sites.google.com/view/oceandark/home) 
  - Paper： [A Contrast-Guided Approach for the Enhancement of Low-Lighting Underwater Images](https://www.mdpi.com/2313-433X/5/10/79) 
  - 数据集介绍：
- - -
## 2.Underwater Datasets(include depth)
**此部分的水下场景数据集包含图像对应的深度图**
- **Sea-thru dataset**
  - Sea-thru dataset： [Sea-thru](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/sea_thru/index.html) 
  - Paper： [A Method For Removing Water From Underwater Images](http://csms.haifa.ac.il/profiles/tTreibitz/webfiles/sea-thru_cvpr2019.pdf)
  - Homepage：[Homepage](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/sea_thru/index.html) 
    - 数据集介绍

- - -

## Contributing (欢迎参与贡献)

If you are interested in contributing, please contact us by email.

- - -

### Copyright notice

> ***[文章版权声明]这个仓库可以遵守相关的开源协议进行使用。这个仓库中包含有很多研究者的论文、硕博士论文等，都来源于在网上的下载，仅作为学术研究使用。这些文章的版权属于相应的出版社。如果作者或出版社有异议，请联系我进行删除。一切都是为了更好地学术！***

