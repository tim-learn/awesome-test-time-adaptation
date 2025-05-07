# Awesome Source-Free Domain Adaptation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome source-free domain adaptation resources. Your contributions are always welcome!

## Contents
- [Shallow Methods](#Shallow-Methods)
- [Image Classification](#Image-Classification)
- [Semantic Segmentation](#Semantic-Segmentation)
- [Object Detection](#Object-Detection)
- [Medical Image Analysis](#Medical-Image-Analysis)
- [Video Classification](#Video-Classification)
- [3D Perception](#3D-Perception)
- [Other CV Applications](#Other-CV-Applications)
- [Beyond CV Applications](#Beyond-CV-Applications)

## Shallow Methods
- `MCFA/ACM/TPA` [Chidlovskii and Orabona, Proc. KDD 2016] **Domain adaptation in the absence of source domain data** [[PDF]](https://dl.acm.org/doi/abs/10.1145/2939672.2939716) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9642892433162386910&hl=en)

- `TPAe` [Clinchant et al., Proc. ACL 2016] **Transductive adaptation of black box predictions** [[PDF]](https://aclanthology.org/P16-2.pdf#page=360) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16905965659974044730&hl=en)

- `RWA` [Van Laarhoven and Marchiori, arXiv 2017] **Unsupervised domain adaptation with random walks on target labelings** [[PDF]](https://arxiv.org/abs/1706.05335) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11439870750939669715&hl=en) [[CODE]](https://github.com/twanvl/rwa-da)

- `AOT` [Nelakurthi et al., Proc. IEEE BigData 2018] **Source free domain adaptation using an off-the-shelf classifier** [[PDF]](https://ieeexplore.ieee.org/abstract/document/8622112/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8692921854542396209&hl=en)

- `MCS` [Liang et al., Proc. CVPR 2019] **Distant supervised centroid shift: A simple and efficient approach to visual domain adaptation** [[PDF]](https://openaccess.thecvf.com/content_CVPR_2019/html/Liang_Distant_Supervised_Centroid_Shift_A_Simple_and_Efficient_Approach_to_CVPR_2019_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6967341548116354815&hl=en) [[CODE]](http://liangjian.xyz/publications.html)

## Image Classification
### 2020
- `SHOT` [Liang et al., Proc. ICML 2020] **Do we really need to access the source data? source hypothesis transfer for unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2002.08546) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2414062070271265691&hl=en) [[CODE]](https://github.com/tim-learn/SHOT)

- `3C-GAN` [Li et al., Proc. CVPR 2020] **Model adaptation: Unsupervised domain adaptation without source data** [[PDF]](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4357107695941200009&hl=en)

- `Inheritune` [Kundu et al., Proc. CVPR 2020] **Towards inheritable models for open-set domain adaptation** [[PDF]](https://openaccess.thecvf.com/content_CVPR_2020/html/Kundu_Towards_Inheritable_Models_for_Open-Set_Domain_Adaptation_CVPR_2020_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14243323555575752250&hl=en) [[CODE]](https://github.com/val-iisc/InheriTune)

- `USFDA` [Kundu et al., Proc. CVPR 2020] **Universal source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content_CVPR_2020/html/Kundu_Universal_Source-Free_Domain_Adaptation_CVPR_2020_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13396021133130094693&hl=en) [[CODE]](https://github.com/val-iisc/USFDA)

- `PLR` [Morerio et al., Proc. WACV 2020] **Generative pseudo-label refinement for unsupervised domain adaptation** [[PDF]](http://openaccess.thecvf.com/content_WACV_2020/html/Morerio_Generative_Pseudo-label_Refinement_for_Unsupervised_Domain_Adaptation_WACV_2020_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4003135053166172144&hl=en)

- `SFDA-TN` [Sahoo et al., Proc. ICML Workshops 2020] **Unsupervised domain adaptation in the absence of source data** [[PDF]](https://arxiv.org/abs/2007.10233) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5171753142766048896&hl=en)

  -------------------------------

- `PPDA` [Kim et al., IEEE SPL 2020] **Towards privacy-preserving domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9200758/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14085849752736504029&hl=en)

- `SFDA-IT` [Hou and Zheng, arXiv 2020] **Source free domain adaptation with image translation** [[PDF]](https://arxiv.org/abs/2008.07514) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8470634382170061837&hl=en)

- `UMSDE` [Zhang et al., arXiv 2020] **Unsupervised domain expansion from multiple sources** [[PDF]](https://arxiv.org/abs/2005.12544) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5634883974973094592&hl=en)

- `TAN` [ Xu and Kang, Misc 2020] **Transfer alignment network for double blind unsupervised domain adaptation** [[PDF]](https://openreview.net/forum?id=BJxGan4FPB) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5557302667401563514&hl=en)

### 2021
- `HCL` [Huang et al., Proc. NeurIPS 2021] **Model adaptation: Historical contrastive learning for unsupervised domain adaptation without source data** [[PDF]](https://proceedings.neurips.cc/paper/2021/hash/1dba5eed8838571e1c80af145184e515-Abstract.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10249665315417132625&hl=en) [[CODE]](https://github.com/jxhuang0508/HCL)

- `PCT` [Tanwisuth et al., Proc. NeurIPS 2021] **A prototype-oriented framework for unsupervised domain adaptation** [[PDF]](https://proceedings.neurips.cc/paper/2021/hash/8edd72158ccd2a879f79cb2538568fdc-Abstract.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13706347291358706428&hl=en) [[CODE]](https://github.com/korawat-tanwisuth/Proto_DA)

- `CAiDA` [Dong et al., Proc. NeurIPS 2021] **Confident anchor-induced multi-source free domain adaptation** [[PDF]](https://openreview.net/forum?id=EAdJEN8xKUl) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4891466716654628888&hl=en) [[CODE]](https://github.com/Learning-group123/CAiDA)

- `LDAuCID` [Rostami, Proc. NeurIPS 2021] **Lifelong domain adaptation via consolidated internal distribution** [[PDF]](https://openreview.net/forum?id=lpW-UP8VKcg) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12047996484572357152&hl=en) [[CODE]](https://openreview.net/forum?id=lpW-UP8VKcg)

- `NRC` [Yang et al., Proc. NeurIPS 2021] **Exploiting the intrinsic neighborhood structure for source-free domain adaptation** [[PDF]](https://proceedings.neurips.cc/paper/2021/hash/f5deaeeae1538fb6c45901d524ee2f98-Abstract.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10860760915812805775&hl=en) [[CODE]](https://github.com/Albert0147/NRC_SFDA)

- `TTT++` [Liu et al., Proc. NeurIPS 2021] **TTT++: When does self-supervised test-time training fail or thrive?** [[PDF]](https://openreview.net/forum?id=86NHK__yFDl) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3286823258483076490&hl=en) [[CODE]](https://github.com/vita-epfl/ttt-plus-plus)

- `SFIT` [Hou and Zheng, Proc. CVPR 2021] **Visualizing adapted knowledge in domain transfer** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Hou_Visualizing_Adapted_Knowledge_in_Domain_Transfer_CVPR_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8771147707141610474&hl=en) [[CODE]](https://github.com/hou-yz/DA_visualization)

- `A2Net` [Xia et al., Proc. CVPR 2021] **Adaptive adversarial network for source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/ICCV2021/html/Xia_Adaptive_Adversarial_Network_for_Source-Free_Domain_Adaptation_ICCV_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7800708115879678959&hl=en)

- `DECISION` [Ahmed et al., Proc. CVPR 2021] **Unsupervised multi-source domain adaptation without access to source data** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Ahmed_Unsupervised_Multi-Source_Domain_Adaptation_Without_Access_to_Source_Data_CVPR_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11084315308284943018&hl=en) [[CODE]](https://github.com/driptaRC/DECISION)

- `G-SFDA` [Yang et al., Proc. ICCV 2021] **Generalized source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/ICCV2021/html/Yang_Generalized_Source-Free_Domain_Adaptation_ICCV_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18251379567537933673&hl=en) [[CODE]](https://github.com/Albert0147/G-SFDA)

- `HDMI` [Lao et al., Proc. AAAI 2021] **Hypothesis disparity regularized mutual information maximization** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/17003) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16324456456194036739&hl=en)

- `CPGA` [Qiu et al., Proc. IJCAI 2021] **Source-free domain adaptation via avatar prototype generation and adaptation** [[PDF]](https://www.ijcai.org/proceedings/2021/0402.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17302653784932548129&hl=en) [[CODE]](https://github.com/SCUT-AILab/CPGA)

- `ISFDA` [Li et al., Proc. ACMMM 2021] **Imbalanced source-free domain adaptation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3474085.3475487) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8284461008656708496&hl=en) [[CODE]](https://github.com/LeoXinhaoLee/Imbalanced-Source-free-Domain-Adaptation)

- `IterLNL` [Zhang et al., Proc. BMVC 2021] **Unsupervised domain adaptation of black-box source models** [[PDF]](https://www.bmvc2021-virtualconference.com/assets/papers/0404.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8265289272342117214&hl=en) [[CODE]](https://github.com/zhjscut/IterLNL)

- `SSFT-SSD` [Yan et al., Proc. BMVC 2021] **Source-free unsupervised domain adaptation with surrogate data generation** [[PDF]](https://www.bmvc2021-virtualconference.com/assets/papers/1158.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15561996283559845579&hl=en)

- `SDDA` [Kurmi et al., Proc. WACV 2021] **Domain impression: A source data free domain adaptation method** [[PDF]](https://openaccess.thecvf.com/content/WACV2021/html/Kurmi_Domain_Impression_A_Source_Data_Free_Domain_Adaptation_Method_WACV_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5153719429923209992&hl=en) [[CODE]](https://github.com/DelTA-Lab-IITK/SFDA)

- `SoFA` [Yeh et al., Proc. WACV 2021] **SoFA: Source-data-free feature alignment for unsupervised domain adaptation** [[PDF]](http://openaccess.thecvf.com/content/WACV2021/html/Yeh_SoFA_Source-Data-Free_Feature_Alignment_for_Unsupervised_Domain_Adaptation_WACV_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6024511699668629047&hl=en)

- `GKD` [Tang et al., Proc. IROS 2021] **Model adaptation through hypothesis transfer with gradual knowledge distillation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9636206/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4710151422345198774&hl=en) [[CODE]](https://github.com/tntek/GKD)

- `ASL` [Yan et al., Proc. NeurIPS Workshops 2021] **Augmented self-labeling for source-free unsupervised domain adaptation** [[PDF]](https://openreview.net/forum?id=c_XaCsX3gtA) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17601533091925618087&hl=en)

- `ADV-M` [Wang et al., Proc. ICETIS 2021] **Providing domain specific model via universal no data exchange domain adaptation** [[PDF]](https://iopscience.iop.org/article/10.1088/1742-6596/1827/1/012154) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16220850660030806434&hl=en)

- `DECDA` [Zhu, Proc. DSIT 2021] **Source free domain adaptation by deep embedding clustering** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9674068/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5402817607572915157&hl=en)

  ------------------------------

- `SHOT++` [Liang et al., IEEE TPAMI 2021] **Source data-absent unsupervised domain adaptation through hypothesis transfer and labeling transfer** [[PDF]](https://arxiv.org/abs/2012.07297) [[G-Scholar]](https://scholar.google.com/scholar?cluster=182670772712263354&hl=en) [[CODE]](https://github.com/tim-learn/SHOT-plus)

- `DI` [Nayak et al., IEEE TPAMI 2021] **Mining data impressions from deep models as substitute for the unavailable training data** [[PDF]](https://arxiv.org/abs/2101.06069) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3306528190507440062&hl=en)

- `LA-VAE` [Yang et al., IEEE TIP 2021] **Model-induced generalization error bound for information-theoretic representation learning in source-data-free unsupervised domain adaptation** [[PDF]](https://ieeexplore.ieee.org/document/9640468) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7383037725836827645&hl=en)

- `OSHT-SC` [Feng et al., IEEE TIP 2021] **Open-set hypothesis transfer with semantic consistency** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9474954/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11598574187674894813&hl=en)

- `VDM-DA` [Tian et al., IEEE TCSVT 2021] **VDM-DA: Virtual domain modeling for source data-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9530705) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7229645414167343012&hl=en)

- `SFDA-APM` [Kim et al., IEEE TAI 2021] **Domain adaptation without source data** [[PDF]](https://arxiv.org/abs/2007.01524) [[G-Scholar]](https://scholar.google.com/scholar?cluster=68747551195247035&hl=en)

- `PIDM` [Ma et al., Knowledge-Based Systems 2022] **Source-free semi-supervised domain adaptation via progressive Mixup** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0950705122013041) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14288050700403813653&hl=en)
  
  ~~[Ma et al., arXiv 2021] **Uncertainty-guided mixup for semi-supervised domain adaptation without source data** [[PDF]](https://arxiv.org/abs/2107.06707)~~

- `TransDA` [Yang et al., Applied Intelligence 2022] **Self-training transformer for source-free domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s10489-022-04364-9) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14850892833711928431&hl=en) [[CODE]](https://github.com/ygjwd12345/TransDA)
  
  ~~[Yang et al., arXiv 2021] **Transformer-based source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2105.14138)~~

- `STDA` [Tian et al., Journal of Computer Science and Technology 2021] **Source-free unsupervised domain adaptation with sample transport learning** [[PDF]](https://link.springer.com/article/10.1007/s11390-021-1106-5) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9561134782602271879&hl=en)

- `OnTA` [Wang et al., arXiv 2021] **On-target adaptation** [[PDF]](https://arxiv.org/abs/2109.01087) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18422951738657247374&hl=en)

- `SFDA-MBNS` [Ishii and Sugiyama, arXiv 2021] **Source-free domain adaptation via distributional alignment by matching batch normalization statistics** [[PDF]](https://arxiv.org/abs/2101.10842) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14393126740179968632&hl=en)

- `N2DC-EX` [Tang et al., arXiv 2021] **Nearest neighborhood-based deep clustering for source data-absent unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2107.12585) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13195135963977220100&hl=en) [[CODE]](https://github.com/tntek/N2DCX)

- `BAIT` [Yang et al., arXiv 2021] **Casting a BAIT for offline and online source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2010.12427) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8008092994774409713&hl=en) [[CODE]](https://github.com/Albert0147/BAIT_SFUDA)

- `UMAD` [Liang et al., arXiv 2021] **UMAD: Universal model adaptation under domain and category shift** [[PDF]](https://arxiv.org/abs/2112.08553) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11487080011595938912&hl=en)

- `SMUDA` [Stan and Rostami, arXiv 2021] **Secure domain adaptation with multiple sources** [[PDF]](https://arxiv.org/abs/2106.12124) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9152141243814212262&hl=en)

- `UB2DA-ST` [Deng et al., arXiv 2021] **On universal black-box domain adaptation** [[PDF]](https://arxiv.org/abs/2104.04665) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11465604669722215123&hl=en) [[CODE]](https://github.com/Gorilla-Lab-SCUT/UB2DA)

- `USFDA-DAT` [Wu et al., arXiv 2021] **Domain adaptation without model transferring** [[PDF]](https://arxiv.org/abs/2107.10174) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4795862503178355859&hl=en)

- `CDL` [Wang et al., arXiv 2021] **Learning invariant representation with consistency and diversity for semi-supervised source hypothesis transfer** [[PDF]](https://arxiv.org/abs/2107.03008) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6313297467321181817&hl=en) [[CODE]](https://github.com/Wang-Xiaodong1899/SSHT)

### 2022
- `CoWA-JMDS` [Lee et al., Proc. ICML 2022] **Confidence score for source-free unsupervised domain adaptation** [[PDF]](https://proceedings.mlr.press/v162/lee22c.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10361966623265648313&hl=en) [[CODE]](https://github.com/Jhyun17/CoWA-JMDS)

- `SFDA-mixup` [Kundu et al., Proc. ICML 2022] **Balancing discriminability and transferability for source-free domain adaptation** [[PDF]](https://proceedings.mlr.press/v162/kundu22a.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9320809919166954591&hl=en)

- `AaD` [Yang et al., Proc. NeurIPS 2022] **Attracting and dispersing: A simple approach for source-free domain adaptation** [[PDF]](https://openreview.net/forum?id=ZlCpRiZN7n) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13477774754227861452&hl=en) [[CODE]](https://github.com/Albert0147/AaD_SFDA)

- `VMP` [Jing et al., Proc. NeurIPS 2022] **Variational model perturbation for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2210.10378) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11797225835673378824&hl=en) [[CODE]](https://openreview.net/forum?id=yTJze_xm-u6)

- `DaC` [Zhang et al., Proc. NeurIPS 2022] **Divide and contrast: Source-free domain adaptation via adaptive contrastive learning** [[PDF]](https://openreview.net/forum?id=NjImFaBEHl) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14836332941736923065&hl=en) [[CODE]](https://github.com/ZyeZhang/DaC)

- `BUFR` [Eastwood et al., Proc. ICLR 2022] **Source-free adaptation to measurement shift via bottom-up feature restoration** [[PDF]](https://openreview.net/forum?id=1JDiK_TbV4S) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13912921237099843796&hl=en) [[CODE]](https://github.com/cianeastwood/bufr)

- `DINE` [Liang et al., Proc. CVPR 2022] **DINE: Domain adaptation from single and multiple black-box predictors** [[PDF]](https://arxiv.org/abs/2104.01539) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16357483897421403796&hl=en) [[CODE]](https://github.com/tim-learn/DINE/)

- `SFDA-DE` [Ding et al., Proc. CVPR 2022] **Source-free domain adaptation via distribution estimation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022/html/Ding_Source-Free_Domain_Adaptation_via_Distribution_Estimation_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7701808491354120074&hl=en) [[CODE]](https://github.com/CvNoob/SFDA-DE)

- `AdaContrast` [Chen et al., Proc. CVPR 2022] **Contrastive test-time adaptation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022/html/Chen_Contrastive_Test-Time_Adaptation_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12033489108280591471&hl=en) [[CODE]](https://github.com/DianCh/AdaContrast)

- `DIPE` [Wang et al., Proc. CVPR 2022] **Exploring domain-invariant parameters for source free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_Exploring_Domain-Invariant_Parameters_for_Source_Free_Domain_Adaptation_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13696286332334056086&hl=en)

- `BMD` [Qu et al., Proc. ECCV 2022] **BMD: A general class-balanced multicentric dynamic prototype strategy for source-free domain adaptation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940161.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14638148510749193557&hl=en) [[CODE]](https://github.com/ispc-lab/BMD)

- `U-SFAN` [Roy et al., Proc. ECCV 2022] **Uncertainty-guided source-free domain adaptation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136850530.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10598112265751424023&hl=en) [[CODE]](https://github.com/roysubhankar/uncertainty-sfda)

- `KUDA` [Sun et al., Proc. ECCV 2022] **Prior knowledge guided unsupervised domain adaptation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930628.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16331707540385180374&hl=en) [[CODE]](https://github.com/tsun/KUDA)

- `StickerDA` [Kundu et al., Proc. ECCV 2022] **Concurrent subsidiary supervision for unsupervised source-free domain adaptation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136900177.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16781913863489916282&hl=en) [[CODE]](https://github.com/val-iisc/StickerDA)

- `D-MCD` [Chu et al., Proc. AAAI 2022] **Denoised maximum classifier discrepancy for source-free unsupervised domain adaptation** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/19925) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5829988423711925015&hl=en) 

- `ELPT` [Li et al., Proc. ACMMM 2022] **Source-free active domain adaptation via energy-based locality preserving transfer** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3503161.3548152) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4072134004192781743&hl=en)

- `PCSR` [Guan et al., Proc. BMVC 2022] **Polycentric clustering and structural regularization for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2210.07463) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10777900923119722899&hl=en) [[CODE]](https://github.com/Gxinuu/PCSR)

- `DMAPL` [Yan and Guo, Proc. BMVC 2022] **Dual moving average pseudo-labeling for source-free inductive domain adaptation** [[PDF]](https://bmvc2022.mpi-inf.mpg.de/0965.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15318503214717444323&hl=en) [[CODE]](https://github.com/cnyanhao/dmapl)

- `R-SFDA` [Agarwal et al., Proc. WACV 2022] **Unsupervised robust domain adaptation without source data** [[PDF]](https://openaccess.thecvf.com/content/WACV2022/html/Agarwal_Unsupervised_Robust_Domain_Adaptation_Without_Source_Data_WACV_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17077601123730740232&hl=en)

- `NEL` [Ahmed et al., Proc. WACV 2022] **Cleaning noisy labels by negative ensemble learning for source-free unsupervised domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/WACV2022/html/Ahmed_Cleaning_Noisy_Labels_by_Negative_Ensemble_Learning_for_Source-Free_Unsupervised_WACV_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17709195455145675886&hl=en)
  
  ~~[Ahmed et al., arXiv 2021] **Adaptive pseudo-label refinement by negative ensemble learning for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2103.15973)~~

- `VDB` [Yazdanpanah and Moradi, Proc. CVPR Workshops 2022] **Visual domain bridge: A source-free domain adaptation for cross-domain few-shot learning** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022W/FaDE-TCV/html/Yazdanpanah_Visual_Domain_Bridge_A_Source-Free_Domain_Adaptation_for_Cross-Domain_Few-Shot_CVPRW_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8987483615037403626&hl=en) [[CODE]](https://github.com/MosyMosy/VDB) 

- `PDA-MCD` [Bohdal et al., Proc. ECCV Workshops 2022] **Feed-forward source-free domain adaptation via class prototypes** [[PDF]](https://www.ood-cv.org/camera-ready/18/Feed_Forward_Source_Free_Domain_Adaptation_via_Class_Prototypes_ECCV_OOD_CV_Workshop.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3669131835455309637&hl=en)

- `SSNLL` [Chen et al., Proc. IROS 2022] **Self-supervised noisy label learning for source-free unsupervised domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9981099) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1592993425069201322&hl=en)

- `GAM` [Li et al., Proc. IJCNN 2022] **Source-free multi-domain adaptation with generally auxiliary model training** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9892718) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14752699554424187119&hl=en)

- `CSFA` [Yeh et al., Proc. ICPR 2022] **Boosting source-free domain adaptation via confidence-based subsets feature alignment** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9956719/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16791079764420455525&hl=en)

- `SFISA` [Zhang and Zhang, Proc. PRICAI 2022] **Source-free implicit semantic augmentation for domain adaptation** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-20865-2_2) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8767449916454723152&hl=en)

- `c-FeaGen` [Xu et al., Proc. IGARSS 2022] **Source-free domain adaptation for cross-scene hyperspectral image classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9883053/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11763446447548009309&hl=en)

- `DC-WSL` [Song et al., Proc. ICNSC 2022] **SS8: Source data-free domain adaptation via deep clustering with weighted self-labelling** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10004109) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6022749472723885436&hl=en)

- `SFDA-DML` [Zhang and Tian, Proc. ICCWAMTIP 2022] **Source-free unsupervised domain adaptation via denoising mutual learning** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10016534) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13564430841982713388&hl=en)

- `DEB` [Sun et al., Proc. DSIT 2022] **Source-free unsupervised domain adaptation in imbalanced datasets** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9943839/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2960885984579400313&hl=en) [[CODE]](https://github.com/zju-SWJ/DEB)

  -------------------------------

- `SCLM` [Tang et al., Neural Networks 2022] **Semantic consistency learning on manifold for source data-free unsupervised domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0893608022001897) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6192182099886884315&hl=en) [[CODE]](https://github.com/tntek/SCLM)

- `DEEM` [Ma et al., Neural Networks 2022] **Context-guided entropy minimization for semi-supervised domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0893608022002672) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11282923299185576921&hl=en) [[CODE]](https://github.com/NingMa-AI/DEEM)

- `CDCL` [Wang et al., IEEE TMM 2022] **Cross-domain contrastive learning for unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2106.05528) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12061580303029241170&hl=en)

- `SFUDA-TPS` [Tian et al., ACM TIST 2022] **Source-free unsupervised domain adaptation with trusted pseudo samples** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3570510) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15227982710957287262&hl=en)

- `RPL` [Rusak et al., TMLR 2022] **If your data distribution shifts, use self-learning** [[PDF]](https://openreview.net/forum?id=vqRzLv6POg) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5941215717305244351&hl=en) [[CODE]](https://github.com/bethgelab/robustness)

- `SAB` [Liu et al., IEEE SPL 2022] **Self-alignment for black-box domain adaptation of image classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9842332/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7062030827885381470&hl=en)

- `CdKD-TSML` [Li et al., Knowledge-Based Systems 2022] **Teacher-student mutual learning for efficient source-free unsupervised domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0950705122013004) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7125161896974350387&hl=en)

- `SFDA-ADT` [Liu et al., Applied Intelligence 2022] **A source free domain adaptation model based on adversarial learning for image classification** [[PDF]](https://link.springer.com/article/10.1007/s10489-022-04026-w) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17483889024275147966&hl=en)
  
  ~~[Liu et al., Proc. IJCNN 2022] **Source free domain adaptation via combined discriminative GAN model for image classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9891979/)~~

- `Prototype-DA` [Zhou et al., Neural Computing and Applications 2022] **Domain adaptation based on source category prototypes** [[PDF]](https://link.springer.com/article/10.1007/s00521-022-07601-x) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6719077136563993281&hl=en)

- `SFMBD` [Tian et al., Computers and Electrical Engineering 2022] **Source-free unsupervised domain adaptation with maintaining model balance and diversity** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0045790622006255) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7714251640306082635&hl=en)

- `LCCL` [Zhao et al., Sensors 2022] **Adaptive contrastive learning with label consistency for source data free unsupervised domain adaptation** [[PDF]](https://www.mdpi.com/1424-8220/22/11/4238) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11201330395391735486&hl=en)

- `JN` [Li et al., arXiv 2022] **Jacobian norm for unsupervised source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2204.03467) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5396999793069796054&hl=en)

- `DAMC` [Zong et al., arXiv 2022] **Domain gap estimation for source free unsupervised domain adaptation with many classifiers** [[PDF]](https://arxiv.org/abs/2207.05785) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6654662849120853418&hl=en) [[CODE]](https://github.com/hejunzz/damc)

- `RCHC` [Diamant et al., arXiv 2022] **Reconciling a centroid-hypothesis conflict in source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2212.03795) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5648022280349163503&hl=en) [[CODE]](https://github.com/ssi-research/SFDA-RCHC)

- `SF-PGL` [Luo et al., arXiv 2022] **Source-free progressive graph learning for open-set domain adaptation** [[PDF]](https://arxiv.org/abs/2202.06174) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14360634658486858894&hl=en) [[CODE]](https://github.com/Luoyadan/SF-PGL)

- `UTR` [Pei et al., arXiv 2022] **Uncertainty-induced transferability representation for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2208.13986) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1877809484055795117&hl=en) [[CODE]](https://github.com/SPIresearch/UTR)

- `EXTERN` [Xu et al., arXiv 2022] **EXTERN: Leveraging endo-temporal regularization for black-box video domain adaptation** [[PDF]](https://arxiv.org/abs/2208.05187) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15714245550833050789&hl=en)

- `...` [Al-Maliki et al., arXiv 2022] **Continual conscious active fine-tuning to robustify online machine learning models against data distribution shifts** [[PDF]](https://arxiv.org/abs/2211.01315) [[G-Scholar]](https://scholar.google.com/scholar?cluster=908547004835103765&hl=en)

- `OneRing` [Yang et al., arXiv 2022] **One ring to bring them all: Model adaptation under domain and category shift** [[PDF]](https://openreview.net/forum?id=dOq0Jbg9hUt) [[G-Scholar]](https://scholar.google.com/scholar?cluster=531273051886454866&hl=en) [[CODE]](https://github.com/Albert0147/OneRing_SF-UNDA)

- `DePT` [Gao et al., Misc 2022] **Visual prompt tuning for test-time domain adaptation** [[PDF]](https://openreview.net/forum?id=3HnIBTjlXTS) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13014566741154429642&hl=en)

- `FTA-FDA` [Peng, Thesis 2022] **Multi-source and source-private cross-domain learning for visual recognition** [[PDF]](https://scholarworks.iupui.edu/handle/1805/29176) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7887089934777244066&hl=en)

### 2023
- `ELR` [Yi et al., Proc. ICLR 2023] **When source-free domain adaptation meets learning with noisy labels** [[PDF]](https://openreview.net/forum?id=u2Pd6x794I) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16104249125202927341&hl=en) [[CODE]](https://github.com/liyi01827/SFDA_LLN/tree/main)

- `BETA` [Yang et al., Proc. ICLR 2023] **Divide to adapt: Mitigating confirmation bias for domain adaptation of black-box predictors** [[PDF]](https://openreview.net/forum?id=hVrXUps3LFA) [[G-Scholar]](https://scholar.google.com/scholar?cluster=202403539281549302&hl=en) [[CODE]](https://github.com/xyupeng/BETA)

- `Twofer` [Liu et al., Proc. ICLR 2023] **Twofer: Tackling continual domain shift with simultaneous domain generalization and adaptation** [[PDF]](https://openreview.net/forum?id=L8iZdgeKmI6) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10874563540507053460&hl=en)

- `SQRL` [Naik et al., Proc. ICML 2023] **Do machine learning models learn statistical rules inferred from data?** [[PDF]](https://www.cis.upenn.edu/~mhnaik/papers/icml23.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10815924208634654959&hl=en) [[CODE--]](https://github.com/DebugML/sqrl)

- `...` [Shen et al., Proc. ICML 2023] **On balancing bias and variance in unsupervised multi-source-free domain adaptation** [[PDF]](https://openreview.net/forum?id=jWFRFz7yIc) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8332211963791176861&hl=en)
  
  ~~[Shen et al., arXiv 2022] **On the benefits of selectivity in pseudo-labeling for unsupervised multi-source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2202.00796) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2134048083339350660&hl=en)~~
  
- `SODA` [Wang et al., Proc. NeurIPS 2023] **SODA: Robust training of test-time data adaptors** [[PDF]](https://arxiv.org/abs/2310.11093) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16757974606908528634&hl=en)

- `CODA` [Chen et al., Proc. NeurIPS 2023] **CODA: Generalizing to open and unseen domains with compaction and disambiguation** [[PDF]](https://openreview.net/forum?id=Jw0KRTjsGA) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1473676182220928288&hl=en) [[CODE]](https://github.com/yuan-yin/CoDA)

- `FedICON` [Tan et al., Proc. NeurIPS 2023] **Is heterogeneity notorious? Taming heterogeneity to handle test-time shift in federated learning** [[PDF]](https://openreview.net/forum?id=qJJmu4qsLO) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6308153228512057567&hl=en)

- `MHPL` [Wang et al., Proc. CVPR 2023] **MHPL: Minimum happy points Learning for active source free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_MHPL_Minimum_Happy_Points_Learning_for_Active_Source_Free_Domain_CVPR_2023_paper.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11650728301910332889&hl=en)
  
  ~~[Wang et al., arXiv 2022] **Active source free domain adaptation** [[PDF]](https://arxiv.org/abs/2205.10711) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13385267099164282245&hl=en)~~

- `PLUE` [Litrico et al., Proc. CVPR 2023] **Guiding pseudo-labels with uncertainty estimation for source-free unsupervised domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/papers/Litrico_Guiding_Pseudo-Labels_With_Uncertainty_Estimation_for_Source-Free_Unsupervised_Domain_Adaptation_CVPR_2023_paper.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3145889777626740597&hl=en) [[CODE]](https://github.com/MattiaLitrico/Guiding-Pseudo-labels-with-Uncertainty-Estimation-for-Source-free-Unsupervised-Domain-Adaptation)
  
  ~~[Litrico et al., arXiv 2023] **Guiding pseudo-labels with uncertainty estimation for test-time adaptation** [[PDF]](https://arxiv.org/abs/2303.03770) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1366266911611158897&hl=en) [[CODE]](https://github.com/MattiaLitrico/Guiding-Pseudo-labels-with-Uncertainty-Estimation-for-Test-Time-Adaptation)~~

- `GLC` [Qu et al., Proc. CVPR 2023] **Upcycling models under domain and category shift** [[PDF]](https://arxiv.org/abs/2303.07110) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4154930328281454966&hl=en) [[CODE]](https://github.com/ispc-lab/GLC)

- `C-SFDA` [Karim et al., Proc. CVPR 2023] **C-SFDA: A curriculum learning aided self-training framework for efficient source free domain adaptation** [[PDF]](https://niluthpol.github.io/Niluthpol_Mithun_Files/CSFDA_CVPR_2023.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3707187333776820224&hl=en) 

- `DiaNA` [Huang et al., Proc. CVPR 2023] **Divide and adapt: Active domain adaptation via customized learning** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Divide_and_Adapt_Active_Domain_Adaptation_via_Customized_Learning_CVPR_2023_paper.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12624075204541864736&hl=en) 

- `CRCo` [Huang et al., Proc. CVPR 2023] **Class relationship embedded learning for source-free unsupervised domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Class_Relationship_Embedded_Learning_for_Source-Free_Unsupervised_Domain_Adaptation_CVPR_2023_paper.pdff) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4697051777212468220&hl=en) [[CODE]](https://github.com/zhyx12/CRCo)

- `SSDA` [Ahmed et al., Proc. ICCV 2023] **SSDA: Secure source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/ICCV2023/html/Ahmed_SSDA_Secure_Source-Free_Domain_Adaptation_ICCV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10826306515588985457&hl=en) [[CODE]](https://github.com/ML-Security-Research-LAB/SSDA)

- `BiMem` [Zhang et al., Proc. ICCV 2023] **Black-box unsupervised domain adaptation with bi-directional atkinson-shiffrin memory** [[PDF]](https://arxiv.org/abs/2308.13236) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14192122120118537229&hl=en) [[CODE]](https://github.com/jingyi0000/BiMem)

- `DSiT` [Sanyal et al., Proc. ICCV 2023] **Domain-specificity inducing transformers for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2308.14023) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7908352507755948834&hl=en) [[CODE--]](http://val.cds.iisc.ac.in/DSiT-SFDA/)

- `...` [Hu et al., Proc. ICCV 2023] **DandelionNet: Domain composition with instance adaptive classification for domain generalization** [[PDF]](https://openaccess.thecvf.com/content/ICCV2023/html/Hu_DandelionNet_Domain_Composition_with_Instance_Adaptive_Classification_for_Domain_Generalization_ICCV_2023_paper.html) [[G-Scholar--]]()

- `Co-learn` [Zhang et al., Proc. ICCV 2023] **Rethinking the role of pre-trained networks in source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_Rethinking_the_Role_of_Pre-Trained_Networks_in_Source-Free_Domain_Adaptation_ICCV_2023_paper.html) [[G-Scholar--]]()
  
  ~~[Zhang et al., arXiv 2022] **Co-learning with pre-trained networks improves source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2212.07585) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3923590156178913294&hl=en)~~

- `CoDAG` [Cho et al., Proc. ICCV 2023] **Complementary domain adaptation and generalization for unsupervised continual domain shift learning** [[PDF]](https://arxiv.org/abs/2303.15833) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8317548949198829712&hl=en) 

- `APA` [Sun et al., Proc. AAAI 2023] **Domain adaptation with adversarial training on penultimate activations** [[PDF]](https://arxiv.org/abs/2208.12853) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13152361105316809189&hl=en) [[CODE]](https://github.com/tsun/APA)

- `DATE` [Han et al., Proc. AAAI 2023] **Discriminability and transferability estimation: A bayesian source importance estimation approach for multi-source-free domain adaptation** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/25946) [[G-Scholar]](https://scholar.google.com/scholar?cluster=87311266190400031&hl=en)

- `RAIN` [Peng et al., IJCAI 2023] **RAIN: Regularization on input and network for black-box domain adaptation** [[PDF]](https://www.ijcai.org/proceedings/2023/0458.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3991269860438698249&hl=en&as_sdt=0,5) [[CODE]](https://github.com/davidpengucf/RAIN)

- `CtO` [Wu et al., Proc. ACMMM 2023] **Chaos to order: A label propagation perspective on source-free domain adaptation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3581783.3613821) [[G-Scholar--]]()

- `CoDE` [Shen et al., Proc. ACMMM 2023] **Collaborative learning of diverse experts for source-free universal domain adaptation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3581783.3612211) [[G-Scholar--]]()

- `CATTAn` [Thopalli et al., Proc. ACCV 2023] **Domain alignment meets fully test-time adaptation** [[PDF]](https://proceedings.mlr.press/v189/thopalli23a.html [[G-Scholar]](https://scholar.google.com/scholar?cluster=10216954534487118514&hl=en) [[CODE]](https://github.com/kowshikthopalli/CATTAn)
  
  ~~[Thopalli et al., Proc. ECCV Workshops 2022] **Geometric alignment improves fully test time adaptation** [[PDF]](https://www.osti.gov/servlets/purl/1874540) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13916311599404592721&hl=en)~~

- `CoNMix` [Kumar et al., Proc. WACV 2023] **Conmix for source-free single and multi-target domain adaptation** [[PDF]](https://arxiv.org/abs/2211.03876) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1532883985875939147&hl=en) [[CODE]](https://github.com/vcl-iisc/CoNMix)

- `GAP` [Chhabra et al., Proc. WACV 2023] **Generative alignment of posterior probabilities for source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/WACV2023/html/Chhabra_Generative_Alignment_of_Posterior_Probabilities_for_Source-Free_Domain_Adaptation_WACV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10619837387605602184&hl=en)

- `SALAD` [Kothandaraman et al., Proc. WACV 2023] **SALAD: Source-free active label-agnostic domain adaptation for classification, segmentation and detection** [[PDF]](https://arxiv.org/abs/2205.12840) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6017453879092897523&hl=en) [[CODE]](https://github.com/divyakraman/SALAD_SourcefreeActiveLabelAgnosticDomainAdaptation)
  
  ~~[Kothandaraman et al., arXiv 2022] **DistillAdapt: Source-free active visual domain adaptation** [[PDF]](https://arxiv.org/abs/2205.12840)~~

- `NHOT` [Cao et al., Proc. ICASSP 2023] **Nasty-SFDA: Source free domain adaptation from a nasty model** [[PDF]](https://ieeexplore.ieee.org/document/10094977) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10777978047288539405&hl=en)

- `C-SUDA` [Ahmed et al., Proc. ICIAP 2023] **Continual source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2304.07374) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5672493940070600167&hl=en) 

- `CIN` [Tang et al., Proc. ICIP 2023] **Cross-inferential networks for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2306.16957) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12620590938840084757&hl=en) 

- `RAT` [Xiao et al., Proc. ICME 2023] **Adversarially robust source-free domain adaptation with relaxed adversarial training** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10219969/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17876047459798404545&hl=en) [[CODE]](https://github.com/Coxy7/RAT)

- `ISKD` [Wang et al., Proc. ICME 2023] **Information selection-based domain adaptation from black-box predictors** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10220054/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15984405574181454776&hl=en)

- `TransMDA` [Li and Wu, Proc. IJCNN 2023] **Transformer-based multi-source domain adaptation without source data** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10191276) [[G-Scholar--]]()

- `SSG-SFDA` [An et al., Proc. IJCNN 2023] **Semi-supervised generalized source-free domain adaptation (SSG-SFDA)** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10191761) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3056186499440201376&hl=en)

- `...` [Zhong et al., Proc. ICIP 2023] **Unknown class feature transformation for open set domain adaptation without source data** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10222226) [[G-Scholar--]]()

- `...` [Li et al., Proc. ICIP 2023] **Target-discriminability-induced multi-source-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10222016) [[G-Scholar--]]()

- `PaCDA` [Prasanna B et al., Proc. CVPR Workshops 2023] **Continual domain adaptation through pruning-aided domain-specific weight modulation** [[PDF]](https://arxiv.org/abs/2304.07560) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4639321340065295039&hl=en) [[CODE]](https://github.com/PrasannaB29/PACDA)

- `...` [Yeh et al., Proc. ICCV Workshops 2023] **Misalignment-free relation aggregation for multi-source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/ICCV2023W/OODCV/html/Yeh_Misalignment-Free_Relation_Aggregation_for_Multi-Source-Free_Domain_Adaptation_ICCVW_2023_paper.html) [[G-Scholar--]]()

- `FCDA` [Lee and Lee, Proc. SPIE International Workshop on Advanced Imaging Technology 2023] **A source-free unsupervised domain adaptation method based on feature consistency** [[PDF]](https://www.spiedigitallibrary.org/proceedings/Download?urlId=10.1117%2F12.2666906) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4306888360461661923&hl=en)

- `...` [Zhang et al., Proc. DSAA 2023] **Tackling model mismatch with mixup regulated test-time training** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10302565) [[G-Scholar--]]()

- `FuzUMSFDA` [Li et al., Proc. FUZZ 2023] **Attention-bridging TS fuzzy rules for universal multi-domain adaptation without source data** [[PDF]](https://ieeexplore.ieee.org/document/10309671) [[G-Scholar--]]()

- `CDT` [Chen et al., Proc. PRCV 2023] **Classifier decoupled training for black-box unsupervised domain adaptation** [[PDF]](https://link.springer.com/chapter/10.1007/978-981-99-8435-0_2) [[G-Scholar--]]()

- `...` [He et al., Proc. IEIR 2023] **Robust batch relation preserving for lifelong unsupervised domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10391241) [[G-Scholar--]]()

- `GILL` [Liang, Proc. ICCWAMTIP 2023] **Source free domain adaptation based on latent dirichlet allocation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10387035)  [[G-Scholar--]]()

  ---------------------------------

- `NRC++` [Yang et al., IEEE TPAMI 2023] **Trust your good friends: Source-free domain adaptation by reciprocal neighborhood clustering** [[PDF]](https://arxiv.org/abs/2309.00528) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13832483681532519069&hl=en)

- `TPDS` [Tang et al., IJCV 2023] **Source-free domain adaptation via target prediction distribution searching** [[PDF]](https://surrey-uplab.github.io/assets/pdf/TangEtAl_IJCV2023.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6285219470702651684&hl=en) [[CODE]](https://github.com/tntek/TPDS)

- `SQAdapt` [Li et al., IEEE TNNLS 2023] **Source-free active domain adaptation via augmentation-based sample query and progressive model adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10368185) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16239702163896389173&hl=en)

- `SDG-MA` [Xu et al., IEEE TGRS 2023] **Universal domain adaptation for remote sensing image scene classification** [[PDF]](https://arxiv.org/abs/2301.11387) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7802316111188678098&hl=en) [[CODE]](https://github.com/zhu-xlab/UniDA)

  ~~[Xu et al., Proc. IGARSS 2022] **Universal domain adaptation without source data for remote sensing image scene classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9884889/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15682142231027232982&hl=en)~~

- `ConDA` [Taufique et al., IEEE TAI 2023] **Continual unsupervised domain adaptation in data-constrained environments** [[PDF]](https://ieeexplore.ieee.org/document/10005797) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8385541483815025219&hl=en)
  
  ~~[Taufique et al., arXiv 2021] **ConDA: Continual unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2103.11056)~~

- `SF-FDN` [Li et al., IEEE TFS 2023] **Source-free multi-domain adaptation with fuzzy rule-based deep neural networks** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10128698) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15428824283149085206&hl=en)

- `PSAT-GDA` [Tang et al., IEEE TMM 2023] **Progressive source-aware transformer for generalized source-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10269002) [[G-Scholar--]]() [[Code--]](https://github.com/tntek/%20PSAT-GDA)

- `TagSHOT` [Hu et al., IEEE TMM 2023] **Unleashing knowledge potential of source hypothesis for source-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/document/10319072/) [[G-Scholar--]]()

- `ASOGE` [Cui et al., IEEE TCSVT 2023] **Adversarial source generation for source-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/document/10335732) [[G-Scholar--]]()

- `DCL` [Tian et al., IEEE TCSVT 2023] **DCL: Dipolar confidence learning for source-free unsupervised domain adaptation** [[PDF]](https://ieeexplore.ieee.org/document/10325530/) [[G-Scholar--]]()

- `PS` [Du et al., Machine Learning 2023] **Generation, augmentation, and alignment: A pseudo-source domain based method for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2109.04015) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2594791991284117635&hl=en)

- `ProxyMix` [Ding et al., Neural Networks 2023] **ProxyMix: Proxy-based mixup training with label refinery for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2205.14566) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8949644873839998049&hl=en) [[CODE]](https://github.com/YuheD/ProxyMix)

- `FAUST` [Lee and Lee, Neural Networks 2023] **Feature alignment by uncertainty and self-training for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2208.14888) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10962800013146398747&hl=en)

- `BPDA` [Shi et al., Pattern Recognition 2023] **Source-free and black-box domain adaptation via distributionally adversarial training** [[PDF]](https://www.sciencedirect.com/science/article/pii/S003132032300448X) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17722267274915107329&hl=en) [[CODE]](https://github.com/shiyuchengTJU/BPDA)

- `CPD` [Zhou et al., Pattern Recognition 2023] **Source-free domain adaptation with class prototype discovery** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320323006726) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13929137317037303976&hl=en)

- `UC-SFDA` [Chen et al., Knowledge-Based Systems 2023] **UC-SFDA: Source-free domain adaptation via uncertainty prediction and evidence-based contrastive learning** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0950705123004781) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17165821853977244331&hl=en) [[CODE]](https://www.github.com/oolown/UC-SFDA)

- `BIAS` [Wang et al., Knowledge-Based Systems 2023] **BIAS: Bridging inactive and active samples for active source free domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0950705123009012) [[G-Scholar--]]()

- `CRMA` [Lü et al., Expert Systems With Applications 2023] **Consistency regularization-based mutual alignment for source-free domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0957417423030798) [[G-Scholar--]]()

- `MSF-SSDA-SPM` [Liang et al., Cognitive Neurodynamics  2023] **Privacy-preserving multi-source semi-supervised domain adaptation for seizure prediction** [[PDF]](https://link.springer.com/article/10.1007/s11571-023-10026-4) [[G-Scholar--]]()

- `RS2L` [Tian et al., Signal, Image and Video Processing 2023] **Robust self-supervised learning for source-free domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s11760-022-02457-z) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18298807507396100788&hl=en)

- `...` [Zhao and Wang, Applied Intelligence 2023] **Universal model adaptation by style augmented open-set consistency** [[PDF]](https://link.springer.com/article/10.1007/s10489-023-04731-0) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11758187876024993731&hl=en) 

- `MViT-PCD` [Dai et al., IEEE Geoscience and Remote Sensing Letters 2023] **MViT-PCD: A lightweight ViT-based network for martian surface topographic change detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10007802/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18353796834673985495&hl=en) [[CODE]](https://github.com/lynn1023-max/MViTPCD)

- `OKRA` [Zhao et al., Computers and Electrical Engineering 2023] **Open-set black-box domain adaptation for remote sensing image scene classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10210386/) [[G-Scholar--]]()

- `FMAS` [Tian and Zhang, Computers and Electrical Engineering 2023] **Feature mixing and self-training for source-free active domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0045790623003907) [[G-Scholar--]]()

- `BCSW` [Tian and Zhao, IEEE Geoscience and Remote Sensing Letters 2023] **Source-free unsupervised domain adaptation via bi-classifier confidence score weighting** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0045790623003518) [[G-Scholar--]]()

- `CLCR` [Tang et al., CAAI Transactions on Intelligence Technology 2023] **Model adaptation via credible local context representation** [[PDF]](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cit2.12228) [[G-Scholar--]]()

- `LCAL` [Fan et al., Journal of Software 2023] **Local consistent active learning for source free open-set domian adaptation** [[PDF]](https://www.jos.org.cn/josen/article/abstract/7010) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8643052782738055932&hl=en)

- `...` [Sahay et al., Sensors 2023] **On the importance of attention and augmentations for hypothesis transfer in domain adaptation and generalization** [[PDF]](https://www.mdpi.com/1424-8220/23/20/8409) [[G-Scholar]](https://scholar.google.com/scholar?cluster=440372465565821463&hl=en)

- `SIE` [Chen et al., Machine Vision and Applications 2023] **Two-stage structural information enhancement for source-free domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s00138-023-01472-5) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2739893677246307437&hl=en)

- `Um2B` [Wang et al., Image and Vision Computing 2023] **Universal domain adaptation from multiple black-box sources** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0262885623002706) [[G-Scholar--]]()

- `FCDC` [Wang et al., Chinese Journal Of Engineering Mathematics 2023] **Source Free Domain Adaptation Based on Feature Structure** [[PDF]](http://jgsx-csiam.org.cn/CN/abstract/abstract427.shtml) [[G-Scholar--]]()

- `ALT` [Wu et al., arXiv 2023] **When source-free domain adaptation meets label propagation** [[PDF]](https://arxiv.org/abs/2301.08413) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16104249125202927341&hl=en)

- `CaC` [Chen et al., arXiv 2023] **Contrast and clustering: Learning neighborhood pair representation for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2301.13428) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3921052647478939852&hl=en) [[CODE]](https://github.com/yukilulu/CaC)

- `GarDA` [Chen et al., arXiv 2023] **Generative appearance replay for continual unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2301.01211) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3516019922974363817&hl=en)

- `PCD` [Tanwisuth et al., arXiv 2023] **A prototype-oriented clustering for domain shift with source privacy** [[PDF]](https://arxiv.org/abs/2302.03807) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16345579331135419218&hl=en) 

- `SCA` [Maracani et al., arXiv 2023] **Key design choices for double-transfer in source-free unsupervised domain adaptation** [[PDF]](https://openreview.net/forum?id=-PL1Gk4jt7) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17679519261820742493&hl=en)

- `...` [Lee et al., arXiv 2023] **Few-shot fine-tuning is all you need for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2304.00792) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5386152009769376343&hl=en) 

- `...` [Rafiee et al., arXiv 2023] **Source-free domain adaptation requires penalized diversity** [[PDF]](https://arxiv.org/abs/2304.02798) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11766176006415279159&hl=en) 

- `T-CPGA` [Lin et al., arXiv 2023] **Imbalance-agnostic source-free domain adaptation via avatar prototype alignment** [[PDF]](https://arxiv.org/abs/2305.12649)) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5357797129800546100&hl=en)

- `Proto-SF-OSDA` [Vray et al., arXiv 2023] **Source-free open-set domain adaptation for histopathological images via distilling self-supervised vision transformer** [[PDF]](https://arxiv.org/abs/2307.04596) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4671978867932847337&hl=en) [[CODE--]](https://github.com/LTS5/Proto-SF-OSDA)

- `FREEDOM` [Yang et al., arXiv 2023] **FREEDOM: Target label & source data & domain information-free multi-source domain adaptation for unsupervised personalization** [[PDF]](https://arxiv.org/abs/2307.02493) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16893616884046226518&hl=en)

- `CCT` [Yan et al., arXiv 2023] **Universal semi-supervised model adaptation via collaborative consistency training** [[PDF]](https://arxiv.org/abs/2307.03449) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5434401477089283458&hl=en)

- `...` [Yu et al., arXiv 2023] **Open-set domain adaptation with visual-language foundation models** [[PDF]](https://arxiv.org/abs/2307.16204) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13858244758842899949&hl=en)

- `...` [Tang et al., arXiv 2023] **Consistency regularization for generalizable source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2308.01587) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6492042532740964914&hl=en)

- `CABB` [Jahan and Savakis, arXiv 2023] **Curriculum guided domain adaptation in the dark** [[PDF]](https://arxiv.org/abs/2308.00956) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9526486867063437046&hl=en)

- `TriDA` [Xu et al., arXiv 2023] **Incorporating pre-training data matters in unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2308.03097) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1813889893434993601&hl=en)

- `DAD++` [Nayak et al., arXiv 2023] **DAD++: Improved data-free test time adversarial defense** [[PDF]](https://arxiv.org/abs/2309.05132) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17366950831150505997&hl=en)

- `FM-SFDA` [Chopra et al., arXiv 2023] **Transcending domains through text-to-image diffusion: A source-free approach to domain adaptation** [[PDF]](https://www.researchgate.net/publication/374419118_Transcending_Domains_through_Text-to-Image_Diffusion_A_Source-Free_Approach_to_Domain_Adaptation) [[G-Scholar]](https://scholar.google.com/scholar?cluster=719025059086880604&hl=en)

- `SIDE` [Liu et al., arXiv 2023] **SIDE: Self-supervised intermediate domain exploration for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2310.08928) [[G-Scholar--]]() [[CODE]](https://github.com/se111/SIDE)

- `Cross DRI` [Sawhney et al., arXiv 2023] **Improving source-free target adaptation with vision transformers leveraging domain representation images** [[PDF]](https://arxiv.org/abs/2311.12589) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7813405270825661306&hl=en)

- `HCLD` [Liu et al., arXiv 2023] **UFDA: Universal federated domain adaptation with practical assumptions** [[PDF]](https://arxiv.org/abs/2311.15570) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18388356757693507313&hl=en)

- `...` [Sheng et al., arXiv 2023] **Self-training solutions for the ICCV 2023 GeoNet challenge** [[PDF]](https://arxiv.org/abs/2311.16843) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2098897309052885736&hl=en)

- `E2` [Shen et al., Misc 2023] **E2: Entropy discrimination and energy optimization for source-free universal domain adaptation** [[PDF]](https://openreview.net/forum?id=FMEXgK9-I8) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2517695593354531262&hl=en)

- `...` [Wang et al., Misc 2023] **Graph-guided unsupervised clustering for source-free domain adaptation** [[PDF]](https://lrjconan.github.io/UBC-EECE571F-DL-Structures/assets/sample_reports_2022_W1/report_06.pdf) [[G-Scholar--]]()

- `...` [Xiao et al., Misc 2023] **Unified multi-level neighbor clustering for source-free unsupervised domain adaptation** [[PDF]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4545323) [[G-Scholar--]]()

- `...` [Wong., Master Thesis 2023] **Reducing negative transfer of random data in source-free unsupervised domain adaptation** [[PDF]](https://ir.lib.uwo.ca/cgi/viewcontent.cgi?article=11907&context=etd) [[G-Scholar--]]() 

- `...` [Thomas., Master Thesis 2023] **Continual domain adaptation through knowledge distillation** [[PDF]](https://scholarworks.rit.edu/theses/11545/) [[G-Scholar--]]() 

### 2024
- `SF(DA)$^2$` [Hwang et al., Proc. ICLR 2024] **SF(DA)$^2$: Source-free domain adaptation through the lens of data augmentation** [[PDF]](https://openreview.net/forum?id=kUCgHbmO11) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2809608642653788853&hl=en) [[CODE]](https://github.com/shinyflight/SFDA2)

- `VDPG` [Chi et al., Proc. ICLR 2024] **Adapting to distribution shift by visual domain prompt generation** [[PDF]](https://openreview.net/forum?id=sSaN4gxuEf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6678494842863135051&hl=en) [[CODE]](https://github.com/Guliisgreat/VDPG)

- `LEAD` [Qu et al., Proc. CVPR 2024] **LEAD: Learning decomposition for source-free universal domain adaptation** [[PDF]](https://arxiv.org/abs/2403.03421) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8636343604585487049&hl=en) [[CODE]](https://github.com/ispc-lab/LEAD)

- `DPC` [Xia et al., Proc. CVPR 2024] **Discriminative pattern calibration mechanism for source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2024/html/Xia_Discriminative_Pattern_Calibration_Mechanism_for_Source-Free_Domain_Adaptation_CVPR_2024_paper.html) [[G-Scholar--]]()

- `UPUK` [Wan et al., Proc. CVPR 2024] **Unveiling the unknown: Unleashing the power of unknown to known in open-set source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2024/html/Wan_Unveiling_the_Unknown_Unleashing_the_Power_of_Unknown_to_Known_CVPR_2024_paper.html) [[G-Scholar--]]() [[CODE--]](https://github.com/xdwfl/UPUK)

- `Improved SFDA` [Mitsuzumi et al., Proc. CVPR 2024] **Understanding and improving source-free domain adaptation from a theoretical perspective** [[PDF]](https://openaccess.thecvf.com/content/CVPR2024/html/Mitsuzumi_Understanding_and_Improving_Source-free_Domain_Adaptation_from_a_Theoretical_Perspective_CVPR_2024_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17385215931384027664&hl=en)

- `DCPL` [Diamant et al., Proc. ECCV 2024] **De-confusing pseudo-labels in source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2401.01650) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7142632812358574823&hl=en) [[CODE]](https://github.com/ssi-research/DCPL_SFDA)

- `NBF` [Song et al., Proc. ECCV 2024] **Is user feedback always informative? Retrieval latent defending for semi-supervised domain adaptation without source data** [[PDF]](https://arxiv.org/abs/2407.15383) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6343848007731199368&hl=en) [[CODE--]](https://github.com/junha1125/RLD-SemiSDA)

- `LFTL` [Lyu et al., Proc. ECCV 2024] **Learn from the learnt: Source-free active domain adaptation via contrastive sampling and visual persistence** [[PDF]](https://arxiv.org/abs/2407.18899) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5688131372670853016&hl=en) [[CODE--]](https://github.com/lyumengyao/lftl)

- `HRD` [Xing et al., Proc. ECCV 2024] **Hierarchical unsupervised relation distillation for source free domain adaptation** [[PDF]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06726.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=123468086557439852&hl=en)

- `SFDA-CDS` [Tejero-de-Pablos et al., Proc. ECCV 2024] **Robust nearest neighbors for source-free domain adaptation under class distribution shift** [[PDF]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09049.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6828132234341731471&hl=en) [[CODE]](https://github.com/CyberAgentAILab/Robust_Nearest_Neighbors_SFDA-CDS)

- `FedGM` [Wei and Han, Proc. AAAI 2024] **Multi-source collaborative gradient discrepancy minimization for federated domain generalization** [[PDF]](https://arxiv.org/abs/2401.10272) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8202719057595874616&hl=en) [[CODE]](https://github.com/weiyikang/FedGM_torch)

- `Bi-ATEN` [Li et al, Proc. AAAI 2024] **Agile multi-source-free domain adaptation** [[PDF](http://arxiv.org/abs/2403.05062) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11330122765447548423&hl=en) [[CODE]](https://github.com/TL-UESTC/Bi-ATEN)

- `SEAL` [Xia et al, Proc. AAAI 2024] **A separation and alignment framework for black-box domain adaptation** [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/29532) [[G-Scholar--]]() [[CODE]](https://github.com/MingxuanXia/SEAL)

- `RFC` [Zhang et al, Proc. AAAI 2024] **Reviewing the forgotten classes for domain adaptation of black-box predictors** [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/29624) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4005670949185008852&hl=en) [[CODE]](https://github.com/shaojiezhanglalala/RFC)

- `DMP` [Zhan et al, Proc. IJCAI 2024] **Towards dynamic-prompting collaboration for source-free domain adaptation** [[PDF](https://www.ijcai.org/proceedings/2024/0182.pdf) [[G-Scholar--]]()

- `AEM` [Xiao et al., Proc. ACM MM 2024] **Adversarial experts model for black-box domain adaptation** [[PDF]](https://openreview.net/forum?id=60QvmIlnhT) [[G-Scholar--]]()

- `...` [Shen et al., Proc. AISTATS 2024] **Continual domain adversarial adaptation via double-head discriminators** [[PDF]](https://arxiv.org/abs/2402.03588) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11538889541778894777&hl=en)

- `EIANet` [Pan et al., Proc. BMVC 2024] **EIANet: A novel domain adaptation approach to maximize class distinction with neural collapse principles** [[PDF]](https://arxiv.org/abs/2407.16189) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2694846243086591413&hl=en) [[CODE]](https://github.com/zichengpan/EIANet)

- `C-SFTrans` [Sanyal et al., Proc. WACV 2024] **Aligning non-causal factors for transformer-based source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2311.16294/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15477511778305510501&hl=en) [[CODE]](https://github.com/val-iisc/DSiT-SFDA)

- `CXDA` [Bohdal et al., Proc. WACV 2024] **Feed-forward latent domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/WACV2024/html/Bohdal_Feed-Forward_Latent_Domain_Adaptation_WACV_2024_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15837576530441040681&hl=en)

- `COCA` [Liu et al., Proc. ACCV 2024] **COCA: Classifier-oriented calibration via textual prototype for source-free universal domain adaptation** [[PDF]](https://arxiv.org/abs/2308.10450) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1207414167001222333&hl=en) [[CODE]](https://github.com/XHomL/COCA)

  ~~ [Bohdal et al., Proc. ICML Workshops 2022] **Feed-forward source-free latent domain adaptation via cross-attention** [[PDF]](https://openreview.net/forum?id=EiQB09V5IX) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15837576530441040681&hl=en)~~

- `USD` [Jahan and Savakis, Proc. CVPR Workshops 2023] **Unknown sample discovery for source free open set domain adaptation** [[PDF]](https://arxiv.org/abs/2312.03767) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4072124127999749285&hl=en)

- `UAD` [Sivaprasad and Fleuret, Proc. ISBI 2024] **Multi-source-free domain adaptation via uncertainty-aware adaptive distillation** [[PDF]](https://arxiv.org/abs/2402.06213) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14240206218895524027&hl=en)

- `SADA` [Liu et al., Proc. ICME 2024] **SADA: Self-adaptive domain adaptation from black-box predictors** [[PDF]](e.org/abstract/document/10687543/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13610058690174521600&hl=en)

- `PECAL` [Machireddy et al., Proc. ICIP 2024] **Source-free continual adaptive learning with limited labels on evolving data drifts** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10648016) [[G-Scholar--]]()

- `...` [Banerjee and Ganesh, Proc. ICPR 2024] **Real-world coarse to fine-grained source-free multidomain adaptation** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-78122-3_29) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14611635445984429551&hl=en)

- `CAT^3` [Feng et al., Proc. CAI 2024] **Category-aware test-time training domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10605260/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10223731562433159378&hl=en)

- `...` [Chen et al., Proc. PRCV 2024] **An entropy-based pseudo-label mixup method for source-free domain adaptation** [[PDF]](https://link.springer.com/chapter/10.1007/978-981-97-8490-5_8) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4900921546291251593&hl=en)

- `SMOTE` [Zou et al., Proc. VCIP 2024] **Handling class imbalance in black-box unsupervised domain adaptation with synthetic minority over-sampling** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10849930/) [[G-Scholar--]]()

- `FedAcross` [Röder et al., Proc. ICPRAM 2024] **Crossing domain borders with federated few-shot adaptation** [[PDF]](https://www.scitepress.org/Papers/2024/123519/123519.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17139721934997781275&hl=en)

- `...` [Yang et al., Proc. IEEE CSCWD 2024] **Source free domain adaptation via adapting to the enhanced style** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10580674/) [[G-Scholar--]]()

- `k-sBetas` [Chiaroni et al., IEEE TPAMI 2024] **Simplex clustering via sBeta with applications to online adjustment of black-box predictions** [[PDF]](https://arxiv.org/abs/2208.00287) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16306533923372320733&hl=en) [[CODE]](https://github.com/fchiaroni/Clustering_Softmax_Predictions/)

- `EAAF` [Pei et al., IEEE TPAMI 2024] **Evidential multi-source-free unsupervised domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10420513)  [[G-Scholar]](https://scholar.google.com/scholar?cluster=7451657378107187713&hl=en) [[CODE]](https://github.com/SPIresearch/EAAF)

- `CC-Loss` [Jin et al., IEEE TPAMI 2024] **One fits many: Class confusion loss for versatile domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10506994)  [[G-Scholar]](https://scholar.google.com/scholar?cluster=9557812502723593052&hl=en) [[CODE]](https://github.com/thuml/Transfer-Learning-Library/blob/master/examples/domain_adaptation/image_classification/cc_loss.py)

- `Co-learn++` [Zhang et al., IJCV 2024] **Source-free domain adaptation guided by vision and vision-language pre-training** [[PDF]](https://arxiv.org/abs/2405.02954) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16448810577157836597&hl=en)

- `BMD-v2` [Qu et al., IJCV 2024] **General Class-balanced multicentric dynamic prototype pseudo-labeling for source-free domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s11263-024-02335-w) [[G-Scholar--]]() [[CODE]](https://github.com/ispc-lab/BMD)

- `ASM` [Jing et al., IEEE TIP 2024] **Visually source-free domain adaptation via adversarial style matching** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10410236)  [[G-Scholar]](https://scholar.google.com/scholar?cluster=1420083944803220325&hl=en)

- `ICPR` [Tian et al., IEEE TNNLS 2024] **Intrinsic consistency preservation with adaptively reliable samples for source-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10438926/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10786835568489220477&hl=en) [[CODE]](https://github.com/CFM-MSG/Code_ICPR)

- `NAMI` [Zhang et al., IEEE TMM 2024] **Neighborhood-aware mutual information maximization for source-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10510655) [[G-Scholar--]]()

- `...` [Ma et al., IEEE TCSVT 2024] **Exploring relational knowledge for source-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10731924) [[G-Scholar--]]()

- `SFADA` [He et al., Pattern Recognition 2024] **Source-free domain adaptation with unrestricted source hypothesis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320323009433) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6406182194472361020&hl=en) [[CODE]](https://github.com/tiggers23/SFADA-main)

- `DPLS` [Ma et al., Pattern Recognition 2024] **Source-free domain adaptation via dynamic pseudo labeling and self-supervision** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0031320324005442) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2006994458495887202&hl=en) [[CODE]](https://github.com/meowpass/DPLS)

- `GOAL` [Peng et al., Pattern Recognition 2024] **Global self-sustaining and local inheritance for source-free unsupervised domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320324004308) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6757497214829593576&hl=en)

- `PFC` [Pan et al., Pattern Recognition 2024] **Overcoming learning bias via prototypical feature compensation for source-free domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320324007763) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5652964496672873440&hl=en)

- `GDT` [Tian and Zhao, Neural Networks 2024] **Generation, division and training: A promising method for source-free unsupervised domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0893608024000583) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13482895004193323062&hl=en)

- `SS-TrBoosting` [Deng et al., IEEE TAI 2024] **Semi-supervised transfer boosting (SS-TrBoosting)** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10382492) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13493837665823220665&hl=en)

- `SiLAN` [Wang et al., TMLR 2024] **What has been overlooked in contrastive source-free domain adaptation: Leveraging source-informed latent augmentation within neighborhood context** [[PDF]](https://openreview.net/forum?id=iulMde3dP1) [[G-Scholar--]]() [[CODE]](https://github.com/JingWang18/SiLAN)

- `UPA` [Chen et al., Neurocomputing 2024] **Uncertainty-aware pseudo-label filtering for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2403.11256) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9592984808926564814&hl=en) [[CODE]](https://github.com/chenxi52/UPA)

- `...` [Xing et al., Neurocomputing 2024] **Rectifying self-training with neighborhood consistency and proximity for source-free domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0925231224011962) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11728936389590945572&hl=en) [[CODE]](https://github.com/xingbw/Rectified-Self-Training)

- `...` [Wang et al., Neurocomputing 2024] **Robust source-free domain adaptation with anti-adversarial samples training** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0925231224015480) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7402858687603446198&hl=en)

- `CdKC` [Zhang et al., Information Processing & Management 2024] **Cross-domain knowledge collaboration for blending-target domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0306457324000906) [[G-Scholar--]]()

- `HCDA` [Li et al., Pattern Recognition Letters 2024] **Pseudo-label refinement via hierarchical contrastive learning for source-free unsupervised domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0167865524002940) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1304108092038411534&hl=en)

- `...` [Zhou et al., Pattern Recognition Letters 2024] **Multi source-free domain adaptation based on pseudo-label knowledge mining** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0167865524003209) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9166091053667283114&hl=en1)

- `DCA` [Wang et al., Neural Processing Letters 2024] **Dual classifier adaptation: Source-free UDA via adaptive pseudo-labels learning** [[PDF]](https://link.springer.com/article/10.1007/s11063-024-11627-8) [[G-Scholar--]]() [[CODE]](https://github.com/MALA-NJUPT/DCA)

- `CODA` [Liu et al., Engineering Applications of Artificial Intelligence 2024] **Consistency-guided multi-source-free domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0952197624016555) [[G-Scholar--]]()

- `SCAL` [Sun et al., IET Image Processing 2024] **You only label once: A self-adaptive clustering-based method for source-free active domain adaptation** [[PDF]](https://ietresearch.onlinelibrary.wiley.com/doi/abs/10.1049/ipr2.13025) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5526844683554218048&hl=en)

- `FUSE` [Tian et al., Signal, Image and Video Processing 2024] **Source bias reduction for source-free domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s11760-024-03200-6) [[G-Scholar--]]()

- `TAS` [Shao et al., Neural Computing and Applications 2024] **Adaptive pseudo-label threshold for source-free domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s00521-024-10697-y) [[G-Scholar--]]()

- `RECS` [Tian and Sun, Neural Computing and Applications 2024] **Rethinking confidence scores for source-free unsupervised domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s00521-024-09867-9) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4082483273156505147&hl=en) [[CODE]](https://github.com/lingyuxuan1234/RECS)

- `MLCL` [Ouyang et al., Multimedia Systems 2024] **Exploiting multi-level consistency learning for source-free domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s00530-024-01444-3) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13519291438299122510&hl=en) [[CODE]](https://github.com/zzj94/MLCL)

- `SP-CDL` [Santoso and Wijaya, Asian American Research Letters Journal 2024] **Source-private cross-domain learning: Enhancing visual recognition with multi-source domain adaptation** [[PDF]](https://www.aarlj.com/index.php/AARLJ/article/view/87) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3318563098078667937&hl=en)

- `USDAP` [Shao et al., Journal of Electronic Imaging 2024] **USDAP: universal source-free domain adaptation based on prompt learning** [[PDF]](https://www.spiedigitallibrary.org/journals/journal-of-electronic-imaging/volume-33/issue-5/053015/USDAP--universal-source-free-domain-adaptation-based-on-prompt/10.1117/1.JEI.33.5.053015.short) [[G-Scholar--]]()

- `CosGAN` [Naz et al., Intelligent Automation & Soft Computing 2024] **Robot vision over CosGANs to enhance performance with source-free domain adaptation using advanced loss function** [[PDF]](https://www.techscience.com/iasc/online/detail/21608) [[G-Scholar--]]() 

- `MixAdapt` [Sheng et al., arXiv 2024] **Can we trust the unlabeled target data? Towards backdoor attack and defense on model adaptation** [[PDF]](https://arxiv.org/abs/2401.06030) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10285492613128460283&hl=en)

- `4Ds` [Tang et al., arXiv 2024] **Direct distillation between different domains** [[PDF]](https://arxiv.org/abs/2401.06826) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4772191739289030232&hl=en)

- `DM-SFDA` [Chopra et al., arXiv 2024] **Source-free domain adaptation with diffusion-guided source data generation** [[PDF]](https://arxiv.org/abs/2402.04929) [[G-Scholar]](https://scholar.google.com/scholar?cluster=892535893651111169&hl=en)

- `SepRep-Net` [Jin et al., arXiv 2024] **SepRep-Net: Multi-source free domain adaptation via model separation and reparameterization** [[PDF]](https://arxiv.org/abs/2402.08249) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9222606155095006545&hl=en)

- `LDAuCID` [Rostami, arXiv 2024] **Continuous unsupervised domain adaptation using stabilized representations and experience replay** [[PDF]](https://arxiv.org/abs/2402.00580) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2690826121693915504&hl=en) [[CODE]](https://github.com/rostami-m/LDACID)

- `HCPR` [Shu et al., arXiv 2024] **Source-free unsupervised domain adaptation with hypothesis consolidation of prediction rationale** [[PDF]](https://arxiv.org/abs/2402.01157) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3460934716051010037&hl=en) [[CODE]](https://github.com/GANPerf/HCPR)

- `SCA` [Maracani et al., arXiv 2024] **Key design choices in source-free unsupervised domain adaptation: An in-depth empirical analysis** [[PDF]](https://arxiv.org/abs/2402.16090) [[G-Scholar]](https://scholar.google.com/scholar?cluster=709449841286767059&hl=en)

- `SUTE` [Pei et al., arXiv 2024] **On the model-agnostic multi-source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2403.01582) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3906297345341610077&hl=en)

- `LCFD` [Tang et al., arXiv 2024] **Unified source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2403.07601) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5793394107610803011&hl=en) [[CODE]](https://github.com/tntek/source-free-domain-adaptation)

- `GLC++` [Qu et al., arXiv 2024] **GLC++: Source-free universal domain adaptation through global-local clustering and contrastive affinity learning** [[PDF]](https://arxiv.org/abs/2403.14410) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9058273234475952888&hl=en) [[CODE]](https://github.com/ispc-lab/GLC-plus)

- `...` [Litrico et al., arXiv 2024] **Uncertainty-guided open-set source-free unsupervised domain adaptation with target-private class segregation** [[PDF]](https://arxiv.org/abs/2404.10574) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17847386924872930134&hl=en)

- `...` [Zou et al., arXiv 2024] **Incremental pseudo-labeling for black-box unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2405.16437) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16767933709374501800&hl=en)

- `...` [Jiang et al., arXiv 2024] **High-order neighborhoods know more: HyperGraph learning meets source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2405.06916) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14976529978689430892&hl=en)

- `MIRoUDA` [Yin et al., arXiv 2024] **Towards trustworthy unsupervised domain adaptation: A representation learning perspective for enhancing robustness, discrimination, and generalization** [[PDF]](https://arxiv.org/abs/2406.13180) [[G-Scholar--]]()

- `ECA` [Zheng et al., arXiv 2024] **Evidential graph contrastive alignment for source-free blending-target domain adaptation** [[PDF]](https://arxiv.org/abs/2408.07527) [[G-Scholar]](https://scholar.google.com.sg/scholar?cluster=11281747430103451880&hl=en)

- `TAB` [Maracani et al., arXiv 2024] **Trust and balance: Few trusted samples pseudo-labeling and temperature scaled loss for effective source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2409.00741) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16032437956341103664&hl=en) [[CODE--]](https://github.com/andreamaracani/TAB_SFUDA)

- `StepSPT` [Xu et al., arXiv 2024] **Step-wise distribution alignment guided style prompt tuning for source-free cross-domain few-shot learning** [[PDF]](https://arxiv.org/abs/2411.10070) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8720702324262666555&hl=en) [[CODE]](https://github.com/xuhuali-mxj/StepSPT)

- `MEA` [Wang et al., arXiv 2024] **Unveiling the superior paradigm: A comparative study of source-free domain adaptation and unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2411.15844) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3412071246184659825&hl=en)

- `RRDA` [Nejjar et al., arXiv 2024] **Recall and refine: A simple but effective source-free open-set domain adaptation framework** [[PDF]](https://arxiv.org/abs/2411.12558) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8922691053923564309&hl=en) [[CODE]](https://github.com/ismailnejjar/RRDA)

- `ProDDing` [Liang et al., arXiv 2024] **Prototypical distillation and debiased tuning for black-box unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2412.20670) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10519664997246515621&hl=en)

- `...` [Zhu et al., Misc 2024] **Pick and adapt: An iterative approach for source-free domain adaptation** [[PDF]](https://openreview.net/forum?id=SaSK9M66KK) [[G-Scholar--]]()

- `SlimTTT` [Cai et al., Misc 2024] **Resource efficient test-time training with slimmable network** [[PDF]](https://openreview.net/forum?id=7iuFxx9Ccx) [[G-Scholar--]]()

- `LPR` [Yoo et al., Misc 2024] **Label space-induced pseudo label refinement for multi-source black-box domain adaptation** [[PDF]](https://openreview.net/forum?id=JGTC6WgO4T) [[G-Scholar--]]()

- `...` [Musabe, Master Thesis 2024] **Towards regression-free and source-free online domain adaptation** [[PDF]](https://mspace.lib.umanitoba.ca/items/d9190005-e89a-4b46-b2de-f12042436094) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8863159720183005103&hl=en)

- `...` [Eastwood, Phd Thesis 2024] **Shift happens: How can machine learning systems be best prepared?** [[PDF]](https://era.ed.ac.uk/handle/1842/41628) [[G-Scholar--]]()

- `...` [Chhabra, Phd Thesis 2024] **Making the best of what we have: Novel strategies for training neural networks under restricted labeling information** [[PDF]](https://keep.lib.asu.edu/items/193841) [[G-Scholar--]]()

- `...` [Yuan, Phd Thesis 2024] **Domain adaptation in biomedical engineering: unsupervised, source‑free, and black box approaches** [[PDF]](https://dr.ntu.edu.sg/handle/10356/177418) [[G-Scholar--]]()

### 2025
- `ProDe` [Tang et al., Proc. ICLR 2025] **Proxy denoising for source-free domain adaptation** [[PDF]](https://openreview.net/forum?id=FIj9IEPCKr) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17620695069530556718&hl=en)

- `UCon-SFDA` [Xu et al., Proc. ICLR 2025] **Revisiting source-free domain adaptation: A new perspective via uncertainty control** [[PDF]](https://openreview.net/forum?id=nx9Z5Kva96) [[G-Scholar--]]() [[CODE--]](https://github.com/xugezheng/UCon_SFDA)

- `BN-SFDA` [Deng et al., Proc. AISTATS 2025] **Rethinking the role of batch normalization in source-free domain adaptation** [[PDF]](https://openreview.net/forum?id=NiyGv5qTzI) [[G-Scholar--]]() [[CODE]](https://github.com/SJTU-dxw/BN-SFDA)

- `EBPR` [Deng et al., Proc. AISTATS 2025] **Leveraging frozen batch normalization for co-training in source-free domain adaptation** [[PDF]](https://proceedings.mlr.press/v258/deng25c.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16283498704495397599&hl=en) [[CODE]](https://github.com/SJTU-dxw/BN-SFDA)

- `GMM` [Schlachter et al., Proc. WACV 2025] **Memory-efficient pseudo-labeling for online source-free universal domain adaptation using a gaussian mixture model** [[PDF]](https://arxiv.org/abs/2407.14208) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5405263564082143661&hl=en) [[CODE]](https://github.com/pascalschlachter/GMM)

- `EKS` [Rai et al., Proc. WACV 2025] **Label calibration in source free domain adaptation** [[PDF]](https://arxiv.org/abs/2501.07072) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10481551965563048436&hl=en) [[CODE--]](https://visdomlab.github.io/EKS/)

- `ElimPCL` [Cheng et al., Proc. ICME 2025] **ElimPCL: Eliminating noise accumulation with progressive curriculum labeling for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2503.23712) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15452441344301908136&hl=en)

- `NVC-LLN` [Xu et al., IEEE TPAMI 2025] **Unraveling the mysteries of label noise in source-free domain adaptation: Theory and practice** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10858421) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6005165208774683209&hl=en) [[CODE]](https://github.com/xugezheng/labelNoiseInSFDA)

- `FuzHDA` [Li et al., IEEE TFUZZ 2025] **Fuzzy domain adaptation from heterogeneous source teacher models** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10883015/) [[G-Scholar--]]()

- `MLR` [Li et al., Pattern Recognition 2025] **Leveraging multi-level regularization for efficient domain adaptation of black-box predictors** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320325002717) [[G-Scholar--]]()

- `SUFS` [Li et al., Pattern Recognition 2025] **Separation of unknown features and samples for unbiased source-free open set domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320325003218) [[G-Scholar--]]()

- `...` [Zhang et al., IEEE Geoscience and Remote Sensing Letters 2025] **Ship detection in SAR images via source-free domain adaptation from optical image domain** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10891040/) [[G-Scholar--]]()

- `EBPR` [Meng et al., Pattern Recognition Letters 2025] **Energy-based pseudo-label refining for source-free domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0167865525001370) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2064201758216349882&hl=en)

- `...` [Guo and Li, Knowledge and Information Systems 2025] **Contrastive prototype source-free adaptation boosted by inherent data structure** [[PDF]](https://link.springer.com/article/10.1007/s10115-025-02385-7) [[G-Scholar--]]()

## Attacks and Defenses
- `AdaptGuard` [Sheng et al., Proc. ICCV 2023] **AdaptGuard: Defending against universal attacks for model adaptation** [[PDF]](https://arxiv.org/abs/2303.10594) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5822749974898079720&hl=en) 

- `MIXADAPT` [Sheng et al., arXiv 2024] **Can we trust the unlabeled target data: Towards backdoor attack and defense on model adaptation** [[PDF]](https://arxiv.org/abs/2401.06030) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10285492613128460283&hl=en)

## Semantic Segmentation
### 2021
- `SFDA-UR` [Sivaprasad and Fleuret, Proc. CVPR 2021] **Uncertainty reduction for model adaptation in semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/S_Uncertainty_Reduction_for_Model_Adaptation_in_Semantic_Segmentation_CVPR_2021_paper.html?ref=https://githubhelp.com) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10763756734865751592&hl=en) [[CODE]](https://github.com/idiap/model-uncertainty-for-adaptation)

- `SFDA-KTMA` [Liu et al., Proc. CVPR 2021] **Source-free domain adaptation for semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Liu_Source-Free_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2021_paper.html?ref=https://githubhelp.com) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9907456742879822543&hl=en)

- `SoMAN-cPAE` [Kundu et al., Proc. ICCV 2021] **Generalize then adapt: Source-free domain adaptive semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/ICCV2021/html/Kundu_Generalize_Then_Adapt_Source-Free_Domain_Adaptive_Semantic_Segmentation_ICCV_2021_paper.html?ref=https://githubhelp.com) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6109459705970378905&hl=en) [[CODE]](https://github.com/val-iisc/SFDA-Seg)

- `MAS3` [Stan and Rostami, Proc. AAAI 2021] **Unsupervised model adaptation for continual semantic segmentation** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/16362) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11863380647808017555&hl=en) [[CODE]](https://github.com/serbanstan/mas3-continual) 

- `LD` [You et al., Proc. ACMMM 2021] **Domain adaptive semantic segmentation without source data** [[PDF]](https://arxiv.org/abs/2110.06484) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2164649778847843995&hl=en) [[CODE]](https://github.com/fumyou13/LDBE)

- `SFDA-VS` [Ye et al., Proc. ACMMM 2021] **Source data-free unsupervised domain adaptation for semantic segmentation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3474085.3475384) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15526409977910918571&hl=en)

- `AUGCO` [Prabhu et al., Proc. NeurIPS Workshops 2022] **Augmentation consistency-guided self-training for source-free domain adaptive semantic segmentation** [[PDF]](https://openreview.net/forum?id=tOCxfUebrlz) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14612502916018600679&hl=en)
  
  ~~[Prabhu et al., Proc. ECCV Workshops 2022] **AUGCO: Augmentation consistency-guided self-training for source-free domain adaptive semantic segmentation** [[PDF]](https://arxiv.org/abs/2107.10140)~~ 
  
  ~~[Prabhu et al., arXiv 2021] **S4T: Source-free domain adaptation for semantic segmentation via self-supervised selective self-training** [[PDF]](https://arxiv.org/abs/2107.10140)~~ 

  -----------------------

- `PR-SFDA` [Luo et al., arXiv 2021] **Exploiting negative learning for implicit pseudo label rectification in source-free domain adaptive semantic segmentation** [[PDF]](https://arxiv.org/abs/2106.12123) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15003821819568404211&hl=en)

- `SFDA-ST` [Paul et al., arXiv 2021] **Unsupervised adaptation of semantic segmentation models without source data** [[PDF]](https://arxiv.org/abs/2112.02359) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10130538691883639678&hl=en)

### 2022
- `RIPU` [Xie et al., Proc. CVPR 2022] **Towards fewer annotations: Active learning via region impurity and prediction uncertainty for domain adaptive semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022/html/Xie_Towards_Fewer_Annotations_Active_Learning_via_Region_Impurity_and_Prediction_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=907514128348245282&hl=en) [[CODE]](https://github.com/BIT-DA/RIPU)

- `SimT` [Guo et al., Proc. CVPR 2022] **SimT: Handling open-set noise for domain adaptive semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022/html/Guo_SimT_Handling_Open-Set_Noise_for_Domain_Adaptive_Semantic_Segmentation_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9175191664302585452&hl=en) [[CODE]](https://github.com/CityU-AIM-Group/SimT)

- `OnDA` [Panagiotakopoulos et al., Proc. ECCV 2022] **Online domain adaptation for semantic segmentation in ever-changing conditions** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940125.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13123083871593814171&hl=en) [[CODE]](https://github.com/theo2021/OnDA)

- `UnMSMA-MiFL` [Li et al., Proc. ECCV 2022] **Union-set multi-source model adaptation for semantic segmentation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136890570.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8783974652276072046&hl=en) [[CODE]](https://github.com/lzy7976/union-set-model-adaptation)

- `UBNA` [Klingner et al., Proc. WACV Workshops 2022] **Unsupervised batchnorm adaptation \(ubna\): A domain adaptation method for semantic segmentation without using source domain representations** [[PDF]](https://openaccess.thecvf.com/content/WACV2022W/DNOW/html/Klingner_Unsupervised_BatchNorm_Adaptation_UBNA_A_Domain_Adaptation_Method_for_Semantic_WACVW_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8599373467519099477&hl=en) [[CODE]](https://github.com/ifnspaml/UBNA)

- `DTAC` [Yang et al., Proc. ICME 2022] **Source free domain adaptation for semantic segmentation via distribution transfer and adaptive class-balanced self-training** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9859581/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8777021429851186285&hl=en)

- `MSMA-MiFL` [Li et al., Proc. ICIP 2022] **Improving model adaptation for semantic segmentation by learning model-invariant features with multiple source-domain models** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9897487/) [[G-Scholar]](https://scholar.google.com/scholar?cites=11886674186993570843&hl=en)

  ------------------

- `SPGM` [Yang et al., IEEE TIFS 2022] **Revealing task-relevant model memorization for source-protected unsupervised domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9705526) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7510566731887672556&hl=en)

- `CPSS` [Zhao et al., IEEE TCSVT 2022] **Source-free open compound domain adaptation in semantic segmentation** [[PDF]](http://yuyangzhao.com/files/sfocda-tcsvt.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3170260958747192184&hl=en) [[CODE]](https://github.com/HeliosZhao/SFOCDA)

- `RuST` [Luo et al., IEEE RAL 2022] **Multi-level consistency learning for source-free model adaptation** [[PDF]](https://ieeexplore.ieee.org/document/9928327/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5126397401023348966&hl=en)

- `STvM` [Akkaya et al., arXiv 2022] **Self-training via metric learning for source-free domain adaptation of semantic segmentation** [[PDF]](https://arxiv.org/abs/2212.04227) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1554540489499857924&hl=en)

- `CONDA` [Truong et al., arXiv 2022] **CONDA: Continual unsupervised domain adaptation learning in visual perception for self-driving cars** [[PDF]](https://arxiv.org/abs/2212.00621) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13009693848444756082&hl=en)

### 2023
- `Uni-UVPT` [Ma et al., Proc. NeurIPS 2023] **When visual prompt tuning meets source-free domain adaptive semantic segmentation** [[PDF]](https://openreview.net/forum?id=ChGGbmTNgE) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11464554454189990593&hl=en)

- `STPL` [Lo et al., Proc. CVPR 2023] **Spatio-temporal pixel-level contrastive learning-based source-free domain adaptation for video semantic segmentation** [[PDF]](https://arxiv.org/abs/2303.14361) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12402659548166581777&hl=en)

- `DT-ST` [Zhao et al., Proc. CVPR 2023] **Towards better stability and adaptability: Improve online self-training for model adaptation in semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Towards_Better_Stability_and_Adaptability_Improve_Online_Self-Training_for_Model_CVPR_2023_paper.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10385024080439123959&hl=en)

- `...` [Lo et al., Proc. CVPR 2023] **Unsupervised continual semantic adaptation through neural rendering** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_Unsupervised_Continual_Semantic_Adaptation_Through_Neural_Rendering_CVPR_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1555361275637880312&hl=en&as_sdt=0,5)

- `...` [Yin et al., Proc. ICCV 2023] **CrossMatch: Source-free domain adaptive semantic segmentation via cross-modal consistency training** [[PDF]](https://openaccess.thecvf.com/content/ICCV2023/html/Yin_CrossMatch_Source-Free_Domain_Adaptive_Semantic_Segmentation_via_Cross-Modal_Consistency_Training_ICCV_2023_paper.html) [[G-Scholar--]]()

- `Cal-SFDA` [Wang et al., Proc. ACMMM 2023] **Cal-SFDA: Source-free domain-adaptive semantic segmentation with differentiable expected calibration error** [[PDF]](https://arxiv.org/abs/2308.03003) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11580522770647117655&hl=en) [[CODE]](https://github.com/Jo-wang/Cal-SFDA)

- `...` [Li et al., Proc. ACMMM 2023] **When masked image modeling meets source-free unsupervised domain adaptation: Dual-level masked network for semantic segmentation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3581783.3612521) [[G-Scholar--]]()

- `...` [Bohdal et al., Proc. ICLR Workshops 2023] **Label calibration for semantic segmentation under domain shift** [[PDF]](https://openreview.net/forum?id=DhKMA-nXrUY) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13852832181788146846&hl=en)

- `CoRTe` [Cuttano et al., Proc. ICCV Workshops 2023] **Cross-domain transfer learning with CoRTe: Consistent and reliable transfer from black-box to lightweight segmentation model** [[PDF]](https://openaccess.thecvf.com/content/ICCV2023W/RCV/html/Cuttano_Cross-Domain_Transfer_Learning_with_CoRTe_Consistent_and_Reliable_Transfer_from_ICCVW_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4916986134423436060&hl=en)

---------------------------------

- `CROTS` [Luo et al., IJCV 2023] **Crots: Cross-domain teacher–student learning for source-free domain adaptive semantic segmentation** [[PDF]](https://link.springer.com/article/10.1007/s11263-023-01863-1) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17462339529821492264&hl=en) [[CODE--]](https://github.com/luoxin13/CROTS)

- `...` [Lu et al., IEEE TIP 2023] **Uncertainty-aware source-free domain adaptive semantic segmentation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10189399) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8610085403644983243&hl=en)

- `STAL` [Guan and Yuan, arXiv 2023] **Iterative loop learning combining self-training and active learning for domain adaptive semantic segmentation** [[PDF]](https://arxiv.org/abs/2301.13361) [[G-Scholar]](https://scholar.google.com/scholar?cluster=580721324325082611&hl=en) [[CODE]](https://github.com/licongguan/STAL)

- `BTOL` [Wang et al., arXiv 2023] **Bootstrap the original latent: Freeze-and-thaw adapter for back-propagated black-box adaptation** [[PDF]](https://arxiv.org/abs/2303.03709) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15783455669601732347&hl=en)

- `CMA` [Bruggemann et al., arXiv 2023] **Contrastive model adaptation for cross-condition robustness in semantic segmentation** [[PDF]](https://arxiv.org/abs/2303.05194) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11262078686777334014&hl=en) [[CODE]](https://github.com/brdav/cma)

- `CoSDA` [Feng et al., arXiv 2023] **CoSDA: Continual source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2304.06627) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9482207153777900850&hl=en) [[CODE]](https://github.com/FengHZ/CoSDA)

- `IAPC` [Cao et al., arXiv 2023] **Towards source-free domain adaptive semantic segmentation via importance-aware and prototype-contrast learning** [[PDF]](https://arxiv.org/abs/2306.01598) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10989803426543315642&hl=en) [[CODE]](https://github.com/yihong-97/Source-free_IAPC)

- `PTDiffSeg` [Gong et al., arXiv 2023] **Prompting diffusion representations for cross-domain semantic segmentation** [[PDF]](https://arxiv.org/abs/2307.02138) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14980397105808204165&hl=en) [[CODE--]](https://github.com/ETHRuiGong/PTDiffSeg)

- `ReGEN` [Tjio et al., arXiv 2023] **Generating reliable pixel-level labels for source free domain adaptation** [[PDF]](https://arxiv.org/abs/2307.00893) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9031506061920618972&hl=en)

- `WeSAM` [Zhang et al., arXiv 2023] **Improving the generalization of segmentation foundation model under distribution shift via weakly supervised adaptation** [[PDF]](https://arxiv.org/abs/2312.03502) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14418083010954243048&hl=en) [[CODE]](https://github.com/Zhang-Haojie/WeSAM)

- `...` [Sashikanth., Master Thesis 2023] **Active learning guided source-free domain adaptive semantic segmentation and applications in the environmental space** [[PDF]](https://escholarship.org/uc/item/1j56m62f) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12433256709592012887&hl=en)

### 2024
- `360SFUDA` [Zheng et al., Proc. CVPR 2024] **Semantics, distortion, and style matter: Towards source-free UDA for panoramic segmentation** [[PDF]](https://arxiv.org/abs/2403.12505) [[G-Scholar]](https://scholar.google.com/scholar?cluster=121363794852722597&hl=en) [[CODE]](https://github.com/zhengxujosh/360SFUDA)

- `SND` [Zhao et al., Proc. CVPR 2024] **Stable neighbor denoising for source-free domain adaptive segmentation** [[PDF]](https://arxiv.org/abs/2406.06813) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17488124855985467148&hl=en) [[CODE]](https://github.com/DZhaoXd/SND)

- `FREST` [Lee et al, Proc. ECCV 2024] **FREST: Feature restoration for semantic segmentation under multiple adverse conditions** [[PDF]](https://arxiv.org/abs/2407.13437) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12288371437392512998&hl=en) [[CODE--]](https://github.com/sohyun-l/frest)

- `RKP` [Zang et al., Proc. ACM MM 2024] **Generalized source-free domain-adaptive segmentation via reliable knowledge propagation** [[PDF]](https://openreview.net/forum?id=dmkAVtukfK) [[G-Scholar--]]()

- `...` [Gao et al., Proc. IEEE GRSL 2024] **Attention prompt-driven source-free adaptation for remote sensing images semantic segmentation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10583928/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3053128466868794489&hl=en)

- `ATP` [Wang et al., IEEE TPAMI 2024] **A curriculum-style self-training approach for source-free semantic segmentation** [[PDF]](https://arxiv.org/abs/2106.11653) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3520399181801870246&hl=en) [[CODE]](https://github.com/yxiwang/ATP)

  ~~`ATP` [Wang et al., arXiv 2021] **Source data-free cross-domain semantic segmentation: align, teach and propagate** [[PDF]](https://arxiv.org/abs/2106.11653) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15515597080922741941&hl=en)~~

- `PIG` [Xie et al., IEEE TIP 2024] **PIG: Prompt images guidance for night-time scene parsing** [[PDF]](https://arxiv.org/abs/2406.10531) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9536420023790544555&hl=en) [[CODE]](https://github.com/qiurui4shu/PIG)

- `ProAC` [Ren et al., IEEE TCSVT 2024] **Exploring prototype-anchor contrast for semantic segmentation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10445499/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8127961343037029711&hl=en)

- `...` [Tian et al., IEEE TMM 2024] **Self-mining the confident prototypes for source-free unsupervised domain adaptation in image segmentation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10452765/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=777411465098328628&hl=en)

- `...` [Ren et al., Multimedia Systems 2024] **SAM-guided contrast based self-training for source-free cross-domain semantic segmentation** [[PDF]](https://link.springer.com/article/10.1007/s00530-024-01426-5) [[G-Scholar--]]()

- `...` [Zhou et al., Image and Vision Computing 2024] **Black-box model adaptation for semantic segmentation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S026288562400338X) [[G-Scholar--]]()

- `...` [Stand and Rostami, Frontiers in Big Data 2024] **Source-free domain adaptation for semantic image segmentation using internal representations** [[PDF]](https://www.frontiersin.org/journals/big-data/articles/10.3389/fdata.2024.1359317/full) [[G-Scholar--]]()

- `MAS3` [Stan and Rostami, arXiv 2024] **Online continual domain adaptation for semantic image segmentation using internal representations** [[PDF]](https://arxiv.org/abs/2401.01035) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5773237290303399495&hl=en)

- `FFreeDA` [Rizzoli et al., arXiv 2024] **When cars meet drones: Hyperbolic federated learning for source-free domain adaptation in adverse weather** [[PDF]](https://arxiv.org/abs/2403.13762) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14495060341531327733&hl=en)

- `360SFUDA++` [Zheng et al., arXiv 2024] **360SFUDA++: Towards source-free UDA for panoramic segmentation by learning reliable category prototypes** [[PDF]](https://arxiv.org/abs/2404.16501) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12998254106770471662&hl=en) [[CODE]](https://github.com/zhengxujosh/360SFUDA)

### 2025
- `UITI` [An et al., Misc 2025] **UITI: Unpaired image-to-image source-free domain adaptation for semantic segmentation** [[PDF]](https://www.researchsquare.com/article/rs-6170622/v1) [[G-Scholar--]]()

## Object Detection
### before 2020
- `DA-Re2` [Jamal et al., Proc. CVPR 2018] **Deep face detector adaptation without negative transfer or catastrophic forgetting** [[PDF]](https://openaccess.thecvf.com/content_cvpr_2018/html/Jamal_Deep_Face_Detector_CVPR_2018_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16142889079977911016&hl=en)

- `TemporalST` [RoyChowdhury et al., Proc. CVPR 2019] **Automatic adaptation of object detectors to new domains using self-training** [[PDF]](https://openaccess.thecvf.com/content_CVPR_2019/html/RoyChowdhury_Automatic_Adaptation_of_Object_Detectors_to_New_Domains_Using_Self-Training_CVPR_2019_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10007525946029526934&hl=en) [[CODE]](https://github.com/AruniRC/detectron-self-train)

### 2021
- `SFOD-Mosaic` [Li et al., Proc. AAAI 2021] **A free lunch for unsupervised domain adaptive object detection without source data** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/17029) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6980672955157492261&hl=en)

- `SMT` [Zhang et al., Proc. ACMMM Asia 2021] **Source-style transferred mean teacher for source-data free object detection** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3469877.3490584) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5511368567027293412&hl=en)

  --------------------
  
- `SOAP` [Xiong et al., International Journal of Intelligent Systems 2021] **Source data‐free domain adaptation of object detector through domain‐specific perturbation** [[PDF]](https://onlinelibrary.wiley.com/doi/abs/10.1002/int.22434) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6633136569680956949&hl=en)

### 2022
- `SFDA-PT` [Chen et al., Proc. ICML 2022] **Learning domain adaptive object detection with probabilistic teacher** [[PDF]](https://proceedings.mlr.press/v162/chen22b.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17755903452096200771&hl=en) [[CODE]](https://github.com/hikvision-research/ProbabilisticTeacher)

- `LODS` [Li et al., Proc. CVPR 2022] **Source-free object detection by learning to overlook domain style** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Source-Free_Object_Detection_by_Learning_To_Overlook_Domain_Style_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11890223003866230078&hl=en) [[CODE]](https://github.com/Flashkong/Source-Free-Object-Detection-by-Learning-to-Overlook-Domain-Style)

- `S&M` [Yuan et al., Proc. ICASSP 2022] **Simulation-and-mining: Towards accurate source-free unsupervised domain adaptive object detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9746269/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12089546329819915592&hl=en)

- `PLMS` [Tang et al., Proc. ICME 2022] **Source-free unsupervised cross-domain pedestrian detection via pseudo label mining and screening** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9859707/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15465655561154028361&hl=en)

- `MoTE` [VS et al., Proc. ICIP 2022] **Mixture of teacher experts for source-free domain adaptive object detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9897795/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9620499609798167796&hl=en)

- `ESOD` [Wei et al., Proc. ICONIP 2022] **Entropy-minimization mean teacher for source-free domain adaptive object detection** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-30105-6_43) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11400952515276089056&hl=en)

  ---------------------------
  
- `PLA-DAP` [Xiong et al., Pattern Recognition 2022] **Source data-free domain adaptation for a faster R-CNN** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320321006129) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2911507652442359206&hl=en) [[CODE]](https://github.com/xiong233/Source-Data-free-Domain-Adaptation-for-a-Faster-R-CNN)

- `G&A` [Zhao et al., arXiv 2022] **1st place solution for ECCV 2022 OOD-CV challenge object detection track** [[PDF]](https://arxiv.org/abs/2301.04796) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14155562576343532471&hl=en)

### 2023
- `IRG` [VS et al., Proc. CVPR 2023] **Instance relation graph guided source-free domain adaptive object detection** [[PDF]](https://arxiv.org/abs/2203.15793) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14769368441924132436&hl=en) [[CODE]](https://github.com/Vibashan/irg-sfda)

- `PETS` [Liu et al., Proc. ICCV 2023] **Periodically exchange teacher-student for source-free object detection** [[PDF]](https://openaccess.thecvf.com/content/ICCV2023/html/Liu_Periodically_Exchange_Teacher-Student_for_Source-Free_Object_Detection_ICCV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13076252047124330234&hl=en)

- `...` [Chen et al., Proc. ACMMM 2023] **Exploiting low-confidence pseudo-labels for source-free object detection** [[PDF]](https://arxiv.org/abs/2310.12705) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8417305377576787304&hl=en)

- `TeST` [Sinha et al., Proc. WACV 2023] **TeST: Test-time self-training under distribution shift** [[PDF]](https://arxiv.org/abs/2209.11459) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5034697452433918735&hl=en)

- `MemCLR` [VS et al., Proc. WACV 2023] **Towards online domain adaptive object detection** [[PDF]](https://openaccess.thecvf.com/content/WACV2023/html/VS_Towards_Online_Domain_Adaptive_Object_Detection_WACV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8996531248585805791&hl=en)

- `RPL` [Zhang et al., Proc. ICASSP 2023] **Refined pseudo labeling for source-free domain adaptive object detection** [[PDF]](https://arxiv.org/abs/2303.03728) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13997093408287471902&hl=en)

- `...` [Lin et al., Proc. ICME 2023] **Run and chase: Towards accurate source-free domain adaptive object detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10220039) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14484656647737119886&hl=en)

- `...` [Peng et al., Proc. ICANN 2023] **Gradient adjusted and weight rectified mean teacher for source-free object detection** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-44195-0_9) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14576125768769676685&hl=en)

  ---------------------

- `SFDA-STW` [Yang et al., IEEE TIM 2023] **Source-free domain adaptive detection of concealed objects in passive millimeter-wave images** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10019315/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11741376668369607853&hl=en)

- `MPG` [Zhang et al., IEEE T-IV 2023] **Multi-prototype guided source-free domain adaptive object detection for autonomous driving** [[PDF]](https://ieeexplore.ieee.org/document/10336548) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16990888552839762557&hl=en)
- 
- `A2SFOD` [Chu et al., arXiv 2023] **Adversarial alignment for source free object detection** [[PDF]](https://arxiv.org/abs/2301.04265) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3777004265512378062&hl=en)

- `...` [Naik et al., arXiv 2023] **Do machine learning models learn common sense?** [[PDF]](https://arxiv.org/abs/2303.01433) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11920731748225216277&hl=en)

- `...` [Sun et al., arXiv 2023] **SF-FSDA: Source-free few-shot domain adaptive object detection with efficient labeled data factory** [[PDF]](https://arxiv.org/abs/2306.04385) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8231756060316661911&hl=en)

- `...` [Shi et al., arXiv 2023] **Improving online source-free domain adaptation for object detection by unsupervised data acquisition** [[PDF]](https://arxiv.org/abs/2310.19258) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18439349657086663420&hl=en)

### 2024
- `LPLD` [Yoon et al., Proc. ECCV 2024] **Enhancing source-free domain adaptive object detection with low-confidence pseudo-label distillation** [[PDF]](https://arxiv.org/abs/2407.13524) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11533298948468001174&hl=en) [[CODE]](https://github.com/junia3/LPLD)

- `DRU` [Khanh et al., Proc. ECCV 2024] **Dynamic retraining-updating mean teacher for source-free object detection** [[PDF]](https://arxiv.org/abs/2407.16497) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7534375265139020140&hl=en) [[CODE]](https://github.com/lbktrinh/DRU)

- `STAR-MT` [Zhang and Zhou, Proc. CVPR Workshops 2024] **Source-free domain adaptation for video object detection under adverse image conditions** [[PDF]](https://arxiv.org/abs/2404.15252) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8777924463734083960&hl=en)

- `...` [Liu et al., Proc. IGARSS 2024] **CLIP-guided source-free object detection in aerial images** [[PDF]](https://arxiv.org/abs/2401.05168) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12573935687703695201&hl=en)

- `S3AHI` [Ding et al., Proc. IJCNN 2024] **S3AHI: Source-free domain adaptive small object detection with slicing aided hyper inference** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10651365/) [[G-Scholar--]]()

- `DACA` [Zhao et al., IJCV 2024] **Multi-source-free domain adaptive object detection** [[PDF]](https://link.springer.com/article/10.1007/s11263-024-02170-z) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5606598480931356106&hl=en)

- `...` [Deng et al., IEEE TCSVT 2024] **Balanced teacher for source-free object detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10466767/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6228066693565063340&hl=en)

- `...` [Liu et al., Geo-spatial Information Science 2024] **Multi-level domain perturbation for source-free object detection in remote sensing images** [[PDF]](https://www.tandfonline.com/doi/full/10.1080/10095020.2024.2378920/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1686166241501336740&hl=en)

- `RMT` [Tian et al., Alexandria Engineering Journal 2024] **A relation-enhanced mean-teacher framework for source-free domain adaptation of object detection** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1110016824016491) [[G-Scholar--]]()

- `...` [Liu et al., arXiv 2024] **Source-free domain adaptive object detection in remote sensing images** [[PDF]](https://arxiv.org/abs/2401.17916) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6757841461042013328&hl=en)

- `LPLDA` [Kim et al., IEEE Geoscience and Remote Sensing Letters 2025] **Source-free domain adaptation for remote-sensing object detection using low-confidence pseudo labels** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10949131/) [[G-Scholar--]]()

- `...` [Wei et al., The Journal of Supercomputing 2025] **Proposal-level reliable feature-guided contrastive learning for SFOD** [[PDF]](https://link.springer.com/article/10.1007/s11227-024-06773-8) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6757841461042013328&hl=en)

## Medical Image Analysis
### 2020
- `AdaEnt` [Bateson et al., Proc. MICCAI 2020] **Source-relaxed domain adaptation for image segmentation** [[PDF]](https://arxiv.org/abs/2005.03697) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10960624360275715336&hl=en) [[CODE]](https://github.com/mathilde-b/SFDA)

### 2021
- `OSUDA` [Liu et al., Proc. MICCAI 2021] **Adapting off-the-shelf source segmenter for target medical image segmentation** [[PDF]](https://arxiv.org/abs/2106.12497) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4743214793005635714&hl=en)

- `DPL` [Chen et al., Proc. MICCAI 2021] **Source-free domain adaptive fundus image segmentation with denoised pseudo-labeling** [[PDF]](https://arxiv.org/abs/2109.09735) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5523252323424851164&hl=en) [[CODE]](https://github.com/cchen-cc/SFDA-DPL)

### 2022
- `MetaTeacher` [Wang et al., Proc. NeurIPS 2022] **Metateacher: Coordinating multi-model domain adaptation for medical image classification** [[PDF]](https://openreview.net/forum?id=AQd4ugzALQ1) [[G-Scholar]](https://scholar.google.com/scholar?cluster=850871157744507452&hl=en) [[CODE]](https://github.com/wongzbb/metateacher)

- `SI-SFDA` [Ye et al., Proc. ACMMM 2022] **Alleviating style sensitivity then adapting: Source-free domain adaptation for medical image segmentation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3503161.3548426) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9012096844528437040&hl=en)

- `SDG-CMT` [Zhu et al., Proc. BIBM 2022] **Domain adaptation for medical image classification without source data** [[PDF]](https://ieeexplore.ieee.org/document/9995395) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17378616917759340812&hl=en)

- `SFS` [Stan and Rostami, Proc. BMVC 2022] **Domain adaptation for the segmentation of confidential medical images** [[PDF]](https://bmvc2022.mpi-inf.mpg.de/1007.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4915149265742081742&hl=en) 

- `U-D4R` [Xu et al., Proc. MICCAI 2022] **Denoising for relaxing: Unsupervised domain adaptive fundus image segmentation without source data** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_21) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1838996182983497541&hl=en)

- `APL` [Li et al., Proc. ICASSP 2022] **Adaptive pseudo labeling for source-free domain adaptation in medical image segmentation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9746286/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9796624921124267986&hl=en)

- `CST` [Xie et al., Proc. NeurIPS Workshops 2022] **Learn complementary pseudo-label for source-free domain adaptive medical segmentation** [[PDF]](https://nips.cc/media/PosterPDFs/NeurIPS%202022/63391.png?t=1668826536.1747398) [[G-Scholar--]]()

- `FUSION` [Chattopadhyay et al., Proc. ECCV Workshops 2022] **FUSION: Fully unsupervised test-time stain adaptation via fused normalization statistics** [[PDF]](https://arxiv.org/abs/2208.14206) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13067331829363611585&hl=en)

  ----------------------------

- `SMPT++` [Liu and Yuan, IEEE TMI 2022] **A source-free domain adaptive polyp detection framework with style diversification flow** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9709278) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16349070323060558698&hl=en) [[CODE]](https://github.com/CityU-AIM-Group/SFPolypDA)

- `AdaMI` [Bateson et al., Medical Image Analysis 2022] **Source-free domain adaptation for image segmentation** [[PDF]](https://arxiv.org/abs/2108.03152) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12042927660451182827&hl=en) [[CODE]](https://github.com/mathilde-b/SFDA)

- `MCOSUDA` [Liu et al., Medical Image Analysis 2022] **Memory consistent unsupervised off-the-shelf model adaptation for source-relaxed medical image segmentation** [[PDF]](https://arxiv.org/abs/2209.07910) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9119513985040151191&hl=en)

- `SFDA-FSM` [Yang et al., Medical Image Analysis 2022] **Source free domain adaptation for medical image segmentation with fourier style mining** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1361841522001049) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10888890131405074459&hl=en) [[CODE]](https://github.com/CityU-AIM-Group/SFDA-FSM)

- `PPMSDA` [Han et al., IEEE JBHI 2022] **Privacy-preserving multi-source domain adaptation for medical data** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9779659/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14847947614110691197&hl=en)

- `AOS` [Hong et al., Knowledge-Based Systems 2022] **Source-free unsupervised domain adaptation for cross-modality abdominal multi-organ segmentation** [[PDF]](https://arxiv.org/abs/2111.12221) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2407109364110005916&hl=en) [[CODE]](https://github.com/Captain-Hong/SFUDA_AOS)

- `PSMT` [Wei et al., Journal of Supercomputing 2022] **Source-free domain adaptive object detection based on pseudo-supervised mean teacher** [[PDF]](https://link.springer.com/article/10.1007/s11227-022-04915-4) [[G-Scholar--]]()

- `BBUDA-EMD` [Liu et al., Frontiers in Neuroscience 2022] **Unsupervised black-box model domain adaptation for brain tumor segmentation** [[PDF]](https://www.frontiersin.org/articles/10.3389/fnins.2022.837646/full?amp;amp) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8709673335885735259&hl=en)
  
  ~~[Liu et al., Proc. SPIE Medical Imaging 2022] **Unsupervised domain adaptation for segmentation with black-box source model** [[PDF]](https://arxiv.org/abs/2208.07769)~~

- `TT-SFUDA` [VS et al., arXiv 2022] **Target and task specific source-free domain adaptive image segmentation** [[PDF]](https://arxiv.org/abs/2203.15792) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17947897479931623051&hl=en) [[CODE]](https://github.com/Vibashan/tt-sfuda)

- `SFDA-NS` [Kondo, arXiv 2022] **Source-free unsupervised domain adaptation with norm and shape constraints for medical image segmentation** [[PDF]](https://arxiv.org/abs/2209.01300) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11603944637647696822&hl=en)

- `ProSFDA` [Hu et al., arXiv 2022] **ProSFDA: Prompt learning based source-free domain adaptation for medical image segmentation** [[PDF]](https://arxiv.org/abs/2211.11514) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15541289658900461005&hl=en) [[CODE]](https://github.com/ShishuaiHu/ProSFDA)

- `IOP-FL` [Jiang et al., arXiv 2022] **IOP-FL: Inside-outside personalization for federated medical image segmentation** [[PDF]](https://arxiv.org/abs/2204.08467) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10670356016526924774&hl=en)

- `SFDA-GEM` [Yuan et al., Misc 2022] **Source protection domain adaptation by gumbel-min-max entropy minimization** [[PDF]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4220604) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12468488454287850515&hl=en)

- `PLP` [Song, Misc 2022] **Source-free few-shot semi-supervised domain adaptation for CT image classification** [[PDF]](https://arxiv.org/abs/2207.08124) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2138500387139877671&hl=en)

- `...` [Li et al., Misc 2022] **Source-free unsupervised adaptive segmentation for knee joint MRI** [[PDF]](https://www.techrxiv.org/articles/preprint/Source-free_Unsupervised_Adaptive_Segmentation_for_Knee_Joint_MRI/21749414) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13776259422469947288&hl=en)

### 2023
- `SFHarmony` [Dinsdale et al., Proc. ICCV 2023] **SFHarmony: Source free domain adaptation for distributed neuroimaging analysis** [[PDF]](https://arxiv.org/abs/2303.15965) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10161228220420913117&hl=en) [[CODE]](https://github.com/nkdinsdale/SFHarmony)

- `SUMT` [Wen et al., Proc. IPMI 2023] **Source-free domain adaptation for medical image segmentation via selectively updated mean teacher** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-34048-2_18) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8075738409234807110&hl=en)

- `UPL-TTA` [Wu et al., Proc. IPMI 2023] **UPL-TTA: Uncertainty-aware pseudo label guided fully test time adaptation for fetal brain segmentation** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-34048-2_19) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16754295285142401028&hl=en)

- `RPANet` [Wang and Chen, Proc. IPMI 2023] **Unsupervised adaptation of polyp segmentation models via coarse-to-fine self-supervision** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-34048-2_20) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1578571642037964508&hl=en)

- `CBMT` [Tang et al., Proc. MICCAI 2023] **Source-free domain adaptive fundus image
segmentation with class-balanced mean teacher** [[PDF]](https://arxiv.org/abs/2307.09973) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9906534363863364991&hl=en) [[CODE]](https://github.com/lloongx/SFDA-CBMT)

- `ProtoContra` [Yu et al., Proc. MICCAI 2023] **Source-free domain adaptation for medical image segmentation via prototype-anchored feature alignment and contrastive learning** [[PDF]](https://arxiv.org/abs/2307.09769) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14419826051141724029&hl=en) [[CODE]](https://github.com/CSCYQJ/MICCAI23-ProtoContra-SFDA)

- `SaTTCA` [Li et al., Proc. MICCAI 2023] **Scale-aware test-time click adaptation for pulmonary nodule and mass segmentation** [[PDF]](https://arxiv.org/abs/2307.15645) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9068452184184040569&hl=en) [[CODE]](https://github.com/SplinterLi/SaTTCA)

- `CPR` [Huai et al., Proc. MICCAI 2023] **Context-aware pseudo-label refinement for source-free domain adaptive fundus image segmentation** [[PDF]](https://arxiv.org/abs/2308.07731) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2879793886454783206&hl=en) [[CODE]](https://github.com/xmed-lab/CPR)

- `...` [Wang et al., Proc. MICCAI 2023] **Black-box domain adaptative cell segmentation via multi-source distillation** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-43907-0_71) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13606280343267908782&hl=en) [[CODE]](https://github.com/NeuronXJTU/MBDA-CellSeg)

- `TGMA` [Yang et al., Proc. MICCAI 2023] **Transferability-guided multi-source model adaptation for medical image segmentation** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-43895-0_66) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7729218250887421054&hl=en) 

- `...` [Lee et al., Proc. MICCAI 2023] **Self-supervised domain adaptive segmentation of breast cancer via test-time fine-tuning** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-43907-0_52) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16580935026141696741&hl=en) 

- `...` [Kondo, Proc. MICCAI Workshops 2023] **Black-box unsupervised domain adaptation for medical image segmentationt** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-45857-6_3) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2631680388442741813&hl=en)

- `...` [Yuan et al., Proc. EMBC 2023] **Entropy-driven adversarial training for source-free medical image segmentation** [[PDF]](https://arinex.com.au/EMBC/pdf/full-paper_228.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15852246687192396998&hl=en)

- `MATS` [Chen et al., Proc. MIDL 2023] **Model adaptive tooth segmentation** [[PDF]](https://openreview.net/forum?id=O2DerS5oQ1) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14510692842514020867&hl=en)

- `...` [Wang et al., Proc. CMMCA 2023] **Advancing delineation of gross tumor volume based on magnetic resonance imaging by performing source-free domain adaptation in nasopharyngeal carcinoma** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-45087-7_8) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15174580942678325244&hl=en)

- `...` [Zhang et al., Proc. ICCECE 2023] **Source-free domain adaptation via multicentric prototype for alzheimer's disease detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10135388/) [[G-Scholar--]]()

- `...` [Xu et al., Proc. AI 2023] **Cross domain pulmonary nodule detection without source data** [[PDF]](https://link.springer.com/chapter/10.1007/978-981-99-8388-9_13) [[G-Scholar--]]()

  ----------------------------

- `...` [Li et al., IEEE TMI 2023] **Towards source-free cross tissues histopathological cell segmentation via target-specific finetuning** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10087318) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5356003107098200108&hl=en) [[CODE]](https://github.com/NeuronXJTU/SFDA-CellSeg)

- `UPL-SFDA` [Wu et al., IEEE TMI 2023] **UPL-SFDA: Uncertainty-aware pseudo label guided source-free domain adaptation for medical image segmentation** [[PDF]](https://arxiv.org/abs/2309.10244) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7117635234828682903&hl=en)

- `SAME` [Li et al., IEEE TMI 2023] **Enhancing and adapting in the clinic: Source-free unsupervised domain adaptation for medical image enhancement** [[PDF]](https://ieeexplore.ieee.org/document/10330609) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4229949942064215100&hl=en) [[CODE]](https://github.com/liamheng/Annotation-free-Medical-Image-Enhancement)

- `DUT` [Liu et al., IEEE TNNLS 2023] **Decoupled unbiased teacher for source-free
domain adaptive medical object detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10128698) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5394961859696758606&hl=en) [[CODE]](https://github.com/CUHK-AIM-Group/Decoupled-Unbiased-Teacher)

- `DCGP-KD` [Cheng et al., IEEE TAI 2023] **Domain-centroid-guided progressive teacher-based knowledge distillation for source-free domain adaptation of histopathological images** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10218991) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15777124283638781368&hl=en)

- `SCD` [Zhou et al., Computers in Biology and Medicine 2023] **Superpixel-guided class-level denoising for unsupervised domain adaptive fundus image segmentation without source data** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0010482523005267) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14733171849301790547&hl=en)

- `CP3Net` [Feng et al., Knowledge-Based Systems 2023] **Cross-platform privacy-preserving CT image COVID-19 diagnosis based on source-free domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0950705123000746) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13133706915130616700&hl=en)

- `CBCOST` [Huang et al., Artificial Intelligence in Medicine 2023] **Source-free domain adaptive segmentation with class-balanced complementary self-training** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0933365723002087) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5080918322211579969&hl=en)

- `RAF` [Yuan et al., The Visual Computer 2023] **Data privacy protection domain adaptation by roughing and finishing stage** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1000936123000493) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8761702195802826554&hl=en)

- `...` [Wang et al., Health Information Science and Systems 2023] **M-MSSEU: Source-free domain adaptation for multi-modal stroke lesion segmentation using shadowed sets and evidential uncertainty** [[PDF]](https://link.springer.com/article/10.1007/s13755-023-00247-6) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3841179597098584563&hl=en)

- `...` [Li et al., IEEE Open Journal of Signal Processing 2023] **Source-data-free cross-domain knowledge transfer for semantic segmentation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10356748) [[G-Scholar--]]()

- `SUP` [Xu et al., arXiv 2023] **Unsupervised cross-domain pulmonary nodule detection without source data** [[PDF]](https://arxiv.org/abs/2304.01085) [[G-Scholar]](https://scholar.google.com/scholar?cluster=682584010073333489&hl=en)

- `MAME` [Dong et al., arXiv 2023] **Tailored multi-organ segmentation with model adaptation and ensemble** [[PDF]](https://arxiv.org/abs/2304.07123) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14131204124314101901&hl=en) 

- `FVP` [Wang et al., arXiv 2023] **FVP: Fourier visual prompting for source-free unsupervised domain adaptation of medical image segmentation** [[PDF]](https://arxiv.org/abs/2304.13672) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6237066515904238911&hl=en) 

- `...` [Wang et al., arXiv 2023] **Black-box source-free domain adaptation via two-stage knowledge distillation** [[PDF]](https://arxiv.org/abs/2305.07881) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6418607013299083420&hl=en&as_sdt=0,5) 

- `SL` [Chen and Wang, arXiv 2023] **SL: Stable learning in source-free domain adaption for medical image segmentation** [[PDF]](https://arxiv.org/abs/2307.12580) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6336157499980091582&hl=en&as_sdt=0,5) 

- `SCDA` [Fang et al., arXiv 2023] **Source-free collaborative domain adaptation via multi-perspective feature enrichment for functional MRI analysis** [[PDF]](https://arxiv.org/abs/2308.12495) [[G-Scholar]](https://scholar.google.com/scholar?cluster=348365801739482490&hl=en)

- `LGDA` [Ye et al., arXiv 2023] **Local-global pseudo-label correction for source-free domain adaptive medical image segmentation** [[PDF]](https://arxiv.org/abs/2308.14312) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14525675125862110265&hl=en)

- `SFADA` [Ran et al., arXiv 2023] **Source-free active domain adaptation for diabetic retinopathy grading based on ultra-wide-field fundus image** [[PDF]](https://arxiv.org/abs/2309.10619) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1090372294966552960&hl=en) [[CODE]](https://github.com/JinyeRAN/SFADA)

- `...` [Wang et al., arXiv 2023] **Dual-reference source-free active domain adaptation for nasopharyngeal carcinoma tumor segmentation across multiple hospitals** [[PDF]](https://arxiv.org/abs/2309.13401) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2322742421309410339&hl=en) [[CODE--]](https://github.com/whq-xxh/Active-GTV-Seg)

- `...` [Hu et al., arXiv 2023] **A chebyshev confidence guided source-free domain adaptation framework for medical image segmentation** [[PDF]](https://arxiv.org/abs/2310.18087) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15144390973634913542&hl=en)

- `PD` [Rafiee et al., Misc 2023] **Diversified source-free domain adaptation** [[PDF]](https://openreview.net/forum?id=Ot0KorOlyl) [[G-Scholar--]]()

- `...` [Pourreza., Master Thesis 2023] **Open-set source-free domain adaptation in fundus images analysis** [[PDF]](https://ir.lib.uwo.ca/cgi/viewcontent.cgi?article=11898&context=etd) [[G-Scholar--]]()

### 2024
- `SF-UT` [Hao et al., Proc. ECCV 2024] **Simplifying source-free domain adaptation for object detection: Effective self-training strategies and performance insights** [[PDF]](https://arxiv.org/abs/2407.07586) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8647739709393243478&hl=en) [[CODE]](https://github.com/EPFL-IMOS/simple-SFOD)

- `PLPB` [Li et al., Proc. WACV 2024] **Robust source-free domain adaptation for fundus image segmentation** [[PDF]](https://arxiv.org/abs/2310.16665) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14362854508610886433&hl=en) [[CODE]](https://github.com/LinGrayy/PLPB)

- `...` [Guichemerre et al., Proc. CVPR Workshops 2024] **Source-free domain adaptation of weakly-supervised object localization models for histology** [[PDF]](https://arxiv.org/abs/2404.19113) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11764162416449308542&hl=en) [[CODE]](https://github.com/AlexisGuichemerreCode/survey_hist_wsol_sfda)

- `RSA` [Zeng et al., Proc. MICCAI 2024] **Reliable source approximation: Source-free unsupervised domain adaptation for vestibular schwannoma MRI segmentation** [[PDF]](https://arxiv.org/abs/2405.16102) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15313961143347598441&hl=en) [[CODE]](https://github.com/zenghy96/Reliable-Source-Approximation)

- `IPLC` [Zhang et al., Proc. MICCAI 2024] **IPLC: Iterative pseudo label correction guided by SAM for source-free domain adaptation in medical image segmentation** [[PDF]](https://papers.miccai.org/miccai-2024/paper/1958_paper.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4930976709266432359&hl=en) [[CODE]](https://github.com/HiLab-git/IPLC)

- `D2SFDA` [Zhou et al., Proc. BIBM 2024] **Diffusion-driven dual-flow source-free domain adaptation for medical image segmentation** [[PDF]](https://www.computer.org/csdl/proceedings-article/bibm/2024/10821827/23onB5pMJBC) [[G-Scholar--]]() [[CODE--]](https://github.com/M4cheal/D2SFDA)

- `A-SFUDA` [Zhang et al., Proc. CAI 2024] **Asymmetric source-free unsupervised domain adaptation for medical image diagnosis** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10605586/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11507737389431698095&hl=en)

- `...` [Nakhaei et al., Proc. SPIE Medical Imaging 2024] **Refining boundaries of the segment anything model in medical images using an active contour model** [[PDF]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12927/1292734/Refining-boundaries-of-the-segment-anything-model-in-medical-images/10.1117/12.3006255.short) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2412331644154163819&hl=en)

- `Distill-SODA` [Vray et al., IEEE TMI 2024] **Distill-SODA: Distilling self-supervised vision transformer for source-free open-set domain adaptation in computational pathology** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10403873)  [[G-Scholar]](https://scholar.google.com/scholar?cluster=14471489511816927773&hl=en) [[CODE]](https://github.com/LTS5/Distill-SODA)

- `MS-MATS` [Chen et al., Medical Image Analysis 2024] **Cross-center model adaptive tooth segmentation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1361841524003682) [[G-Scholar--]]()

- `...` [Yin et al., Scientific Reports 2024] **Source free domain adaptation for kidney and tumor image segmentation with wavelet style mining** [[PDF]](https://www.nature.com/articles/s41598-024-75972-3) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15999060855296565676&hl=en)

- `CCMT` [Zhang et al., Neurocomputing 2024] **Source-free domain adaptation framework based on confidence constrained mean teacher for fundus image segmentation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0925231224020332) [[G-Scholar--]]()

- `UCDA` [Yu and Pei et al., Applied Sciences 2024] **Uncertainty-guided asymmetric consistency domain adaptation for histopathological image classification** [[PDF]](https://www.mdpi.com/2076-3417/14/7/2900)  [[G-Scholar]](https://scholar.google.com/scholar?cluster=2119962835455490279&hl=en)

- `...` [Liu and Jiao, Biomedical Engineering Letters 2024] **Cross-domain additive learning of new knowledge rather than replacement** [[PDF]](https://link.springer.com/article/10.1007/s13534-024-00399-8) [[G-Scholar--]]()

- `...` [Zhang et al., International Journal of Ophthalmology 2024] **Diabetic retinopathy identification based on multi-source-free domain adaptation** [[PDF]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11246935/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9166609315682439482&hl=en)

- `VP-SFDA` [Chen et al., Health Data Science 2024] **VP-SFDA: Visual prompt source-free domain adaptation for cross-modal medical image** [[PDF]](https://spj.science.org/doi/pdf/10.34133/hds.0143) [[G-Scholar--]]()

- `UniFed` [Dinsdale et al., arXiv 2024] **UniFed: A unified deep learning framework for segmentation of partially labelled, distributed neuroimaging data** [[PDF]](https://www.biorxiv.org/content/10.1101/2024.02.05.578912v1.abstract) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10410788971059392258&hl=en)

- `DyNA` [Chen et al., arXiv 2024] **Day-night adaptation: An innovative source-free adaptation framework for medical image segmentation** [[PDF]](https://arxiv.org/abs/2410.13472) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8896829600509695972&hl=en)

- `...` [Sun and  Rostami, arXiv 2024] **Cross-domain distribution alignment for segmentation of private unannotated 3D medical Images** [[PDF]](https://arxiv.org/abs/2410.09210) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15303510450833492450&hl=en)

- `...` [Peralta et al., Misc 2024] **Source-free domain adaptation for improving medical image quality in clinical applications** [[PDF]](https://www.researchgate.net/publication/385659625_Source-Free_Domain_Adaptation_for_Improving_Medical_Image_Quality_in_Clinical_Applications) [[G-Scholar--]]()

### 2025
- `AIF-SFDA` [Li et al., Proc. AAAI 2025] **AIF-SFDA: Autonomous information filter-driven source-free domain adaptation for medical image segmentation** [[PDF]](https://arxiv.org/abs/2501.03074) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17692708446747663719&hl=en) [[CODE]](https://github.com/JingHuaMan/AIF-SFDA)

- `...` [Oda et al., Proc. IWAIT 2025] **Strict source-free domain adaptation with simple assumptions for cardiac segmentation** [[PDF]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13510/1351007/Strict-source-free-domain-adaptation-with-simple-assumptions-for-cardiac/10.1117/12.3057249.short) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18286509675007678391&hl=en)

- `...` [Zhang et al., Medical Image Analysis 2025] **Enhancing source-free domain adaptation in medical image segmentation via regulated model self-training** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1361841525000908) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4313468517098520011&hl=en)

- `...` [Soylu et al., IEEE TBME 2025] **Migration of deep learning models across ultrasound scanners** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10977778/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3359585114202157563&hl=en)

- `MPPL-SFDA` [Zhang et al., Biomedical Signal Processing and Control 2025] **Multicentric prototype and pseudo-labeling based source-free domain adaptation for Alzheimer's disease classification** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1746809424015416) [[G-Scholar--]]()

- `C2MAL` [Zhou et al., Medical & Biological Engineering & Computing 2025] **C2MAL: Cascaded network-guided class-balanced multi-prototype auxiliary learning for source-free domain adaptive medical image segmentation** [[PDF]](https://link.springer.com/article/10.1007/s11517-025-03287-0) [[G-Scholar--]]()

## Video Classification
### 2022
- `ATCoN` [Xu et al., Proc. ECCV 2022] **Learning temporal consistency for source-free video domain adaptation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940144.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4238691108482542310&hl=en) [[CODE]](https://github.com/xuyu0010/ATCoN)

- `MTRAN` [Huang et al., Proc. ACMMM 2022] **Relative alignment network for source-free multimodal video domain adaptation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3503161.3548009) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16061407528461480325&hl=en)

- `SFTADA` [Chen and Ma, Proc. ICMR 2022] **Source-free temporal attentive domain adaptation for video action recognition** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3512527.3531392) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14618082401482357386&hl=en)

- `RNA++` [Plananamente et al., Proc. ICIAP 2022] **Test-time adaptation for egocentric action recognition** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-06433-3_18) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2806024882988284863&hl=en) [[CODE]](https://github.com/EgocentricVision/RNA-TTA)

- `CleanAdapt` [Dasgupta et al., Proc. ICVGIP 2022] **Overcoming label noise for source-free unsupervised video domain adaptation** [[PDF]](https://hal.science/hal-03929619/document) [[G-Scholar]](https://scholar.google.com/scholar?cluster=623684659834620344&hl=en)

### 2023
- `STHC` [Li et al., Proc. CVPR 2023] **Source-free video domain adaptation with spatial-temporal-historical consistency learning** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Source-Free_Video_Domain_Adaptation_With_Spatial-Temporal-Historical_Consistency_Learning_CVPR_2023_paper.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6519226237067497793&hl=en) 

- `DALL-V` [Zara et al., Proc. ICCV 2023] **The unreasonable effectiveness of large language-vision models for source-free video domain adaptation** [[PDF]](https://arxiv.org/abs/2308.09139) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18439349657086663420&hl=en) [[CODE]](https://github.com/giaczara/dallv)

- `LCMV` [Neubert et al., Proc. ICIAP 2023] **LCMV: Lightweight classification module for video domain adaptation** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-43153-1_23) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11153014118790552510&hl=en)

- `...` [Neubert., Master Thesis 2023] **Source-free domain adaptation for video action recognition** [[PDF]](https://webthesis.biblio.polito.it/secure/26775/1/tesi.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9953124906512607690&hl=en)

- `CleanAdapt` [Dasgupta et al., Misc 2024] **Source-free video domain adaptation by learning from noisy labels** [[PDF]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4832737) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15914376423884787323&hl=en) [[CODE]](https://github.com/avijit9/CleanAdapt)

- `CleanAdapt+TS` [Neubert et al., Pattern Recognition 2025] **Source-free video domain adaptation by learning from noisy labels** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320324010793) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15914376423884787323&hl=en) [[CODE]](https://github.com/avijit9/CleanAdapt)

- `Co-STAR` [Dadashzadeh et al., arXiv 2025] **Co-STAR: Collaborative curriculum self-training with adaptive regularization for source-free video domain adaptation** [[PDF]](https://arxiv.org/abs/2504.11669) [[G-Scholar--]]() [[CODE--]](https://github.com/Plrbear/Co-Star)

- `...` [Zara, Master Thesis 2025] **Human action recognition in the real world: handling domain shift in open-set, source-free and multi-source scenarios** [[PDF]](https://iris.unitn.it/handle/11572/443511) [[G-Scholar]](https://scholar.google.com/scholar?cluster=739977252216400299&hl=en)

## 3D Perception
### 3D Object Detection
- `SF-UDA3D` [Saltori et al., Proc. 3DV 2020] **SF-UDA3D: Source-free unsupervised domain adaptation for lidar-based 3d object detection** [[PDF]](https://arxiv.org/abs/2010.08243) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12668139134909180101&hl=en) [[CODE]](https://github.com/saltoricristiano/SF-UDA-3DV)

- `ST3D` [Yang et al., Proc. CVPR 2021] **ST3D: Self-training for unsupervised domain adaptation on 3d object detection** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Yang_ST3D_Self-Training_for_Unsupervised_Domain_Adaptation_on_3D_Object_Detection_CVPR_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12232176416755323092&hl=en) [[CODE]](https://github.com/CVMI-Lab/ST3D)

- `Dreaming` [You et al., Proc. ICRA 2022] **Exploiting playbacks in unsupervised domain adaptation for 3d object detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9811722/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2067943135953406159&hl=en)

- `UAMT` [Hegde et al., Proc. ICRA 2023] **Source-free unsupervised domain adaptation for 3D object detection in adverse weather** [[PDF]](https://ieeexplore.ieee.org/document/10161341/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15152098937042722440&hl=en) [[CODE]](https://github.com/deeptibhegde/UncertaintyAwareMeanTeacher)

  ~~ [Hegde et al., arXiv 2021] **Uncertainty-aware mean teacher for source-free unsupervised domain adaptive 3d object detection** [[PDF]](https://arxiv.org/abs/2109.14651) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15247976641359211271&hl=en) [[CODE]](https://github.com/deeptibhegde/UncertaintyAwareMeanTeacher)~~

- `AP-SFDA` [Hegde et al., Proc. WACV 2024] **Attentive prototypes for source-free unsupervised domain adaptive 3d object detection** [[PDF]](https://arxiv.org/abs/2111.15656) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4281673598628254257&hl=en) [[CODE]](https://github.com/deeptibhegde/AttentivePrototypeSFUDA)

### 3D Pose Estimation
- `Anat-SFDA` [Bigalke et al., arXiv 2022] **Anatomy-guided domain adaptation for 3D in-bed human pose estimation** [[PDF]](https://arxiv.org/abs/2211.12193) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5720884605736008576&hl=en) [[CODE]](https://github.com/multimodallearning/da-3dhpe-anatomy)

### 3D Lidar Segmentation
- `GIPSO` [Saltori et al., Proc. ECCV 2022] **GIPSO: Geometrically informed propagation for online adaptation in 3d lidar segmentation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930557.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13813760731976228346&hl=en) [[CODE]](https://github.com/saltoricristiano/gipso-sfouda)

- `LiDAR-UDA` [Shaban et al., Proc. ICCV 2023] **LiDAR-UDA: Self-ensembling through time for unsupervised LiDAR domain adaptation** [[PDF]](https://arxiv.org/abs/2309.13523) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3023674887678953347&hl=en) [[CODE]](https://github.com/JHLee0513/LiDARUDA)

- `TTYD` [Michele et al., Proc. ECCV 2024] **Train till you drop: Towards stable and robust source-free unsupervised 3D domain adaptation** [[PDF]](https://arxiv.org/abs/2409.04409) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16485874495803986516&hl=en) [[CODE]](https://github.com/valeoai/TTYD)

- `TGSF` [Duan et al., Proc. ICME 2024] **Source-free domain adaptation for point cloud semantic segmentation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10687489/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6688461912906131608&hl=en) 

### 3D Lidar Recognition
- `GeoAdapt` [Knights et al., IEEE Robotics and Automation Letters 2023] **GeoAdapt: Self-supervised test-time adaptation in LiDAR place recognition using geometric priors** [[PDF]](https://arxiv.org/abs/2308.04638) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16846487955556908782&hl=en) [[CODE--]](https://github.com/csiro-robotics/GeoAdapt)

### 3D Pose Estimation
- `...` [Kaushik et al., Proc. ICLR 2024] **Source-free and image-only unsupervised domain adaptation for category level object pose estimation** [[PDF]](https://openreview.net/forum?id=UPvufoBAIs) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7622273541116368780&hl=en)

## Facial Analysis
### Face Anti-spoofing
- `AdaptML` [Wang et al., Proc. AAAI 2021] **Self-domain adaptation for face anti-spoofing** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/16379) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11751431376596364916&hl=en)

- `Self-Ensemble` [Lv et al., Proc. ICASSP 2021] **Combining dynamic image and prediction ensemble for cross-domain face anti-spoofing** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9413926/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13575521535806939327&hl=en)

- `GDA` [Zhou et al., Proc. ECCV 2022] **Generative domain adaptation for face anti-spoofing** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650328.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11917164576597623324&hl=en)

- `SDA-FAS` [Liu et al., Proc. ECCV 2022] **Source-free domain adaptation with contrastive domain alignment and self-supervised exploration for face anti-spoofing** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720506.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13216320534230331303&hl=en) [[CODE]](https://github.com/YuchenLiu98/ECCV2022-SDA-FAS)

- `SDA-FAS++` [Liu et al., IEEE TPAMI 2024] **Source-free domain adaptation with domain generalized pretraining for face anti-spoofing** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10449373) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6628630424057197693&hl=en)

- `OTA` [Li et al.,  arXiv 2025] **Optimal transport-guided source-free adaptation for face anti-spoofing** [[PDF]](https://arxiv.org/abs/2503.22984) [[G-Scholar--]]()

### Occluded Face Recognition
- `SFOFR` [Zhang et al., Proc. ICASSP 2022] **Free lunch for cross-domain occluded face recognition without source data** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9746642/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11652130877492418578&hl=en)

### Facial Expression Recognition
- `CluP` [Conti et al., Proc. BMVC 2022] **Cluster-level pseudo-labelling for source-free cross-domain facial expression recognition** [[PDF]](https://bmvc2022.mpi-inf.mpg.de/0486.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6739844971812107667&hl=en) [[CODE]](https://github.com/altndrr/clup)

- `LTVAL` [Guo et al., Multimedia Tools and Applications 2023] **LTVAL: Label transfer virtual adversarial learning framework for source-free facial expression recognition** [[PDF]](https://link.springer.com/article/10.1007/s11042-023-15297-x) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4189974368646562589&hl=en)

- `DSFDA` [Sharafi et al., Proc. FG 2025] **Disentangled source-free personalization for facial expression recognition with neutral target data** [[PDF]](https://arxiv.org/abs/2503.20771) [[G-Scholar--]]() [[CODE]](https://github.com/MasoumehSharafi/DSFDA-for-Pain-Assessment)

### Face forgery detection
- `...` [Xu et al., CVIU 2024] **Uncertainty guided test-time training for face forgery detection** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1077314224002662) [[G-Scholar--]]()

### Visual Emotion Recognition
- `BBA` [Zhu et al., Proc. AAAI 2025] **Bridge then begin anew: Generating target-relevant intermediate model for source-free visual emotion adaptation** [[PDF]](https://arxiv.org/abs/2412.13577) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15291681000096552828&hl=en) [[CODE]](https://github.com/zhuzhu804/BBA)

- `FAL` [Zheng et al., arXiv 2025] **Fuzzy-aware loss for source-free domain adaptation in visual emotion recognition** [[PDF]](https://arxiv.org/abs/2501.15519) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11497093528770730532&hl=en) 

## Other CV Applications
### Person ReID
- `MtASD` [Wu et al., Proc. CVPR 2019] **Distilled person re-identification: Towards a more scalable system** [[PDF]](https://openaccess.thecvf.com/content_CVPR_2019/html/Wu_Distilled_Person_Re-Identification_Towards_a_More_Scalable_System_CVPR_2019_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4580639918930348414&hl=en)

- `MSFDA-PT` [Ding et al., The Visual Computer 2021] **Source-free unsupervised multi-source domain adaptation via proxy task for person re-identification** [[PDF]](https://link.springer.com/article/10.1007/s00371-021-02246-8) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17612309789629474685&hl=en)

- `...` [Song et al., Applied Sciences 2023] **Unsupervised vehicle re-identification method based on source-free knowledge transfer** [[PDF]](https://www.mdpi.com/2076-3417/13/19/11013) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3692002900286986347&hl=en)

- `S2ADAP` [Qu et al., Knowledge-Based Systems 2023] **Source-free style-diversity adversarial domain adaptation with privacy-preservation for person re-identification** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0950705123009000) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18323410649227535346&hl=en)

- `IAMT` [Qu et al., ACM TOMM 2024] **Instance-level adversarial source-free domain adaptive person re-identification** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3649900) [[G-Scholar--]]()

- `AAMT` [Qu et al., IEEE TMM 2024] **AAMT: Adversarial attack-driven mutual teaching for source-free domain-adaptive person reidentification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10475539/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1116489178484008905&hl=en)

- `SFPS` [Yan et al., Pattern Recognition 2025] **Source-free domain adaptive person search** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320324010689) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11553475249890518895&hl=en)

### Multi-modality
- `SOCKET` [Ahmed et al., Proc. ECCV 2022] **Cross-modal knowledge transfer without task-relevant source data** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940108.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8131184106801888753&hl=en) [[CODE]](https://github.com/merlresearch/SOCKET)

- `PopNet` [Wu et al., arXiv 2022] **Source-free depth for object pop-out** [[PDF]](https://arxiv.org/abs/2212.05370) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14863581017412360599&hl=en) [[CODE--]](https://github.com/Zongwei97/PopNet)

- `UPL` [Huang et al., arXiv 2022] **Unsupervised prompt learning for vision-language models** [[PDF]](https://arxiv.org/abs/2204.03649) [[G-Scholar]](https://scholar.google.com/scholar?cluster=957051867909380413&hl=en) [[CODE]](https://github.com/tonyhuang2022/UPL)

- `POUF` [Tanwisuth et al., Proc. ICML 2023] **POUF: Prompt-oriented unsupervised fine-tuning for large pre-trained models** [[PDF]](https://arxiv.org/abs/2305.00350) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13206932361048138270&hl=en) [[CODE]](https://github.com/korawat-tanwisuth/POUF)

- `SUMMIT` [Simons et al., Proc. ICCV 2023] **SUMMIT: Source-free adaptation of uni-modal models to multi-modal targets** [[PDF]](https://arxiv.org/abs/2308.11880) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11393512066880928622&hl=en) [[CODE]](https://github.com/csimo005/SUMMIT)

- `CDUL` [Abdelfattah et al., Proc. ICCV 2023] **CDUL: CLIP-driven unsupervised learning for multi-label image classification** [[PDF]](https://openaccess.thecvf.com/content/ICCV2023/html/Abdelfattah_CDUL_CLIP-Driven_Unsupervised_Learning_for_Multi-Label_Image_Classification_ICCV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10923615722465272903&hl=en) [[CODE]](https://github.com/cs-mshah/CDUL)

- `MISFIT` [Rizzoli et al., arXiv 2023] **Source-free domain adaptation for RGB-D semantic segmentation with vision transformers** [[PDF]](https://arxiv.org/abs/2305.14269) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1106788040715184555&hl=en)

- `CPL` [Zhang et al., Proc. ICML 2024] **Candidate pseudolabel learning: Enhancing vision-language models by prompt tuning with unlabeled data** [[PDF]](https://openreview.net/forum?id=sBJNokmYuV) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13370731097677354084&hl=en) [[CODE]](https://github.com/vanillaer/Candidate_Pseudolabel_Learning-ICML2024)

- `FPL/GRIP` [Menghini et al., Proc. NeurIPS 2024] **Enhancing CLIP with CLIP: Exploring pseudolabeling for limited-label prompt tuning** [[PDF]](https://openreview.net/forum?id=2b9aY2NgXE) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9071158111110701723&hl=en) [[CODE]](https://github.com/BatsResearch/menghini-neurips23-code)

- `Frolic` [Zhu et al., Proc. NeurIPS 2024] **Enhancing zero-shot vision models by label-free prompt distribution learning and bias correcting** [[PDF]](https://arxiv.org/abs/2410.19294) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4323282939757350124&hl=en) [[CODE--]](https://github.com/zhuhsingyuu/Frolic)

- `EventDance` [Zheng and Wang, Proc. CVPR 2024] **EventDance: Unsupervised source-free cross-modal adaptation for event-based object recognition** [[PDF]](https://arxiv.org/abs/2403.14082) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6946776143159713482&hl=en)

- `ZLaP` [Stojnić et al., Proc. CVPR 2024] **Label propagation for zero-shot classification with vision-language models** [[PDF]](https://arxiv.org/abs/2404.04072) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3792709328276280732&hl=en) [[CODE]](https://github.com/vladan-stojnic/ZLaP)

- `uCAP` [Nguyen et al., Proc. ECCV 2024] **uCAP: An unsupervised prompting method for vision-language models** [[PDF]](https://atuannguyen.com/assets/pdf/nguyen2024ucap.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15602846846448616966&hl=en)

- `NtUA` [Ali and Khan, Proc. ECCV 2024] **Noise-tolerant few-shot unsupervised adapter for vision-language models** [[PDF]](https://bmva-archive.org.uk/bmvc/2024/papers/Paper_66/paper.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9326184152587377710&hl=en)

- `...` [Zhan et al., Proc. IJCAI 2024] **Towards dynamic-prompting collaboration for source-free domain adaptation** [[PDF]](https://www.ijcai.org/proceedings/2024/182) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11953111724963562741&hl=en) [[CODE]](https://github.com/Anonymous3119/paperID3119)

- `ReCLIP` [Hu et al., Proc. WACV 2024] **ReCLIP: Refine contrastive language image pre-training with source free domain adaptation** [[PDF]](https://arxiv.org/abs/2308.03793) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18135944623162059089&hl=en) [[CODE]](https://github.com/michiganleon/ReCLIP_WACV)

- `DIFO` [Tang et al., Proc. WACV 2024] **Source-free domain adaptation with frozen multimodal foundation model** [[PDF]](https://arxiv.org/abs/2311.16510) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7386217752559798759&hl=en) 

- `OT-VP` [Zhang et al., Proc. CVPR Workshops 2024] **OT-VP: Optimal transport-guided visual prompting for test-time adaptation** [[PDF]](https://tta-cvpr2024.github.io/_downloads/63a4c7ea64117d8e8f2db690967c01fb/matc_4_ot_vp_optimal_transport_guided.pdf) [[G-Scholar--]]() 

- `QED` [Liu et al., IEEE TCSVT 2024] **Question type-aware debiasing for test-time visual question answering model adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10550013) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6734344509097123329&hl=en)

- `BBC` [Tian et al., Signal, Image and Video Processing 2024] **CLIP-guided black-box domain adaptation of image classification** [[PDF]](https://link.springer.com/article/10.1007/s11760-024-03101-8) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1976933170084150331&hl=en)

- `TGKT` [Zhu et al., arXiv 2024] **Source-free cross-modal knowledge transfer by unleashing the potential of task-irrelevant data** [[PDF]](https://openreview.net/forum?id=zSN6mXz6VF) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3323615604707430203&hl=en)

- `TFUP` [Long et al., arXiv 2024] **Training-free unsupervised prompt for vision-language models** [[PDF]](https://arxiv.org/abs/2404.16339) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14169978613107453045&hl=en) [[CODE]](https://github.com/wlb12345/TFUP)

- `RCL` [Chen et al., arXiv 2024] **Empowering source-free domain adaptation with MLLM-driven curriculum learning** [[PDF]](https://arxiv.org/abs/2405.18376) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14936799511700755704&hl=en) [[CODE--]](https://github.com/Dong-Jie-Chen/RCL)

- `TransCLIP` [Zanella et al., arXiv 2024] **Boosting vision-language models with transduction** [[PDF]](https://arxiv.org/abs/2406.01837) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3194689844176400835&hl=en) [[CODE]](https://github.com/MaxZanella/transduction-for-vlms)

- `DPA` [Ali et al., arXiv 2024] **DPA: Dual prototypes alignment for unsupervised adaptation of vision-language models** [[PDF]](https://arxiv.org/abs/2408.08855) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1540060541549975731&hl=en)

- `EventDance++` [Zheng and Wang, arXiv 2024] **EventDance: Unsupervised source-free cross-modal adaptation for event-based object recognition** [[PDF]](https://arxiv.org/abs/2409.12778) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6946776143159713482&hl=en) [[CODE--]](https://github.com/zhengxujosh/EventDance)

- `LatteCLIP` [Cao et al., arXiv 2024] **LatteCLIP: Unsupervised CLIP fine-tuning via LMM-synthetic texts** [[PDF]](https://arxiv.org/abs/2410.08211) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12882603399194379365&hl=en)

- `CDBN` [Li et al., arXiv 2024] **Data-efficient CLIP-powered dual-branch networks for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2410.15811) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17056937347900577651&hl=en)

- `LAD` [Peng et al., arXiv 2024] **Language-guided alignment and distillation for source-free domain adaptation** [[PDF]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5074834) [[G-Scholar--]]()

- `ECALP` [Li et al., arXiv 2024] **Efficient and context-aware label propagation for zero-/few-shot training-free adaptation of vision-language model** [[PDF]](https://arxiv.org/abs/2412.18303) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2144864553872756774&hl=en)

- `L2C` [Chi et al., Proc. ICLR 2025] **Learning to adapt frozen CLIP for few-shot test-time domain adaptation** [[PDF]](https://openreview.net/forum?id=TD3SGJfBC7) [[G-Scholar--]]()

- `CCD` [Kim and Shim, Proc. CVPR 2025] **Classifier-guided CLIP distillation for unsupervised multi-label classification** [[PDF]](https://arxiv.org/abs/2503.16873) [[G-Scholar--]]() [[CODE--]](https://github.com/k0u-id/CCD)

- `GTA-CLIP` [Saha et al., arXiv 2025] **Generate, transduct, adapt: Iterative transduction with VLMs** [[PDF]](https://arxiv.org/abs/2501.06031) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3421787342752012824&hl=en) [[CODE--]](https://github.com/cvl-umass/GTA-CLIP)

- `ViLAaD` [Tarashima et al., arXiv 2025] **ViLAaD: Enhancing "attracting and dispersing" source-free domain adaptation with vision-and-language model** [[PDF]](https://arxiv.org/abs/2503.23529) [[G-Scholar--]]()

- `...` [Xu et al., arXiv 2025] **Probability distribution alignment and low-rank weight decomposition for source-free domain adaptive brain decoding** [[PDF]](https://arxiv.org/abs/2504.09109) [[G-Scholar--]]()

### Image Super-Resolution
- `SOSR` [Ai et al., arXiv 2023] **SOSR: Source-free image super-resolution with wavelet augmentation transformer** [[PDF]](https://arxiv.org/abs/2303.17783) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15698511251689818196&hl=en)

### Image Dehazing
- `DRN` [Yu et al., Proc. ACMMM 2022] **Source-free domain adaptation for real-world image dehazing** [[PDF]](https://arxiv.org/abs/2207.06644) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16555277816059371930&hl=en)

### Image Harmonization
- `Harmonizing-Flows` [Beizaee et al., arXiv 2024] **Harmonizing flows: Unsupervised MR harmonization based on normalizing flows** [[PDF]](https://arxiv.org/abs/2407.15717) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1720838732837069065&hl=en) [[CODE]](https://github.com/farzad-bz/Harmonizing-Flows)
  ~~- `Harmonizing-Flows` [Beizaee et al., arXiv 2023] **Harmonizing flows: Unsupervised MR harmonization based on normalizing flows** [[PDF]](https://arxiv.org/abs/2301.11551) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14941931549061751891&hl=en) [[CODE]](https://github.com/farzad-bz/Harmonizing-Flows)~~

### Video Quality Enhancement
- `CVQE-MT` [Wang, Proc. ICCWAMTIP 2022] **An unsupervised domain adaptation method for compressed video quality enhancement** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10016616/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11682562181534960786&hl=en)

### Image Quality Assessment
- `SFDA-SSLBN` [Liu et al., arXiv 2022] **Source-free unsupervised domain adaptation for blind image quality assessment** [[PDF]](https://arxiv.org/abs/2207.08124) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2138500387139877671&hl=en)

### Road Segmentation (binary)
- `SS-SFDA` [Kothandaraman et al., Proc. ICCV Workshops 2021] **SS-SFDA: Self-supervised source-free domain adaptation for road segmentation in hazardous environments** [[PDF]](https://openaccess.thecvf.com/content/ICCV2021W/AVVision/html/Kothandaraman_SS-SFDA_Self-Supervised_Source-Free_Domain_Adaptation_for_Road_Segmentation_in_Hazardous_ICCVW_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2325306153552113178&hl=en) [[CODE]](https://github.com/divyakraman/SS-SFDA-Self-Supervised-Source-Free-Domain-Adaptation-for-Road-Segmentation-in-Hazardous-Environme)

### Sign Segmentation
- `CMPL` [Renz et al., Proc. CVPR Workshops 2021] **Sign segmentation with changepoint-modulated pseudo-labelling** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021W/ChaLearn/html/Renz_Sign_Segmentation_With_Changepoint-Modulated_Pseudo-Labelling_CVPRW_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10843136778842689752&hl=en) [[CODE]](https://github.com/RenzKa/sign-segmentation)

### Visual Document Understanding
- `DocTTA` [Ebrahimi et al., TMLR 2023] **Test-time adaptation for visual document understanding** [[PDF]](https://arxiv.org/abs/2206.07240) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4974275319186080260&hl=en) [[DATA]](https://sites.google.com/berkeley.edu/doctta/)

### 2D Keypoint Detection (Pose estimation)
- `MAPS` [Ding et al., IEEE TCSVT 2023] **MAPS: A noise-robust progressive learning approach for source-free domain adaptive keypoint detection** [[PDF]](https://arxiv.org/abs/2302.04589) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13949106311988540827&hl=en) [[CODE]](https://github.com/YuheD/MAPS)

- `...` [Peng et al., Proc. ICCV 2023] **Source-free domain adaptive human pose estimation** [[PDF]](https://arxiv.org/abs/2308.03202) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9372500620586065556&hl=en)

- `...` [Raychaudhuri et al., Proc. ICCV 2023] **Prior-guided source-free domain adaptation for human pose estimation** [[PDF]](https://arxiv.org/abs/2308.13954) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11978507610057332137&hl=en)

- `...` [Santoso and Wijaya, Asian American Research Letters Journal 2024] **Unsupervised domain adaptation for human pose estimation in the absence of source data** [[PDF]](https://www.aarlj.com/index.php/AARLJ/article/view/88) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6541271337536806061&hl=en)

### Tracking
- `DARTH` [Segu et al., Proc. ICCV 2023] **DARTH: Holistic test-time adaptation for multiple object tracking** [[PDF]](https://openaccess.thecvf.com/content/ICCV2023/html/Segu_DARTH_Holistic_Test-time_Adaptation_for_Multiple_Object_Tracking_ICCV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9104639642522487809&hl=en) [[CODE]](https://github.com/mattiasegu/darth)

- `OC-SORT` [Shu et al., ITE Technical Report 2024] **Exploring source-free domain adaption in multiple object tracking** [[PDF]](https://www.ite.or.jp/ken/paper/20240219GAMb/eng/) [[G-Scholar--]]()

### Anomaly detection
- `CaSA` [Bozorgtabar et al., Proc. BMVC 2022] **Anomaly detection and localization using attention-guided synthetic anomaly and test-time adaptation** [[PDF]](https://bmvc2022.mpi-inf.mpg.de/0472.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=209397539357448856&hl=en)

- `AnoVL` [Deng et al., arXiv 2023] **AnoVL: Adapting vision-language models for unified zero-shot anomaly localization** [[PDF]](https://arxiv.org/abs/2308.15939) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7060182260008690857&hl=en)

- `...` [Klüttermann and Müller, arXiv 2024] **About test-time training for outlier detection** [[PDF]](https://arxiv.org/abs/2404.03495) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6153300472947898632&hl=en) [[CODE]](https://anonymous.4open.science/r/doust-15EE/README.md)

### Retrieval
- `T3AR` [Zancato et al., Proc. CVPR 2023] **Train/test-time adaptation with retrieval** [[PDF]](https://arxiv.org/abs/2303.14333) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3099149445593841717&hl=en)

- `DISC` [Ma et al., IEEE TMM 2024] **Discrepancy and structure-based contrast for test-time adaptive retrieval** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10478505) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4497474903186916401&hl=en)

- `PCLO` [Li et al., IEEE TCSVT 2024] **Progressive contrastive label optimization for source-free universal 3D model retrieval** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10714442) [[G-Scholar--]]()

### Gaze estimation
- `UnReGA` [Cai et al., Proc. CVPR 2023] **Source-free adaptive gaze estimation by uncertainty reduction** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/papers/Cai_Source-Free_Adaptive_Gaze_Estimation_by_Uncertainty_Reduction_CVPR_2023_paper.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11136870237307965506&hl=en) [[CODE--]](https://github.com/caixin1998/UnReGA)

### Hand-Object Interaction
- `POV` [Xu et al., Proc. ACMMM 2023] **POV: Prompt-oriented view-agnostic learning for egocentric hand-object interaction in the multi-view world** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3581783.3612484) [[G-Scholar]](https://scholar.google.com/scholar?cluster=587874071327455739&hl=en)

### Human Activity Recognition
- `SF-Adapter` [Kang et al., Proc. IMWUT 2023] **SF-Adapter: Computational-efficient source-free domain adaptation for human activity recognition** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3631428) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12814668313511289033&hl=en)

### Handwritten Text Recognition
- `AMD` [Alfaro-Contreras and Calvo-Zaragoza, arXiv 2024] **Align, minimize and diversify: A source-free unsupervised domain adaptation method for handwritten text recognition** [[PDF]](https://arxiv.org/abs/2404.18260) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3896483948031450426&hl=en)

### Model merging
- `AdaMerging` [Yang et al., Proc. ICLR 2024] **AdaMerging: Adaptive model merging for multi-task learning** [[PDF]](https://arxiv.org/abs/2310.02575) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13566734225805515719&hl=en) [[CODE]](https://github.com/EnnengYang/AdaMerging)

- `Surgery` [Yang et al., Proc. ICML 2024] **Representation surgery for multi-task model merging** [[PDF]](https://arxiv.org/abs/2402.02705) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6453660338776961868&hl=en) [[CODE]](https://github.com/EnnengYang/RepresentationSurgery)

- `WEMOE` [Tang et al., Proc. ICML 2024] **Merging multi-task models via weight-ensembling mixture of experts** [[PDF]](https://arxiv.org/abs/2402.00433) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1325857199730013195&hl=en) [[CODE]](https://github.com/tanganke/weight-ensembling_MoE)

- `Twin-Merging` [Lu et al., Proc. NeurIPS 2024] **Twin-merging: Dynamic integration of modular expertise in model merging** [[PDF]](https://arxiv.org/abs/2406.15479) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5883076762358660219&hl=en) [[CODE]](https://github.com/LZY-the-boys/Twin-Merging)

- `Surgeryv2` [Yang et al., arXiv 2024] **SurgeryV2: Bridging the gap between model merging and multi-task learning with deep representation surgery** [[PDF]](https://arxiv.org/abs/2410.14389) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1720729308555898635&hl=en) [[CODE]](https://github.com/ennengyang/surgeryv2)

- `AdaRank` [Lee et al., arXiv 2025] **AdaRank: Adaptive rank pruning for enhanced model merging** [[PDF]](https://arxiv.org/abs/2503.22178) [[G-Scholar--]]() [[CODE]](https://github.com/david3684/AdaRank)

### Misc
- `...` [Rufin et al., arXiv 2023] **Taking it further: Leveraging pseudo labels for field delineation across label-scarce smallholder regions** [[PDF]](https://arxiv.org/abs/2312.08384) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8445827874885835800&hl=en)

- `...` [Mohammadi et al., Remote Sensing of Environment 2024] **A source-free unsupervised domain adaptation method for cross-regional and cross-time crop mapping from satellite image time series** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0034425724004115) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17849911299123650292&hl=en) [[CODE]](https://github.com/Sina-Mohammadi/SFUDA-CropMapping)

- `SFDA-rPPG` [Xie et al., arXiv 2024] **SFDA-rPPG: Source-free domain adaptive remote physiological measurement with spatio-temporal consistency** [[PDF]](https://arxiv.org/abs/2409.12040) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5782627783857860990&hl=en) [[CODE]](https://github.com/XieYiping66/SFDA-rPPG)

- `...` [Wen et al., arXiv 2024] **Generalizing segmentation foundation model under sim-to-real domain-shift for guidewire segmentation in X-ray fluoroscopy** [[PDF]](https://arxiv.org/abs/2410.07460) [[G-Scholar--]]()

## Beyond CV Applications
### 2020
- `...` [Laparra et al., JAMIA open 2020] **Rethinking domain adaptation for machine learning over clinical language** [[PDF]](https://academic.oup.com/jamiaopen/article/3/2/146/5831556) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15011224356081547243&hl=en)

### 2021
- `CdKD` [Zhao et al., Proc. ACL 2021] **Matching distributions between model and data: Cross-domain knowledge distillation for unsupervised domain adaptation** [[PDF]](https://aclanthology.org/2021.acl-long.421/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16829742576573810731&hl=en)

- `PPT` [Kurniawan et al., Proc. EACL 2021] **PPT: Parsimonious parser transfer for unsupervised cross-lingual adaptation** [[PDF]](https://aclanthology.org/2021.eacl-main.254/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7324868212400960642&hl=en) [[CODE]](https://github.com/kmkurn/ppt-eacl2021)

- `...` [Kedia et al., Proc. ECAL 2021] **Keep learning: Self-supervised meta-learning for learning from inference** [[PDF]](https://aclanthology.org/2021.eacl-main.6/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12795460589001675704&hl=en) 

- `ActiveST` [Su et al., Proc. ACL SemEval 2021] **The University of Arizona at SemEval-2021 task 10: Applying self-training, active learning and data augmentation to source-free domain adaptation** [[PDF]](https://aclanthology.org/2021.semeval-1.56/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15617873900739629649&hl=en)

- `...` [Laparra et al., Proc. ACL SemEval 2021] **SemEval-2021 task 10: Source-free domain adaptation for semantic processing** [[PDF]](https://aclanthology.org/2021.semeval-1.42/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3826840294377233499&hl=en)

  ----------

- `e-SHOT-CE` [Cao et al., IEEE TVT 2021] **Towards cross-environment human activity recognition based on radar without source data** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9760113/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6452327194388265947&hl=en)

### 2022
- `...` [Su et al., Proc. ACL 2022] **A comparison of strategies for source-free domain adaptation** [[PDF]](https://aclanthology.org/2022.acl-long.572/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4321860393076444396&hl=en) [[CODE]](https://github.com/xinsu626/SourceFreeDomainAdaptation)

- `...` [Kurniawan et al., Proc. NAACL 2022] **Unsupervised cross-lingual transfer of structured predictors without source data** [[PDF]](https://aclanthology.org/2022.naacl-main.149/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5635921638596604365&hl=en) [[CODE]](https://github.com/kmkurn/uxtspwsd)

- `IDANI` [Antverg et al., Proc. ACL Workshops 2022] **IDANI: Inference-time domain adaptation via neuron-level interventions** [[PDF]](https://aclanthology.org/2022.deeplo-1.3/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10046849600588003301&hl=en) [[CODE]](https://github.com/technion-cs-nlp/idani)

- `...` [Zhang et al., Proc. China Automation Congress 2022] **Source-free domain adaptation for rotating machinery cross-domain fault diagnosis with neighborhood reciprocity clustering** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10055182) [[G-Scholar--]]()

- `...` [Zhu et al., Proc. ICSMD 2022] **Source-free unsupervised domain adaptation for privacy-preserving intelligent fault diagnosis** [[PDF]](https://ieeexplore.ieee.org/document/10058437) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11612300519810323279&hl=en)

- `MDMAML` [Li et al., IEEE CIM 2022] **Meta-learning for fast and privacy-preserving source knowledge transfer of EEG-based BCIs** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9942685) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9383691095506932596&hl=en)

- `MSDT` [Zhang et al., IEEE TNSRE 2022] **Multi-source decentralized transfer for privacy-preserving BCIs** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9894428/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2150739430618555059&hl=en)

- `LSFT` [Zhang and Wu, IEEE TCDS 2022] **Lightweight source-free transfer for privacy-preserving motor imagery classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9840893/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15691682036339231302&hl=en)

- `ASFA` [Xia et al., IEEE TBE 2022] **Privacy-preserving domain adaptation for motor imagery-based brain-computer interfaces** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9760113/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13402357178362327681&hl=en) [[CODE]](https://github.com/xkazm/ASFA)

- `T-ISTGNN` [Qi et al., IEEE TITS 2022] **Privacy-preserving cross-area traffic forecasting in ITS: A transferable spatial-temporal graph neural network approach** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9928430/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1841703851715000157&hl=en)

- `DP-SFDA` [An et al., IEEE TITS 2022] **A privacy-preserving unsupervised domain adaptation framework for clinical text analysis** [[PDF]](https://arxiv.org/abs/2201.07317) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15348410852649744691&hl=en)

- `SFAD` [Jiao et al., IEEE TII 2022] **Source-free adaptation diagnosis for rotating machinery** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9997572/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5207715234075089280&hl=en)

- `scEMAIL` [Wan et al., Genomics, Proteomics and Bioinformatics 2022] **scEMAIL: Universal and source-free annotation method for scRNA-seq data with novel cell-type perception** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1672022922001747) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1698595785369986836&hl=en) [[CODE]](https://github.com/aster-ww/scEMAIL)

- `...` [Wang et al., Chinese Journal of Aeronautics 2022] **Source free unsupervised domain adaptation for electro-mechanical actuator fault diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1000936123000493) [[G-Scholar]](https://scholar.google.com/scholar?cites=2405206262999061108&hl=en)

- `MDAQA` [Yin et al., arXiv 2022] **Source-free domain adaptation for question answering with masked self-training** [[PDF]](https://arxiv.org/abs/2212.09563) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6098149583071335403&hl=en)

### 2023
- `NOTELA` [Boudiaf et al., Proc. ICML 2023] **In search for a generalizable method for source free domain adaptation** [[PDF]](https://arxiv.org/abs/2302.06658) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12424145282212014491&hl=en)

  ~~[Boudiaf et al., Misc 2023] **NOTELA: A generalizable method for source free domain adaptation** [[PDF]](https://openreview.net/forum?id=aOBs18ycBr)~~

- `TaU` [Zhan et al., Proc. ACL 2023] **Test-time adaptation for machine translation evaluation by uncertainty minimization** [[PDF]](https://aclanthology.org/2023.acl-long.47/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5961333184577110024&hl=en) [[CODE--]](https://github.com/NLP2CT/TaU)

- `FLOOD` [Liu et al., Proc. KDD 2023] **FLOOD: A flexible invariant learning framework for out-of-distribution generalization on graphs** [[PDF]](https://ponderly.github.io/pub/FLOOD_KDD2023.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14116178253552611360&hl=en)

- `MAPU` [Ragab et al., Proc. KDD 2023] **Source-free domain adaptation with temporal imputation for time series data** [[PDF]](https://arxiv.org/pdf/2307.07542.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18173378344700689071&hl=en) [[CODE]](https://github.com/mohamedr002/MAPU_SFDA_TS)

- `TALC` [Wei et al., Proc. EMNLP Findings 2023] **Leveraging multiple teachers for test-time adaptation of language-guided classifiers** [[PDF]](https://arxiv.org/abs/2311.07538) [[G-Scholar--]]() [[CODE--]](https://github.com/WeiKangda/TALC)

- `...` [Lee et al., Proc. BCI 2023] **Source-free cross-domain state of charge estimation of lithium-ion batteries at different ambient temperatures** [[PDF]](https://arxiv.org/abs/2301.08448) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4013259541683787047&hl=en) [[CODE]](https://github.com/DeepBCI/Deep-BCI)

- `SFQA` [Zhao et al., Proc. ICASSP 2023] **Source-free unsupervised domain adaptation for question answering** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10095248/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3276881990878709043&hl=en)

- `BKD-SFUDA` [Tian et al., Proc. CSCWD 2023] **Knowledge distillation with source-free unsupervised domain adaptation for BERT model compression** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10152760/) [[G-Scholar--]]()

- `...` [Wang et al., Proc. IEEE ICMA 2023] **Source-free domain adaptation network for rolling bearing fault diagnosis** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10216194) [[G-Scholar--]]()

- `DSP` [Liu et al., Proc. AIMLR 2023] **Adaptive speech recognition via dual-level sequential pseudo labels** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3625343.3625366) [[G-Scholar--]]()

- `...` [Zhang et al., Proc. ASRU 2023] **Consistency based unsupervised self-training for ASR personalisation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10389677) [[G-Scholar--]]()

- `...` [Islam et al., Proc. ETFG 2023] **Location agnostic source-free domain adaptive learning to predict solar power generation** [[PDF]](https://arxiv.org/abs/2401.14422) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11502766210675756156&hl=en)

  ---------------------

- `SFTTN` [Shen et al., IEEE TPEL 2023] **Source-free cross-domain state of charge estimation of lithium-ion batteries at different ambient temperatures** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10058040/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14503249759236941200&hl=en)

- `...` [Yue et al., IEEE TIM 2023] **Multiple source-free domain adaptation network based on knowledge distillation for machinery fault diagnosis** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10174649) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10702745574636542183&hl=en)

- `...` [Wu et al., IEEE TIM 2023] **Privacy-preserving adaptive remaining useful life prediction via source free domain adaption** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10239252) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15845870528425704517&hl=en) [[CODE]](https://github.com/TL-UESTC/Privacy-Preserving-Adaptive-Remaining-Useful-Life-Prediction-via-Source-Free-Domain-Adaption)

- `SF-CA` [Zhu et al., IEEE TIM 2023] **Source-free cluster adaptation for privacy-preserving machinery fault diagnosis** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10243035) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7922385448172105319&hl=en)

- `...` [Zhu et al., IEEE TIM 2023] **Dual contrastive training and transferability aware adaptation for multi-source privacy-preserving motor imagery classification** [[PDF]](https://ieeexplore.ieee.org/document/10352359) [[G-Scholar]](https://scholar.google.com/scholar?cluster=393038847129649152&hl=en) [[CODE]](https://github.com/grilled-chicken-burger/bci)

- `...` [Zhao et al., IEEE TII 2023] **Source-free domain adaptation for privacy-preserving seizure prediction** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10199136) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4950345496318245785&hl=en)

- `TASFA` [Xiao et al., IEEE TII 2023] **Temporal attention source-free adaptation for chemical processes fault diagnosis** [[PDF]](https://ieeexplore.ieee.org/document/10315182) [[G-Scholar--]]()

- `B2TSDA` [Ren et al., IEEE TCYB 2023] **Single/multi-source black-box domain adaption for sensor time series data** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10226509) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12501956151412606425&hl=en)

- `SS-TrBoosting` [Zhao et al., IEEE TNSRE 2023] **Source-free domain adaptation (SFDA) for privacy-preserving seizure subtype classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10122236) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13671255325572013222&hl=en)

- `...` [Wang et al., IEEE Internet of Things Journal 2023] **Wireless IoT monitoring system in Hong Kong–Zhuhai–Macao bridge and edge computing for anomaly detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10197602) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16524208117464603479&hl=en)

- `...` [Dridi et al., Building and Environment 2023] **Unsupervised domain adaptation with and without access to source data for estimating occupancy and recognizing activities in smart buildings** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0360132323006789) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10023762052679130264&hl=en)

- `...` [Dridi et al., Energy and Buildings 2023] **Unsupervised domain adaptation without source data for estimating occupancy and recognizing activities in smart buildings** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0378778823010381) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8559686073612311627&hl=en)

- `SFDAF` [Li et al., Reliability Engineering and System Safety 2023] **Source-free domain adaptation framework for fault diagnosis of rotation machinery under data privacy** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0951832023003824) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1724382786110975115&hl=en)

- `UCSN` [Li et al., IEEE Sensors Journal 2023] **Unsupervised continual source-free network for fault diagnosis of machines under multiple diagnostic domains** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10075359/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13992913209973746928&hl=en)

- `PPDA` [Wang et al., IEEE Sensors Journal 2023] **Privacy-preserving domain adaptation for intracranial EEG classification via information maximization and gaussian mixture model** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10268883) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8201062960212700233&hl=en)

- `HSSC-EMM` [Zhang et al., Mechanical Systems and Signal Processing 2023] **Universal source-free domain adaptation method for cross-domain fault diagnosis of machines** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0888327023000663) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9778377080450704864&hl=en)

- `...` [Li et al., Journal of Manufacturing Systems 2023] **Federated transfer learning in fault diagnosis under data privacy with target self-adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0278612523000808) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10402589798438834852&hl=en)

- `TAPDA` [Yuan and Siyal, Biomedical Signal Processing and Control 2023] **Target-oriented augmentation privacy-protection domain adaptation for imbalanced ECG beat classification** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1746809423007413) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2697741390977458349&hl=en)

- `...` [Zhao et al., Measurement Science and Technology 2023] **Single-source UDA for privacy-preserving intelligent fault diagnosis based on domain augmentation** [[PDF]](https://iopscience.iop.org/article/10.1088/1361-6501/acf3ff/meta) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15840671848054047759&hl=en)

- `MWSDTN` [Gao et al., Expert Systems With Applications 2023] **Multi-source weighted source-free domain transfer method for rotating machinery fault diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0957417423020870) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16738456458868616908&hl=en)

- `...` [Tian et al., Reliability Engineering & System Safety 2023] **A novel generalized source-free domain adaptation approach for cross-domain industrial fault diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0951832023008050) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10414247860469223332&hl=en)

- `...` [Guney et al., arXiv 2023] **Source free domain adaptation of a DNN for SSVEP-based brain-computer interfaces** [[PDF]](https://arxiv.org/abs/2305.17403) [[G-Scholar--]]() [[CODE--]](https://github.com/osmanberke/SFDA-SSVEP-BCI)

- `AMFDA` [Salimnia., Master Thesis 2023] **Attention-based multi-source-free domain adaptation for EEG emotion recognition** [[PDF]](https://ir.lib.uwo.ca/etd/9154) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17471628973502560469&hl=en)

- `...` [Niknam., Master Thesis 2023] **Source-free domain adaptation for sleep stage classification** [[PDF]](https://ir.lib.uwo.ca/cgi/viewcontent.cgi?article=11881&context=etd) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2882485758239180576&hl=en)

### 2024
- `...` [Vermani et al., Proc. ICLR 2024] **Leveraging generative models for unsupervised alignment of neural time series data** [[PDF]](https://openreview.net/forum?id=9zhHVyLY4K) [[G-Scholar]](https://scholar.google.com/scholar?cluster=140027540675777815&hl=en)

- `RNA` [Luo et al., Proc. IJCAI 2024] **Rank and align: Towards effective source-free graph domain adaptation** [[PDF]](https://arxiv.org/abs/2408.12185) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7055237628244854793&hl=en)

- `GraphCTA` [Zhang et al., Proc. WWW 2024] **Collaborate to adapt: Source-free graph domain adaptation via bi-directional adaptation** [[PDF]](https://arxiv.org/abs/2403.01467) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16951290595962241076&hl=en) [[CODE]](https://github.com/cszhangzhen/GraphCTA)

- `SOGA` [Mao et al., Proc. WSDM 2024] **Source free graph unsupervised domain adaptation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3616855.3635802) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8057939358946355621&hl=en)

  ~~[Mao et al., arxiv 2024] **Source free unsupervised graph domain adaptation** [[PDF]](https://arxiv.org/abs/2112.00955) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8057939358946355621&hl=en)~~

- `...` [Flynn and Ragni, Proc. Interspeech 2024] **Self-train before you transcribe** [[PDF]](https://arxiv.org/abs/2406.12937) [[G-Scholar--]]() 

- `CHDA` [Chien et al., Proc. Interspeech 2024] **Collaborative contrastive learning for hypothesis domain adaptation** [[PDF]](https://www.isca-archive.org/interspeech_2024/chien24c_interspeech.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3998914961896605396&hl=en) 

- `CaHTN` [Wang et al., Proc. Interspeech 2024] **Confidence-aware hypothesis transfer networks for source-free cross-corpus speech emotion recognition** [[PDF]](https://www.isca-archive.org/interspeech_2024/wang24ja_interspeech.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12349650725579758100&hl=en) 

- `...` [Oiso et al., Proc. Interspeech 2024] **Prompt tuning for audio deepfake detection: Computationally efficient test-time domain adaptation with limited target dataset** [[PDF]](https://www.isca-archive.org/interspeech_2024/oiso24_interspeech.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17030823437044705096&hl=en) 

- `PASAL` [Yin et al., Proc. NAACL Findings 2024] **Source-free unsupervised domain adaptation for question answering via prompt-assisted self-learning** [[PDF]](https://aclanthology.org/2024.findings-naacl.44/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1877486025191451008&hl=en)

- `SFPS` [Shimizu, et al., Proc. ACL Findings 2024] **Improving self-training with prototypical learning for source-free domain adaptation on clinical text** [[PDF]](https://aclanthology.org/2024.bionlp-1.1/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1517429916656098663&hl=en)

- `SF-ABSA` [Zhao et al., Proc. LREC-COLING 2024] **Source-free domain adaptation for aspect-based sentiment analysis** [[PDF]](https://aclanthology.org/2024.lrec-main.1310/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11780693717911139987&hl=en)

- `...` [Bu et al., Proc. KSEM 2024] **Weighted multiple source-free domain adaptation ensemble network in intelligent machinery fault diagnosis** [[PDF]](https://link.springer.com/chapter/10.1007/978-981-97-5495-3_16) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13382767580481507075&hl=en)

- `ECAN` [Zhao et al., Proc. ICASSP 2024] **Emotion-aware contrastive adaptation network for source-free cross-corpus speech emotion recognition** [[PDF]](https://arxiv.org/abs/2401.12925) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7127082626726998970&hl=en)

- `...` [Liu et al., Proc. ICASSP 2024] **Source-free domain adaptation for millimeter wave radar based human activity recognition** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10446797) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7655365186618261962&hl=en)

- `PAW` [Huang et al., Proc. ICASSP 2024] **Privacy-preserving attention-weighted multi-source domain adaptation for EEG motor imagery** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10447934) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13203764657277448692&hl=en)

- `SFDA-OMR` [Roselló et al., Proc. ICDAR 2024] **Source-free domain adaptation for optical music recognition** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-70552-6_1) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4768070999123411402&hl=en) [[CODE]](https://github.com/OMR-PRAIG-UA-ES/SFDA-OMR)

- `...` [Wang et al., Proc. I2MTC 2024] **A clustering-guided source-free domain transfer learning diagnostic method for rotating machiner** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10561161) [[G-Scholar--]]()

- `SODAN` [Yue et al., Proc. I2MTC 2024] **Source-free open-set domain adaptation network for emerging fault diagnosis of planetary gearbox** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10561232) [[G-Scholar--]]()

- `GALA` [Luo et al., IEEE TPAMI 2024] **GALA: Graph diffusion-based alignment with Jigsaw for source-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/document/10561561/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13509649659634355934&hl=en) [[CODE]](ttps://github.com/luo-junyu/GALA)

- `ISFAD` [Liu et al., IEEE TIM 2024] **Imbalanced source-free adaptation diagnosis for rotating machinery** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10530023/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12174296527035494087&hl=en)

- `SF-UDA` [Kumar et al., IEEE TIM 2024] **Mitigating negative transfer learning in source free-unsupervised domain adaptation for rotating machinery fault diagnosis** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10711882/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11629309404659096141&hl=en)

- `...` [Zhong et al., IEEE TIM 2024] **Source-free domain adaptation with self-supervised learning for non-intrusive load monitoring** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10716675/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4261247306804307782&hl=en)

- `SPARK` [Yuan et al., IEEE JBHI 2024] **SPARK: a high-efficiency black-box domain adaptation framework for source privacy-preserving drowsiness detection** [[PDF]](https://ieeexplore.ieee.org/document/10472580/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16448312945024888601&hl=en)

- `AEA` [Wang et al., IEEE JBHI 2024] **Lightweight source-free domain adaptation based on adaptive euclidean alignment for brain-computer interfaces** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10684016/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7768300027339612735&hl=en)

- `TSSFDA` [Jia et al., IEEE TETCI 2024] **A two-stage privacy-preserving domain adaptation for industrial time-series prediction** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10771794) [[G-Scholar--]]()

- `...` [Chen et al., IEEE Internet of Things Journal 2024] **Uncertainty estimation pseudo-labels guided source-free domain adaptation for cross-domain remaining useful life prediction in IIoT** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10684608/) [[G-Scholar--]]()

- `EMDKFA` [Lin et al., IEEE Internet of Things Journal 2024] **Towards efficient multi-domain knowledge fusion adaptation via low-rank reparameterization and noisy label learning: Application to source-free cross-comain fault diagnosis in IIoT** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10700721) [[G-Scholar--]]()

- `...` [Hu et al., IEEE Sensors Journal 2024] **Fast online fault diagnosis for PMSM based on adaptation model** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10566612/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=828297948872303531&hl=en)

- `...` [Zhang et al., IEEE Sensors Journal 2024] **Reliable source-free domain adaptation for cross-user myoelectric pattern recognition** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10716503) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7142550685932545462&hl=en)

- `...` [Ma et al., Knowledge-Based Systems 2024] **Source-free cross-domain fault diagnosis of rotating machinery using the siamese framework** [[PDF]](https://www.sciencedirect.com/science/article/pii/S095070512400813X) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11685984920291285181&hl=en) 

- `SFRDA-PLUE` [Liu et al., Knowledge-Based Systems 2024] **A source free robust domain adaptation approach with pseudo-labels uncertainty estimation for rolling bearing fault diagnosis under limited sample conditions** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0950705124010773) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18199630948025301789&hl=en) 

- `AFSF-FD` [Li et al., Knowledge-Based Systems 2024] **Anti-forgetting source-free domain adaptation method for machine fault diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0950705124013066) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1656857839841928663&hl=en)

- `...` [Cao et al., Reliability Engineering & System Safety 2024] **Source-free domain adaptation for transferable remaining useful life prediction of machine considering source data absence** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0951832024001534) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15671673724434139005&hl=en)

- `...` [Yu et al., Reliability Engineering & System Safety 2024] **Source-free domain adaptation method for fault diagnosis of rotation machinery under partial information** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0951832024002552) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11298423459024052845&hl=en)

- `SSFDA-DLP` [Su et al., Reliability Engineering & System Safety 2024] **Semi-supervised source-free domain adaptation method via diffusive label propagation for rotating machinery fault diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0951832024004800) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6038143790540755247&hl=en)

- `ACPDA` [Li et al., Reliability Engineering & System Safety 2024] **Adaptive centroid prototype-based domain adaptation for fault diagnosis of rotating machinery without source data** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0951832024004654) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9664454312666572678&hl=en)

- `...` [Lin et al., Reliability Engineering & System Safety 2024] **A robust source-free unsupervised domain adaptation method based on uncertainty measure and adaptive calibration for rotating machinery fault diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S095183202400588X) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12696508735075566846&hl=en)

- `TFFM` [Gao et al., Information Fusion 2024] **Time- and frequency-domain fusion for source-free adaptation fault diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1566253524006535) [[G-Scholar--]]()

- `...` [Liu et al., Expert Systems with Applications 2024] **Reinforced fuzzy domain adaptation: Revolutionizing data-unaccessible rotating machinery fault diagnosis across multiple domains** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0957417424009606) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9096171087736030635&hl=en)

- `SFDA-CD` [Wang and Wu, Remote Sensing 2024] **SFDA-CD: A source-free unsupervised domain adaptation for VHR image change detection** [[PDF]](https://www.mdpi.com/2072-4292/16/7/1274) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1329002655691214590&hl=en)

- `...` [Wang et al., Advanced Engineering Informatics 2024] **SFDA-T: A novel source-free domain adaptation method with strong generalization ability for fault diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1474034624005548) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5499746836155505795&hl=en)

- `...` [Wu et al., Acta Energiae Solaris Sinica 2024] **Multi-source domain adaptive fault diagnosis method of wind turbine gearbox under no-accessing source data** [[PDF]](https://epjournal.csee.org.cn/tynxb/article/doi/10.19912/j.0254-0096.tynxb.2022-1953) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1739518772071810013&hl=en)

- `...` [Mellot et al., arXiv 2024] **Physics-informed and unsupervised riemannian domain adaptation for machine learning on heterogeneous EEG datasets** [[PDF]](https://arxiv.org/abs/2403.15415) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1424685735481569976&hl=en)

- `STAR` [Hu et al., arXiv 2024] **Self-taught recognizer: Toward unsupervised adaptation for speech foundation models** [[PDF]](https://arxiv.org/abs/2405.14161) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12568151450760744067&hl=en) [[CODE]](https://github.com/YUCHEN005/STAR-Adapt)

- `SSFDA` [Guo et al., arXiv 2024] **SpGesture: Source-free domain-adaptive sEMG-based gesture recognition with jaccard attentive spiking neural network** [[PDF]](https://arxiv.org/abs/2405.14398) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12901215899556874191&hl=en) 

- `E-MAPU` [Gong et al., arXiv 2024] **Evidentially calibrated source-free time-series domain adaptation with temporal imputation** [[PDF]](https://arxiv.org/abs/2406.02635) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8565279166729981246&hl=en)

- `...` [Elia et al., arXiv 2024] **Source-free domain adaptation for speaker verification in data-scarce languages and noisy channels** [[PDF]](https://arxiv.org/abs/2406.05863) [[G-Scholar--]]()

- `TAAD` [Sun et al., arXiv 2024] **Continuous test-time domain adaptation for efficient fault detection under evolving operating conditions** [[PDF]](https://arxiv.org/abs/2406.06607) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13762840643117134718&hl=en)

- `DT3OR` [Yang et al., arXiv 2024] **Dual test-time training for out-of-distribution recommender system** [[PDF]](https://arxiv.org/abs/2407.15620) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4342024997383986704&hl=en)

- `STMA` [Gnassounou et al., arXiv 2024] **Multi-source and test-time domain adaptation on multivariate signals using spatio-temporal monge alignment** [[PDF]](https://arxiv.org/abs/2407.14303) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2096507746238511515&hl=en)

- `...` [Soylu et al., arXiv 2024] **The art of the steal: Purloining deep learning models developed for an ultrasound scanner to a competitor machine** [[PDF]](https://arxiv.org/abs/2407.03512) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7842814758539637375&hl=en)

- `EverAdapt` [Ragab et al., arXiv 2024] **EverAdapt: Continuous adaptation for dynamic machine fault diagnosis environments** [[PDF]](https://arxiv.org/abs/2407.17117) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12357921755290939860&hl=en) [[CODE]](https://anonymous.4open.science/r/EverAdapt-4876/README.md)

- `TemSR` [Wang et al., arXiv 2024] **Temporal source recovery for time-series source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2409.19635) [[G-Scholar]](https://scholar.google.com/scholar?cluster=179109207018088258&hl=en) [[CODE]](https://github.com/Frank-Wang-oss/TemSR)

- `AdaRC` [Bao et al., arXiv 2024] **AdaRC: Mitigating graph structure shifts during test-time** [[PDF]](https://arxiv.org/abs/2410.06976) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3635276106417759013&hl=en)

- `SPDIM` [Li et al., arXiv 2024] **SPDIM: Source-free unsupervised conditional and label shift adaptation in EEG** [[PDF]](https://arxiv.org/abs/2411.07249) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2743532792452439142&hl=en)

- `SFT` [Patel et al., Proc. ICLR 2025] **Efficient source-free time-series adaptation via parameter subspace disentanglement** [[PDF]](https://arxiv.org/abs/2410.02147) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15088096027663744139&hl=en)

- `GraphATA` [Zhang and He, Proc. WWW 2025] **Aggregate to adapt: Node-centric aggregation for multi-source-free graph domain adaptation** [[PDF]](https://openreview.net/forum?id=RLpXUQgbfK) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17295134469464662445&hl=en) [[CODE]](https://github.com/cszhangzhen/GraphATA)

- `KTDA` [Jiao et al., IEEE TII 2025] **Source-free black-box adaptation for machine fault diagnosis** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10851433/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15500242352771600002&hl=en)

- `CoUDA` [Chen et al., IEEE TII 2025] **CoUDA: Continual unsupervised domain adaptation for industrial fault diagnosis under dynamic working conditions** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10896871/) [[G-Scholar--]]()

- `BRR` [Zhan et al., Neural Networks 2025] **Reducing bias in source-free unsupervised domain adaptation for regression** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0893608025000401) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5294577320566535956&hl=en)

- `LEMON` [Zhong et al., Neural Networks 2025] **Source-free time series domain adaptation with wavelet-based multi-scale temporal imputation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0893608025003077) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5589481467223192616&hl=en)

- `TFDA` [Furqon et al., Information Sciences 2025] **Time and frequency synergy for source-free time-series domain adaptations** [[PDF]](https://arxiv.org/abs/2410.17511) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8585440708527090222&hl=en) [[CODE]](https://github.com/furqon3009/TFDA)

- `CSSL` [Wang et al., User Modeling and User-Adapted Interaction 2025] **A contrastive self-supervised learning method for source-free EEG emotion recognition** [[PDF]](https://link.springer.com/article/10.1007/s11257-024-09424-y) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5236416154497442425&hl=en)

- `NUD` [Wang et al., Biomedical Signal Processing and Control 2025] **Active source-free domain adaptation for intracranial EEG classification via neighborhood uncertainty and diversity** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1746809424015222) [[G-Scholar--]]()

- `SDANU` [Jia et al., Measurement Science and Technology 2025] **A novel source-free domain adaptation network for intelligent diagnosis of bearings under unknown faults** [[PDF]](https://iopscience.iop.org/article/10.1088/1361-6501/adc6a6/meta) [[G-Scholar--]]()

- `AI3M` [Liu et al., Mechanical Systems and Signal Processing 2025] **An adaptive source-free unsupervised domain adaptation method for mechanical fault detection** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0888327025001761) [[G-Scholar]](https://scholar.google.com/scholar?cluster=405100385356478046&hl=en)

- `CSAD` [Li et al., Mechanical Systems and Signal Processing 2025] **Calibrated source-free adaptation for intelligent diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0888327025002833) [[G-Scholar--]]()

- `...` [Liu et al., IEEE Robotics and Automation Letters 2025] **Contrastive learning-based secure unsupervised domain adaptation framework and its application in cross-factory intelligent manufacturing** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10948317/) [[G-Scholar--]]()

- `JSEA` [Kari et al., arXiv 2025] **Joint source-environment adaptation of data-driven underwater acoustic source ranging based on model uncertainty** [[PDF]](https://arxiv.org/abs/2503.23258) [[G-Scholar--]]()

## Related
- [Yang et al., Proc. ACM-MM2007] **Cross-domain video concept detection using adaptive svms** [[PDF]](https://dl.acm.org/doi/abs/10.1145/1291233.1291276) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4589454669556425406&hl=en)

- [Aytal and Zisserman, Proc. ICCV 2011] **Tabula rasa: Model transfer for object category detection** [[PDF]](https://ieeexplore.ieee.org/document/6126504/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13106480027062040527&hl=en)

- [Kuzborskij et al., Proc. ICML 2013] **Stability and hypothesis transfer learning** [[PDF]](https://proceedings.mlr.press/v28/kuzborskij13.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5642234637780837688&hl=en)

- [Tommasi et al., IEEE TPAMI 2013] **Learning categories from few examples with multi model knowledge transfer** [[PDF]](https://ieeexplore.ieee.org/abstract/document/6620871/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10892813110202908253&hl=en)

- `AdaBN` [Li et al., Proc. ICLR 2017] **Revisiting batch normalization for practical domain adaptation** [[PDF]](https://openreview.net/forum?id=Hk6dkJQFx) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11679251260326951806&hl=en)

- `...` [Burns and Steinhardt, Proc. CVPR 2021] **Limitations of post-hoc feature alignment for robustness** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Burns_Limitations_of_Post-Hoc_Feature_Alignment_for_Robustness_CVPR_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10007615184186415315&hl=en) [[CODE]](https://github.com/collin-burns/feature-alignment)

- `DARE` [Rosenfeld et al., Proc. NeurIPS Workshops 2022] **Domain-adjusted regression or: ERM may already learn features sufficient for out-of-distribution generalization** [[PDF]](https://arxiv.org/abs/2202.06856) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18354400836987334001&hl=en)

- `GDSDA` [Ao et al., Proc. AAAI 2017] **Fast generalized distillation for semi-supervised domain adaptation** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/10848) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11001527589625859954&hl=en)

- `MapNet+` [Brahmbhatt et al., Proc. CVPR 2018] **Geometry-aware learning of maps for camera localization** [[PDF]](https://openaccess.thecvf.com/content_cvpr_2018/html/Brahmbhatt_Geometry-Aware_Learning_of_CVPR_2018_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15361942550307476955&hl=en)

- `dkdHTL` [Yu et al., arXiv 2020] **Dynamic knowledge distillation for black-box hypothesis transfer learning** [[PDF]](https://arxiv.org/abs/2007.12355) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4102832996867063478&hl=en)

- `TOHAN` [Chi et al., Proc. NeurIPS 2021] **TOHAN: A one-step approach towards few-shot hypothesis adaptation** [[PDF]](https://openreview.net/forum?id=vrkQ07gp0kq) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3362363617253826009&hl=en) [[CODE]](https://github.com/Haoang97/TOHAN)

- `LCCS` [Zhang et al., Proc. IJCAI 2022] **Few-shot adaptation of pre-trained networks for domain shift** [[PDF]](https://arxiv.org/abs/2205.15234) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17927210508667621786&hl=en) [[CODE]](https://github.com/zwenyu/lccs)

- `CIDA` [Kundu et al., Proc. ECCV 2020] **Class-incremental domain adaptation** [[PDF]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580052.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15757977957260800975&hl=en)

### 2023
- `DEG-Net` [Dong et al., Proc. ICML 2023] **Diversity-enhancing generative network for few-shot hypothesis adaptation** [[PDF]](https://openreview.net/forum?id=PJzjHAnoVp)[[G-Scholar]](https://scholar.google.com/scholar?cluster=16697282792430687674&hl=en)

- `RMT` [Döbler et al., Proc. CVPR 2023] **Class-incremental domain adaptation** [[PDF]](https://arxiv.org/abs/2211.13081) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5205082821636588766&hl=en) [[CODE]](https://github.com/mariodoebler/test-time-adaptation)

- `PromptStyler` [Cho et al., Proc. ICCV 2023] **PromptStyler: Prompt-driven style generation for source-free domain generalization** [[PDF]](https://arxiv.org/abs/2307.15199) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16858908258517096129&hl=en) [[CODE]](https://github.com/PromptStyler/PromptStyler.github.io)

- `SF-DAP` [Lee et al., Proc. ICCV 2023] **Unsupervised accuracy estimation of deep visual models using domain-adaptive adversarial perturbation without source samples** [[PDF]](https://arxiv.org/abs/2307.10062) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9360881807300326411&hl=en)

- `...` [Ericsson et al., Proc. AutoML 2023] **Better practices for domain adaptation** [[PDF]](https://openreview.net/forum?id=tQz8u2KU3zy) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10962178703413848128&hl=en)

---------------------------------------------

-  `CIFA` [Qi et al., IEEE Signal Processing Letters 2023] **Causal intervention for few-shot hypothesis adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10223279) [[G-Scholar--]]()

- `TIDo` [Ambastha and Yun, arXiv 2023] **TIDo: Source-free task incremental learning in non-stationary environments** [[PDF]](https://arxiv.org/abs/2301.12055) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17872927398350991456&hl=en)

- `ALeN` [Ambastha and Yun, arXiv 2023] **Adversarial learning networks: Source-free unsupervised domain incremental learning** [[PDF]](https://arxiv.org/abs/2301.12055) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3178251369340369001&hl=en)

- `...` [Singh and Diggavi, arXiv 2023] **Representation transfer learning via multiple pre-trained models for linear regression** [[PDF]](https://arxiv.org/abs/2305.16440) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13038876698699615849&hl=en)

- `...` [Huang et al., arXiv 2023] **Prompt ensemble self-training for open-vocabulary domain adaptation** [[PDF]](https://arxiv.org/abs/2306.16658) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2994211628111857111&hl=en)

- `PseudoCal` [Hu et al., arXiv 2023] **PseudoCal: A source-free approach to unsupervised uncertainty calibration in domain adaptation** [[PDF]](https://arxiv.org/abs/2307.07489) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7757812403763949632&hl=en)

### 2024
- `MAP` [Peng et al., Proc. CVPR 2024] **MAP: MAsk-pruning for source-free model intellectual property protection** [[PDF]](https://arxiv.org/abs/2403.04149) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6744190580142637230&hl=en) [[CODE--]](https://github.com/ispc-lab/MAP)

- `TASFAR` [He et al., Porc. ICDE 2024] **Target-agnostic source-free domain adaptation for regression tasks** [[PDF]](https://arxiv.org/abs/2312.00540) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3952939575279367642&hl=en) [[CODE]](https://github.com/Siriusize/TASFAR_DA)

- `...` [Leroux et al., Proc. CVPR Workshops 2024] **Test-time specialization of dynamic neural networks** [[PDF]](https://tta-cvpr2024.github.io/_downloads/4d709aa8330b463834bd636dac27d927/matp_4_test_time_specialization_of_dy.pdf) [[G-Scholar--]]() 

- `IM-DCL` [Xu et al., IEEE TIP 2024] **Enhancing information maximization with distance-aware contrastive learning for source-free cross-domain few-shot learning** [[PDF]](https://arxiv.org/abs/2403.01966) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6606628700918716097&hl=en) [[CODE]](https://github.com/xuhuali-mxj/IM-DCL)

- `TEA` [Jin et al., IEEE TMM 2024] **Federated hallucination translation and source-free regularization adaptation in decentralized domain adaptation for foggy scene understanding** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10814654/) [[G-Scholar--]]()

- `OSFTL` [Wu et al., IEEE TNSRE 2024] **Online privacy-preserving EEG classification by source-free transfer learning** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10638104/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1021214697549059773&hl=en)

- `CamoNet` [Zhang et al., IEEE TMC 2024] **CamoNet: On-device neural network adaptation with zero interaction and unlabeled data for diverse edge environments** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10522944/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12018083912496855600&hl=en)

- `RobustDA` [Guo et al., IEEE Journal on Emerging and Selected Topics in Circuits and Systems 2024] **RobustDA: Lightweight robust domain adaptation for evolving data at edge** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10714457/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2785912523970263712&hl=en)

- `TETOT` [Mehra et al., arXiv 2024] **Test-time assessment of a model's performance on unseen domains via optimal transport** [[PDF]](https://arxiv.org/abs/2405.01451) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17236322836354599887&hl=en)

- `L^3` [Xie et al., arXiv 2024] **Look, learn and leverage (L^3): Mitigating visual-domain shift and discovering intrinsic relations via symbolic alignment** [[PDF]](https://arxiv.org/abs/2408.17363) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13875583366994072200&hl=en)

- `...` [Zeng et al., arXiv 2024] **LLM embeddings improve test-time adaptation to tabular Y|X-shifts** [[PDF]](https://arxiv.org/abs/2410.07395) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18201469738692370537&hl=en) [[CODE]](https://github.com/namkoong-lab/LLM-Tabular-Shifts)

- `ACT` [Li and Wu et al., arXiv 2025] **Asymmetric co-training for source-free few-shot domain adaptation** [[PDF]](https://arxiv.org/abs/2502.14214) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14716110979078801764&hl=en) [[CODE]](https://github.com/gengxuli/ACT)