# Awesome Source-Free Domain Adaptation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome source-free domain adaptation resources. Your contributions are always welcome!

## Contents
- [Shallow Methods](#Shallow-Methods)
- [Image Classification](#Image-Classification)
- [Semantic Segmentation](#Semantic-Segmentation)
- [Object Detection](#Object-Detection)
- [Medical Image Analysis](#Medical-Image-Analysis)
- [Video Classification](#Video-Classification)
- [3D Point Cloud Perception](#3D-Point-Cloud-Perception)
- [Other CV Applications](#Other-CV-Applications)
- [Beyond CV Applications](#Beyond-CV-Applications)

## Shallow Methods
- `MCFA/ACM/TPA` [Chidlovskii and Orabona, Proc. KDD 2016] **Domain adaptation in the absence of source domain data** [[PDF]](https://dl.acm.org/doi/abs/10.1145/2939672.2939716) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9642892433162386910&hl=en)

- `TPAe` [Clinchant et al., Proc. ACL 2016] **Transductive adaptation of black box predictions** [[PDF]](https://aclanthology.org/P16-2.pdf#page=360) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16905965659974044730&hl=en)

- `RWA` [Van Laarhoven and Marchiori, Arxiv 2017] **Unsupervised domain adaptation with random walks on target labelings** [[PDF]](https://arxiv.org/abs/1706.05335) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11439870750939669715&hl=en) [[CODE]](https://github.com/twanvl/rwa-da)

- `AOT` [Nelakurthi et al., Proc. IEEE BigData 2018] **Source free domain adaptation using an off-the-shelf classifier** [[PDF]](https://ieeexplore.ieee.org/abstract/document/8622112/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8692921854542396209&hl=en)

- `MCS` [Liang et al., Proc. CVPR 2019] **Distant supervised centroid shift: A simple and efficient approach to visual domain adaptation** [[PDF]](https://openaccess.thecvf.com/content_CVPR_2019/html/Liang_Distant_Supervised_Centroid_Shift_A_Simple_and_Efficient_Approach_to_CVPR_2019_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6967341548116354815&hl=en) [[CODE]](http://liangjian.xyz/publications.html)

## Surveys
- `...` [Liu et al., Arxiv 2021] **Data-free knowledge transfer: A survey** [[PDF]](https://arxiv.org/abs/2112.15278) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5352982607916438632&hl=en)

- `...` [Fang et al., Arxiv 2023] **Source-free unsupervised domain adaptation: A survey** [[PDF]](https://arxiv.org/abs/2301.00265) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6946137905131972989&hl=en)

- `...` [Yu et al., Arxiv 2023] **A comprehensive survey on source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2302.11803) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1321308630726521384&hl=en)

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

- `SFDA-IT` [Hou and Zheng, Arxiv 2020] **Source free domain adaptation with image translation** [[PDF]](https://arxiv.org/abs/2008.07514) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8470634382170061837&hl=en)

- `UMSDE` [Zhang et al., Arxiv 2020] **Unsupervised domain expansion from multiple sources** [[PDF]](https://arxiv.org/abs/2005.12544) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5634883974973094592&hl=en)

- `TAN` [ Xu and Kang, Misc 2020] **Transfer alignment network for double blind unsupervised domain adaptation** [[PDF]](https://openreview.net/forum?id=BJxGan4FPB) [[G-Scholar--]]()

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

- `LA-VAE` [Yang et al., IEEE TIP 2021] **Model-induced generalization error bound for information-theoretic representation learning in source-data-free unsupervised domain adaptation** [[PDF]](https://ieeexplore.ieee.org/document/9640468) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7383037725836827645&hl=en)]

- `OSHT-SC` [Feng et al., IEEE TIP 2021] **Open-set hypothesis transfer with semantic consistency** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9474954/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11598574187674894813&hl=en)

- `VDM-DA` [Tian et al., IEEE TCSVT 2021] **VDM-DA: Virtual domain modeling for source data-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9530705) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7229645414167343012&hl=en)

- `SFDA-APM` [Kim et al., IEEE TAI 2021] **Domain adaptation without source data** [[PDF]](https://arxiv.org/abs/2007.01524) [[G-Scholar]](https://scholar.google.com/scholar?cluster=68747551195247035&hl=en)

- ~~[Ma et al., Arxiv 2021] **Uncertainty-guided mixup for semi-supervised domain adaptation without source data** [[PDF]](https://arxiv.org/abs/2107.06707)~~
- `PIDM` [Ma et al., Knowledge-Based Systems 2022] **Source-free semi-supervised domain adaptation via progressive Mixup** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0950705122013041) [[G-Scholar--]](https://scholar.google.com/scholar?q=Source-free+semi-supervised+domain+adaptation+via+progressive+Mixup&hl=en)

- ~~[Yang et al., Arxiv 2021] **Transformer-based source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2105.14138)~~
- `TransDA` [Yang et al., Applied Intelligence 2022] **Self-training transformer for source-free domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s10489-022-04364-9) [[G-Scholar--]](https://scholar.google.com/scholar?q=Self-training+transformer+for+source-free+domain+adaptation&hl=en) [[CODE]](https://github.com/ygjwd12345/TransDA)

- `STDA` [Tian et al., Journal of Computer Science and Technology 2021] **Source-free unsupervised domain adaptation with sample transport learning** [[PDF]](https://link.springer.com/article/10.1007/s11390-021-1106-5) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9561134782602271879&hl=en)

- `OnTA` [Wang et al., Arxiv 2021] **On-target adaptation** [[PDF]](https://arxiv.org/abs/2109.01087) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18422951738657247374&hl=en)

- `PS` [Du et al., Arxiv 2021] **Generation, augmentation, and alignment: A pseudo-source domain based method for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2109.04015) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2594791991284117635&hl=en)

- `SFDA-MBNS` [Ishii and Sugiyama, Arxiv 2021] **Source-free domain adaptation via distributional alignment by matching batch normalization statistics** [[PDF]](https://arxiv.org/abs/2101.10842) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14393126740179968632&hl=en)

- `N2DC-EX` [Tang et al., Arxiv 2021] **Nearest neighborhood-based deep clustering for source data-absent unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2107.12585) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13195135963977220100&hl=en) [[CODE]](https://github.com/tntek/N2DCX)

- `BAIT` [Yang et al., Arxiv 2021] **Casting a BAIT for offline and online source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2010.12427) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8008092994774409713&hl=en) [[CODE]](https://github.com/Albert0147/BAIT_SFUDA)

- `UMAD` [Liang et al., Arxiv 2021] **UMAD: Universal model adaptation under domain and category shift** [[PDF]](https://arxiv.org/abs/2112.08553) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11487080011595938912&hl=en)

- `SMUDA` [Stan and Rostami, Arxiv 2021] **Secure domain adaptation with multiple sources** [[PDF]](https://arxiv.org/abs/2106.12124) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9152141243814212262&hl=en)

- `UB2DA-ST` [Deng et al., Arxiv 2021] **On universal black-box domain adaptation** [[PDF]](https://arxiv.org/abs/2104.04665) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11465604669722215123&hl=en) [[CODE]](https://github.com/Gorilla-Lab-SCUT/UB2DA)

- `USFDA-DAT` [Wu et al., Arxiv 2021] **Domain adaptation without model transferring** [[PDF]](https://arxiv.org/abs/2107.10174) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4795862503178355859&hl=en)

- `CDL` [Wang et al., Arxiv 2021] **Learning invariant representation with consistency and diversity for semi-supervised source hypothesis transfer** [[PDF]](https://arxiv.org/abs/2107.03008) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6313297467321181817&hl=en) [[CODE]](https://github.com/Wang-Xiaodong1899/SSHT)

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

- `D-MCD` [Chu et al., Proc. AAAI 2022] **Denoised maximum classifier discrepancy for source-free unsupervised domain adaptation** [[PDF]](https://www.aaai.org/AAAI22Papers/AAAI-758.ChuT.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5829988423711925015&hl=en) 

- `ELPT` [Li et al., Proc. ACMMM 2022] **Source-free active domain adaptation via energy-based locality preserving transfer** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3503161.3548152) [[G-Scholar--]]()

- `PCSR` [Guan et al., Proc. BMVC 2022] **Polycentric clustering and structural regularization for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2210.07463) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10777900923119722899&hl=en) [[CODE]](https://github.com/Gxinuu/PCSR)

- `DMAPL` [Yan and Guo, Proc. BMVC 2022] **Dual moving average pseudo-labeling for source-free inductive domain adaptation** [[PDF]](https://bmvc2022.mpi-inf.mpg.de/0965.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15318503214717444323&hl=en) [[CODE]](https://github.com/cnyanhao/dmapl)

- `R-SFDA` [Agarwal et al., Proc. WACV 2022] **Unsupervised robust domain adaptation without source data** [[PDF]](https://openaccess.thecvf.com/content/WACV2022/html/Agarwal_Unsupervised_Robust_Domain_Adaptation_Without_Source_Data_WACV_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17077601123730740232&hl=en)

- ~~[Ahmed et al., Arxiv 2021] **Adaptive pseudo-label refinement by negative ensemble learning for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2103.15973)~~
- `NEL` [Ahmed et al., Proc. WACV 2022] **Cleaning noisy labels by negative ensemble learning for source-free unsupervised domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/WACV2022/html/Ahmed_Cleaning_Noisy_Labels_by_Negative_Ensemble_Learning_for_Source-Free_Unsupervised_WACV_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17709195455145675886&hl=en)

- `CXDA` [Bohdal et al., Proc. ICML Workshops 2022] **Feed-forward source-free latent domain adaptation via cross-attention** [[PDF]](https://openreview.net/forum?id=EiQB09V5IX) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15837576530441040681&hl=en)

- `VDB` [Yazdanpanah and Moradi, Proc. CVPR Workshops 2022] **Visual domain bridge: A source-free domain adaptation for cross-domain few-shot learning** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022W/FaDE-TCV/html/Yazdanpanah_Visual_Domain_Bridge_A_Source-Free_Domain_Adaptation_for_Cross-Domain_Few-Shot_CVPRW_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8987483615037403626&hl=en) [[CODE]](https://github.com/MosyMosy/VDB) 

- `PDA-MCD` [Bohdal et al., Proc. ECCV Workshops 2022] **Feed-forward source-free domain adaptation via class prototypes** [[PDF]](https://www.ood-cv.org/camera-ready/18/Feed_Forward_Source_Free_Domain_Adaptation_via_Class_Prototypes_ECCV_OOD_CV_Workshop.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3669131835455309637&hl=en)

- `SSNLL` [Chen et al., Proc. IROS 2022] **Self-supervised noisy label learning for source-free unsupervised domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9981099) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1592993425069201322&hl=en)

- `GAM` [Li et al., Proc. IJCNN 2022] **Source-free multi-domain adaptation with generally auxiliary model training** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9892718) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14752699554424187119&hl=en)

- `CSFA` [Yeh et al., Proc. ICPR 2022] **Boosting source-free domain adaptation via confidence-based subsets feature alignment** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9956719/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16791079764420455525&hl=en)

- `SFISA` [Zhang and Zhang, Proc. PRICAI 2022] **Source-free implicit semantic augmentation for domain adaptation** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-20865-2_2) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8767449916454723152&hl=en)

- `c-FeaGen` [Xu et al., Proc. IGARSS 2022] **Source-free domain adaptation for cross-scene hyperspectral image classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9883053/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11763446447548009309&hl=en)

- `DC-WSL` [Song et al., Proc. ICNSC 2022] **SS8: Source data-free domain adaptation via deep clustering with weighted self-labelling** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10004109) [[G-Scholar--]]()

- `SFDA-DML` [Zhang and Tian, Proc. ICCWAMTIP 2022] **Source-free unsupervised domain adaptation via denoising mutual learning** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10016534) [[G-Scholar--]]()

- `DEB` [Sun et al., Proc. DSIT 2022] **Source-free unsupervised domain adaptation in imbalanced datasets** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9943839/) [[G-Scholar--]]() [[CODE]](https://github.com/zju-SWJ/DEB)

  -------------------------------

- `SCLM` [Tang et al., Neural Networks 2022] **Semantic consistency learning on manifold for source data-free unsupervised domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0893608022001897) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6192182099886884315&hl=en) [[CODE]](https://github.com/tntek/SCLM)

- `DEEM` [Ma et al., Neural Networks 2022] **Context-guided entropy minimization for semi-supervised domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0893608022002672) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11282923299185576921&hl=en) [[CODE]](https://github.com/NingMa-AI/DEEM)

- `CDCL` [Wang et al., IEEE TMM 2022] **Cross-domain contrastive learning for unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2106.05528) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12061580303029241170&hl=en)

- `SFUDA-TPS` [Tian et al., ACM TIST 2022] **Source-free unsupervised domain adaptation with trusted pseudo samples** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3570510) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15227982710957287262&hl=en)

- `RPL` [Rusak et al., TMLR 2022] **If your data distribution shifts, use self-learning** [[PDF]](https://openreview.net/forum?id=vqRzLv6POg) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5941215717305244351&hl=en) [[CODE]](https://github.com/bethgelab/robustness)

- `SAB` [Liu et al., IEEE SPL 2022] **Self-Alignment for Black-Box Domain Adaptation of Image Classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9842332/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7062030827885381470&hl=en)

- `CdKD-TSML` [Li et al., Knowledge-Based Systems 2022] **Teacher-student mutual learning for efficient source-free unsupervised domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0950705122013004) [[G-Scholar--]]()

- ~~[Liu et al., Proc. IJCNN 2022] **Source free domain adaptation via combined discriminative GAN model for image classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9891979/)~~
- `SFDA-ADT` [Liu et al., Applied Intelligence 2022] **A source free domain adaptation model based on adversarial learning for image classification** [[PDF]](https://link.springer.com/article/10.1007/s10489-022-04026-w) [[G-Scholar--]]()

- `Prototype-DA` [Zhou et al., Neural Computing and Applications 2022] **Domain adaptation based on source category prototypes** [[PDF]](https://link.springer.com/article/10.1007/s00521-022-07601-x) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6719077136563993281&hl=en)

- `SFMBD` [Tian et al., Computers and Electrical Engineering 2022] **Source-free unsupervised domain adaptation with maintaining model balance and diversity** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0045790622006255) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7714251640306082635&hl=en)

- `LCCL` [Zhao et al., Sensors 2022] **Adaptive contrastive learning with label consistency for source data free unsupervised domain adaptation** [[PDF]](https://www.mdpi.com/1424-8220/22/11/4238) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11201330395391735486&hl=en)

- `ProxyMix` [Ding et al., Arxiv 2022] **ProxyMix: Proxy-based mixup training with label refinery for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2205.14566) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8949644873839998049&hl=en) [[CODE]](https://github.com/YuheD/ProxyMix)

- ~~[Thopalli et al., Proc. ECCV Workshops 2022] **Geometric alignment improves fully test time adaptation** [[PDF]](https://www.osti.gov/servlets/purl/1874540) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13916311599404592721&hl=en)~~
- `CATTAn` [Thopalli et al., Arxiv 2022] **Domain alignment meets fully test-time adaptation** [[PDF]](https://arxiv.org/abs/2207.04185) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10216954534487118514&hl=en) [[CODE]](https://github.com/kowshikthopalli/CATTAn)

- `JN` [Li et al., Arxiv 2022] **Jacobian norm for unsupervised source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2204.03467) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5396999793069796054&hl=en)

- `DAMC` [Zong et al., Arxiv 2022] **Domain gap estimation for source free unsupervised domain adaptation with many classifiers** [[PDF]](https://arxiv.org/abs/2207.05785) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6654662849120853418&hl=en) [[CODE]](https://github.com/hejunzz/damc)

- `FAUST` [Lee et al., Arxiv 2022] **Feature alignment by uncertainty and self-training for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2208.14888) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10962800013146398747&hl=en)

- `RCHC` [Diamant et al., Arxiv 2022] **Reconciling a centroid-hypothesis conflict in source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2212.03795) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5648022280349163503&hl=en) [[CODE]](https://github.com/ssi-research/SFDA-RCHC)

- `SF-PGL` [Luo et al., Arxiv 2022] **Source-free progressive graph learning for open-set domain adaptation** [[PDF]](https://arxiv.org/abs/2202.06174) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14360634658486858894&hl=en) [[CODE]](https://github.com/Luoyadan/SF-PGL)

- `MSFDA-SPL` [Shen et al., Arxiv 2022] **On the benefits of selectivity in pseudo-labeling for unsupervised multi-source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2202.00796) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2134048083339350660&hl=en)

- `Co-learn` [Zhang et al., Arxiv 2022] **Co-learning with pre-trained networks improves source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2212.07585) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3923590156178913294&hl=en)

- `UTR` [Pei et al., Arxiv 2022] **Uncertainty-induced transferability representation for source-free unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2208.13986) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1877809484055795117&hl=en) [[CODE]](https://github.com/SPIresearch/UTR)

- `k-sBetas` [Chiaroni et al., Arxiv 2022] **Simplex clustering via sBeta with applications to online adjustment of black-box predictions** [[PDF]](https://arxiv.org/abs/2208.00287) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16306533923372320733&hl=en) [[CODE]](https://github.com/fchiaroni/Clustering_Softmax_Predictions/)

- `MHPL` [Wang et al., Arxiv 2022] **Active source free domain adaptation** [[PDF]](https://arxiv.org/abs/2205.10711) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13385267099164282245&hl=en)

- `FMML` [Peng et al., Arxiv 2022] **Toward better target representation for source-free and black-box domain adaptation** [[PDF]](https://arxiv.org/abs/2208.10531) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3991269860438698249&hl=en)

- `EXTERN` [Xu et al., Arxiv 2022] **EXTERN: Leveraging endo-temporal regularization for black-box video domain adaptation** [[PDF]](https://arxiv.org/abs/2208.05187) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15714245550833050789&hl=en)

- `...` [Al-Maliki et al., Arxiv 2022] **Continual conscious active fine-tuning to robustify online machine learning models against data distribution shifts** [[PDF]](https://arxiv.org/abs/2211.01315) [[G-Scholar]](https://scholar.google.com/scholar?cluster=908547004835103765&hl=en)

- `OneRing` [Yang et al., Arxiv 2022] **One ring to bring them all: Model adaptation under domain and category shift** [[PDF]](https://openreview.net/forum?id=dOq0Jbg9hUt) [[G-Scholar]](https://scholar.google.com/scholar?cluster=531273051886454866&hl=en) [[CODE]](https://github.com/Albert0147/OneRing_SF-UNDA)

- `DePT` [Gao et al., Misc 2022] **Visual prompt tuning for test-time domain adaptation** [[PDF]](https://openreview.net/forum?id=3HnIBTjlXTS) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13014566741154429642&hl=en)

- `FTA-FDA` [Peng, Thesis 2022] **Multi-source and source-private cross-domain learning for visual recognition** [[PDF]](https://scholarworks.iupui.edu/handle/1805/29176) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7887089934777244066&hl=en)

### 2023
- `ELR` [Yi et al., Proc. ICLR 2023] **When source-free domain adaptation meets learning with noisy labels** [[PDF]](https://openreview.net/forum?id=u2Pd6x794I) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16104249125202927341&hl=en)

- `BETA` [Yang et al., Proc. ICLR 2023] **Divide to adapt: Mitigating confirmation bias for domain adaptation of black-box predictors** [[PDF]](https://openreview.net/forum?id=hVrXUps3LFA) [[G-Scholar]](https://scholar.google.com/scholar?cluster=202403539281549302&hl=en) [[CODE]](https://github.com/xyupeng/BETA)

- `Twofer` [Liu et al., Proc. ICLR 2023] **Twofer: Tackling continual domain shift with simultaneous domain generalization and adaptation** [[PDF]](https://openreview.net/forum?id=L8iZdgeKmI6) [[G-Scholar--]]()

- `PLUE` [Liu et al., Proc. CVPR 2023] **Guiding pseudo-labels with uncertainty estimation for test-time adaptation** [[PDF]](https://arxiv.org/abs/2303.03770) [[G-Scholar--]]() [[CODE]](https://github.com/MattiaLitrico/Guiding-Pseudo-labels-with-Uncertainty-Estimation-for-Test-Time-Adaptation)

- `GLC` [Qu et al., Proc. CVPR 2023] **Upcycling models under domain and category shift** [[PDF]](https://arxiv.org/abs/2303.07110) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4154930328281454966&hl=en) [[CODE]](https://github.com/ispc-lab/GLC)

- `C-SFDA` [Karim et al., Proc. CVPR 2023] **C-SFDA: A curriculum learning aided self-training framework for efficient source free domain adaptation** [[PDF]](https://niluthpol.github.io/Niluthpol_Mithun_Files/CSFDA_CVPR_2023.pdf) [[G-Scholar--]]() 

- `APA` [Sun et al., Proc. AAAI 2023] **Domain adaptation with adversarial training on penultimate activations** [[PDF]](https://arxiv.org/abs/2208.12853) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13152361105316809189&hl=en) [[CODE]](https://github.com/tsun/APA)

- `CoNMix` [Kumar et al., Proc. WACV 2023] **Conmix for source-free single and multi-target domain adaptation** [[PDF]](https://arxiv.org/abs/2211.03876) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1532883985875939147&hl=en) [[CODE]](https://github.com/vcl-iisc/CoNMix)

- `GAP` [Chhabra et al., Proc. WACV 2023] **Generative alignment of posterior probabilities for source-free domain adaptation** [[PDF]](https://openaccess.thecvf.com/content/WACV2023/html/Chhabra_Generative_Alignment_of_Posterior_Probabilities_for_Source-Free_Domain_Adaptation_WACV_2023_paper.html) [[G-Scholar--]]()

- ~~[Kothandaraman et al., Arxiv 2022] **DistillAdapt: Source-free active visual domain adaptation** [[PDF]](https://arxiv.org/abs/2205.12840)~~
- `SALAD` [Kothandaraman et al., Proc. WACV 2023] **SALAD: Source-free active label-agnostic domain adaptation for classification, segmentation and detection** [[PDF]](https://arxiv.org/abs/2205.12840) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6017453879092897523&hl=en) [[CODE]](https://github.com/divyakraman/SALAD_SourcefreeActiveLabelAgnosticDomainAdaptation)

  ---------------------------------
- ~~[Xu et al., Proc. IGARSS 2022] **Universal domain adaptation without source data for remote sensing image scene classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9884889/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15682142231027232982&hl=en)~~
- `SDG-MA` [Xu et al., IEEE TGRS 2023] **Universal domain adaptation for remote sensing image scene classification** [[PDF]](https://arxiv.org/abs/2301.11387) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7802316111188678098&hl=en)[[CODE]](https://github.com/zhu-xlab/UniDA)

- ~~[Taufique et al., Arxiv 2021] **ConDA: Continual unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2103.11056)~~
- `ConDA` [Taufique et al., IEEE TAI 2023] **Continual unsupervised domain adaptation in data-constrained environments** [[PDF]](https://ieeexplore.ieee.org/document/10005797) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8385541483815025219&hl=en)

- `RS2L` [Tian et al., Signal, Image and Video Processing 2023] **Robust self-supervised learning for source-free domain adaptation** [[PDF]](https://link.springer.com/article/10.1007/s11760-022-02457-z) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18298807507396100788&hl=en)

- `MViT-PCD` [Dai et al., IEEE Geoscience and Remote Sensing Letters 2023] **MViT-PCD: A lightweight ViT-based network for martian surface topographic change detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10007802/) [[G-Scholar--]]() [[CODE]](https://github.com/lynn1023-max/MViTPCD)

- `ALT` [Wu et al., Arxiv 2023] **When source-free domain adaptation meets label propagation** [[PDF]](https://arxiv.org/abs/2301.08413) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16104249125202927341&hl=en)

- `CaC` [Chen et al., Arxiv 2023] **Contrast and clustering: Learning neighborhood pair representation for source-free domain adaptation** [[PDF]](https://arxiv.org/abs/2301.13428) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3921052647478939852&hl=en) [[CODE]](https://github.com/yukilulu/CaC)

- `GarDA` [Chen et al., Arxiv 2023] **Generative appearance replay for continual unsupervised domain adaptation** [[PDF]](https://arxiv.org/abs/2301.01211) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3516019922974363817&hl=en)

- `PCD` [Tanwisuth et al., Arxiv 2023] **A prototype-oriented clustering for domain shift with source privacy** [[PDF]](https://arxiv.org/abs/2302.03807) [[G-Scholar--]]() 

- `SCA` [Maracani et al., Arxiv 2023] **Key design choices for double-transfer in source-free unsupervised domain adaptation** [[PDF]](https://openreview.net/forum?id=-PL1Gk4jt7) [[G-Scholar--]]()

- `E2` [Shen et al., Misc 2023]  **E2: Entropy discrimination and energy optimization for source-free universal domain adaptation** [[PDF]](https://openreview.net/forum?id=FMEXgK9-I8) [[G-Scholar--]]()

- `SepRep-Net` [Jin et al., Misc 2023] **SepRep-Net: Multi-source free domain adaptation via model separation and reparameterization** [[PDF]](https://openreview.net/forum?id=E67OghNSDMf) [[G-Scholar--]]()

- `AdaptGuard` [Sheng et al., Misc 2023] **AdaptGuard: Defending against universal attacks for model adaptation** [[PDF]](https://arxiv.org/abs/2303.10594) [[G-Scholar--]]() 

## Semantic Segmentation
### 2021
- `SFDA-UR` [Sivaprasad and Fleuret, Proc. CVPR 2021] **Uncertainty reduction for model adaptation in semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/S_Uncertainty_Reduction_for_Model_Adaptation_in_Semantic_Segmentation_CVPR_2021_paper.html?ref=https://githubhelp.com) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10763756734865751592&hl=en) [[CODE]](https://github.com/idiap/model-uncertainty-for-adaptation)

- `SFDA-KTMA` [Liu et al., Proc. CVPR 2021] **Source-free domain adaptation for semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Liu_Source-Free_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2021_paper.html?ref=https://githubhelp.com) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9907456742879822543&hl=en)

- `SoMAN-cPAE` [Kundu et al., Proc. ICCV 2021] **Generalize then adapt: Source-free domain adaptive semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/ICCV2021/html/Kundu_Generalize_Then_Adapt_Source-Free_Domain_Adaptive_Semantic_Segmentation_ICCV_2021_paper.html?ref=https://githubhelp.com) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6109459705970378905&hl=en) [[CODE]](https://github.com/val-iisc/SFDA-Seg)

- `MAS3` [Stan and Rostami, Proc. AAAI 2021] **Unsupervised model adaptation for continual semantic segmentation** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/16362) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11863380647808017555&hl=en) [[CODE]](https://github.com/serbanstan/mas3-continual) 

- `LD` [You et al., Proc. ACMMM 2021] **Domain adaptive semantic segmentation without source data** [[PDF]](https://arxiv.org/abs/2110.06484) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2164649778847843995&hl=en) [[CODE]](https://github.com/fumyou13/LDBE)

- `SFDA-VS` [Ye et al., Proc. ACMMM 2021] **Source data-free unsupervised domain adaptation for semantic segmentation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3474085.3475384) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15526409977910918571&hl=en)

- ~~[Prabhu et al., Arxiv 2021] **S4T: Source-free domain adaptation for semantic segmentation via self-supervised selective self-training** [[PDF]](https://arxiv.org/abs/2107.10140)~~ 
- ~~[Prabhu et al., Proc. ECCV Workshops 2022] **AUGCO: Augmentation consistency-guided self-training for source-free domain adaptive semantic segmentation** [[PDF]](https://arxiv.org/abs/2107.10140)~~ 
- `AUGCO` [Prabhu et al., Proc. NeurIPS Workshops 2022] **Augmentation consistency-guided self-training for source-free domain adaptive semantic segmentation** [[PDF]](https://openreview.net/forum?id=tOCxfUebrlz) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14612502916018600679&hl=en)

  -----------------------

- `PR-SFDA` [Luo et al., Arxiv 2021] **Exploiting negative learning for implicit pseudo label rectification in source-free domain adaptive semantic segmentation** [[PDF]](https://arxiv.org/abs/2106.12123) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15003821819568404211&hl=en)

- `SFDA-ST` [Paul et al., Arxiv 2021] **Unsupervised adaptation of semantic segmentation models without source data** [[PDF]](https://arxiv.org/abs/2112.02359) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10130538691883639678&hl=en)

- `ATP` [Wang et al., Arxiv 2021] **Source data-free cross-domain semantic segmentation: align, teach and propagate** [[PDF]](https://arxiv.org/abs/2106.11653) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15515597080922741941&hl=en)

### 2022
- `RIPU` [Xie et al., Proc. CVPR 2022] **Towards fewer annotations: Active learning via region impurity and prediction uncertainty for domain adaptive semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022/html/Xie_Towards_Fewer_Annotations_Active_Learning_via_Region_Impurity_and_Prediction_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=907514128348245282&hl=en) [[CODE]](https://github.com/BIT-DA/RIPU)

- `SimT` [Guo et al., Proc. CVPR 2022] **SimT: Handling open-set noise for domain adaptive semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022/html/Guo_SimT_Handling_Open-Set_Noise_for_Domain_Adaptive_Semantic_Segmentation_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9175191664302585452&hl=en) [[CODE]](https://github.com/CityU-AIM-Group/SimT)

- `OnDA` [Panagiotakopoulos et al., Proc. ECCV 2022] **Online domain adaptation for semantic segmentation in ever-changing conditions** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940125.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13123083871593814171&hl=en) [[CODE]](https://github.com/theo2021/OnDA)

- `UnMSMA-MiFL` [Li et al., Proc. ECCV 2022] **Union-set multi-source model adaptation for semantic segmentation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136890570.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8783974652276072046&hl=en) [[CODE]](https://github.com/lzy7976/union-set-model-adaptation)

- `UBNA` [Klingner et al., Proc. WACV Workshops 2022] **Unsupervised batchnorm adaptation \(ubna\): A domain adaptation method for semantic segmentation without using source domain representations** [[PDF]](https://openaccess.thecvf.com/content/WACV2022W/DNOW/html/Klingner_Unsupervised_BatchNorm_Adaptation_UBNA_A_Domain_Adaptation_Method_for_Semantic_WACVW_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8599373467519099477&hl=en) [[CODE]](https://github.com/ifnspaml/UBNA)

- `DTAC` [Yang et al., Proc. ICME 2022] **Source free domain adaptation for semantic segmentation via distribution transfer and adaptive class-balanced self-training** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9859581/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8777021429851186285&hl=en)

- `MSMA-MiFL` [Li et al., Proc. ICIP 2022] **Improving model adaptation for semantic segmentation by learning model-invariant features with multiple source-domain models** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9897487/) [[G-Scholar--]]()

  ------------------

- `SPGM` [Yang et al., IEEE TIFS 2022] **Revealing task-relevant model memorization for source-protected unsupervised domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9705526) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7510566731887672556&hl=en)

- `CPSS` [Zhao et al., IEEE TCSVT 2022] **Source-free open compound domain adaptation in semantic segmentation** [[PDF]](http://yuyangzhao.com/files/sfocda-tcsvt.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3170260958747192184&hl=en) [[CODE]](https://github.com/HeliosZhao/SFOCDA)

- `RuST` [Luo et al., IEEE RAL 2022] **Multi-level consistency learning for source-free model adaptation** [[PDF]](https://ieeexplore.ieee.org/document/9928327/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5126397401023348966&hl=en)

- `STvM` [Akkaya et al., Arxiv 2022] **Self-training via metric learning for source-free domain adaptation of semantic segmentation** [[PDF]](https://arxiv.org/abs/2212.04227) [[G-Scholar--]]()

- `CONDA` [Truong et al., Arxiv 2022] **CONDA: Continual unsupervised domain adaptation learning in visual perception for self-driving cars** [[PDF]](https://arxiv.org/abs/2212.00621) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13009693848444756082&hl=en)

### 2023
---------------------------------

- `STAL` [Guan and Yuan, Arxiv 2023] **Iterative loop learning combining self-training and active learning for domain adaptive semantic segmentation** [[PDF]](https://arxiv.org/abs/2301.13361) [[G-Scholar]](https://scholar.google.com/scholar?cluster=580721324325082611&hl=en) [[CODE]](https://github.com/licongguan/STAL)

- `BTOL` [Wang et al., Arxiv 2023] **Bootstrap the original latent: Freeze-and-thaw adapter for back-propagated black-box adaptation** [[PDF]](https://arxiv.org/abs/2303.03709) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15783455669601732347&hl=en)

- `CMA` [Bruggemann et al., Arxiv 2023] **Contrastive model adaptation for cross-condition robustness in semantic segmentation** [[PDF]](https://arxiv.org/abs/2303.05194) [[G-Scholar--]]() [[CODE]](https://github.com/brdav/cma)

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

- `MoTE` [VS et al., Proc. ICIP 2022] **Mixture of teacher experts for source-free domain adaptive object detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9897795/) [[G-Scholar--]]()

  ---------------------------
  
- `PLA-DAP` [Xiong et al., Pattern Recognition 2022] **Source data-free domain adaptation for a faster R-CNN** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320321006129) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2911507652442359206&hl=en) [[CODE]](https://github.com/xiong233/Source-Data-free-Domain-Adaptation-for-a-Faster-R-CNN)

- `IRG` [VS et al., Arxiv 2022] **Instance relation graph guided source-free domain adaptive object detection** [[PDF]](https://arxiv.org/abs/2203.15793) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14769368441924132436&hl=en) [[CODE]](https://github.com/Vibashan/irg-sfda)

- `G&A` [Zhao et al., Arxiv 2022] **1st place solution for ECCV 2022 OOD-CV challenge object detection track** [[PDF]](https://arxiv.org/abs/2301.04796) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14155562576343532471&hl=en)

### 2023
- `TeST` [Sinha et al., Proc. WACV 2023] **TeST: Test-time self-training under distribution shift** [[PDF]](https://arxiv.org/abs/2209.11459) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5034697452433918735&hl=en)

- `MemCLR` [VS et al., Proc. WACV 2023] **Towards online domain adaptive object detection** [[PDF]](https://openaccess.thecvf.com/content/WACV2023/html/VS_Towards_Online_Domain_Adaptive_Object_Detection_WACV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8996531248585805791&hl=en)

- `RPL` [Zhang et al., Proc. ICASSP 2023] **Refined pseudo labeling for source-free domain adaptive object detection** [[PDF]](https://arxiv.org/abs/2303.03728) [[G-Scholar--]]()

  ---------------------

- `SFDA-STW` [Yang et al., IEEE TIM 2023] **Source-free domain adaptive detection of concealed objects in passive millimeter-wave images** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10019315/) [[G-Scholar--]]()

- `A2SFOD` [Chu et al., Arxiv 2023] **Adversarial alignment for source free object detection** [[PDF]](https://arxiv.org/abs/2301.04265) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3777004265512378062&hl=en)

- `...` [Naik et al., Arxiv 2023] **Do machine learning models learn common sense?** [[PDF]](https://arxiv.org/abs/2303.01433) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11920731748225216277&hl=en)

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

- ~~[Liu et al., Proc. SPIE Medical Imaging 2022] **Unsupervised domain adaptation for segmentation with black-box source model** [[PDF]](https://arxiv.org/abs/2208.07769)~~
- `BBUDA-EMD` [Liu et al., Frontiers in Neuroscience 2022] **Unsupervised black-box model domain adaptation for brain tumor segmentation** [[PDF]](https://www.frontiersin.org/articles/10.3389/fnins.2022.837646/full?amp;amp) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8709673335885735259&hl=en)

- `TT-SFUDA` [VS et al., Arxiv 2022] **Target and task specific source-free domain adaptive image segmentation** [[PDF]](https://arxiv.org/abs/2203.15792) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17947897479931623051&hl=en) [[CODE]](https://github.com/Vibashan/tt-sfuda)

- `SFDA-NS` [Kondo, Arxiv 2022] **Source-free unsupervised domain adaptation with norm and shape constraints for medical image segmentation** [[PDF]](https://arxiv.org/abs/2209.01300) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11603944637647696822&hl=en)

- `ProSFDA` [Hu et al., Arxiv 2022] **ProSFDA: Prompt learning based source-free domain adaptation for medical image segmentation** [[PDF]](https://arxiv.org/abs/2211.11514) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15541289658900461005&hl=en) [[CODE]](https://github.com/ShishuaiHu/ProSFDA)

- `IOP-FL` [Jiang et al., Arxiv 2022] **IOP-FL: Inside-outside personalization for federated medical image segmentation** [[PDF]](https://arxiv.org/abs/2204.08467) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10670356016526924774&hl=en)

- `SFDA-GEM` [Yuan et al., Misc 2022] **Source protection domain adaptation by gumbel-min-max entropy minimization** [[PDF]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4220604) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12468488454287850515&hl=en)

- `PLP` [Song, Misc 2022] **Source-free few-shot semi-supervised domain adaptation for CT image classification** [[PDF]](https://arxiv.org/abs/2207.08124) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2138500387139877671&hl=en)

- `...` [Li et al., Misc 2022] **Source-free unsupervised adaptive segmentation for knee joint MRI** [[PDF]](https://www.techrxiv.org/articles/preprint/Source-free_Unsupervised_Adaptive_Segmentation_for_Knee_Joint_MRI/21749414) [[G-Scholar--]]()

### 2023
- `CP3Net` [Feng et al., Knowledge-Based Systems 2023] **Cross-platform privacy-preserving CT image COVID-19 diagnosis based on source-free domain adaptation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0950705123000746) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13133706915130616700&hl=en)

- `RAF` [Yuan et al., The Visual Computer 2023] **Data privacy protection domain adaptation by roughing and finishing stage** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1000936123000493) [[G-Scholar--]]()


## Video Classification
### 2022
- `ATCoN` [Xu et al., Proc. ECCV 2022] **Learning temporal consistency for source-free video domain adaptation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940144.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4238691108482542310&hl=en) [[CODE]](https://github.com/xuyu0010/ATCoN)

- `MTRAN` [Huang et al., Proc. ACMMM 2022] **Relative alignment network for source-free multimodal video domain adaptation** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3503161.3548009) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16061407528461480325&hl=en)

- `SFTADA` [Chen and Ma, Proc. ICMR 2022] **Source-free temporal attentive domain adaptation for video action recognition** [[PDF]](https://dl.acm.org/doi/abs/10.1145/3512527.3531392) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14618082401482357386&hl=en)

- `RNA++` [Plananamente et al., Proc. ICIAP 2022] **Test-time adaptation for egocentric action recognition** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-06433-3_18) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2806024882988284863&hl=en) [[CODE]](https://github.com/EgocentricVision/RNA-TTA)

- `CleanAdapt` [Dasgupta et al., Proc. ICVGIP 2022] **Overcoming label noise for source-free unsupervised video domain adaptation** [[PDF]](https://hal.science/hal-03929619/document) [[G-Scholar]](https://scholar.google.com/scholar?cluster=623684659834620344&hl=en)


## 3D Point Cloud Perception
### 3D Object Detection
- `SF-UDA3D` [Saltori et al., Proc. 3DV 2020] **SF-UDA3D: Source-free unsupervised domain adaptation for lidar-based 3d object detection** [[PDF]](https://arxiv.org/abs/2010.08243) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12668139134909180101&hl=en) [[CODE]](https://github.com/saltoricristiano/SF-UDA-3DV)

- `UAMT` [Hegde et al., Arxiv 2021] **Uncertainty-aware mean teacher for source-free unsupervised domain adaptive 3d object detection** [[PDF]](https://arxiv.org/abs/2109.14651) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15247976641359211271&hl=en) [[CODE]](https://github.com/deeptibhegde/UncertaintyAwareMeanTeacher)

- `AP-SFDA` [Hegde et al., Arxiv 2021] **Attentive prototypes for source-free unsupervised domain adaptive 3d object detection** [[PDF]](https://arxiv.org/abs/2111.15656) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4281673598628254257&hl=en) [[CODE]](https://github.com/deeptibhegde/AttentivePrototypeSFUDA)

- `ST3D` [Yang et al., Proc. CVPR 2021] **ST3D: Self-training for unsupervised domain adaptation on 3d object detection** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Yang_ST3D_Self-Training_for_Unsupervised_Domain_Adaptation_on_3D_Object_Detection_CVPR_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12232176416755323092&hl=en) [[CODE]](https://github.com/CVMI-Lab/ST3D)

- `Dreaming` [You et al., Proc. ICRA 2022] **Exploiting playbacks in unsupervised domain adaptation for 3d object detection** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9811722/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2067943135953406159&hl=en)

### 3D Pose Estimation
- `Anat-SFDA` [Bigalke et al., Arxiv 2022] **Anatomy-guided domain adaptation for 3D in-bed human pose estimation** [[PDF]](https://arxiv.org/abs/2211.12193) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5720884605736008576&hl=en) [[CODE]](https://github.com/multimodallearning/da-3dhpe-anatomy)

### 3D Lidar Segmentation
- `GIPSO` [Saltori et al., Proc. ECCV 2022] **GIPSO: Geometrically informed propagation for online adaptation in 3d lidar segmentation** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930557.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13813760731976228346&hl=en) [[CODE]](https://github.com/saltoricristiano/gipso-sfouda)


## Facial Analysis
### Face Anti-spoofing
- `AdaptML` [Wang et al., Proc. AAAI 2021] **Self-domain adaptation for face anti-spoofing** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/16379) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11751431376596364916&hl=en)

- `Self-Ensemble` [Lv et al., Proc. ICASSP 2021] **Combining dynamic image and prediction ensemble for cross-domain face anti-spoofing** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9413926/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13575521535806939327&hl=en)

- `GDA` [Zhou et al., Proc. ECCV 2022] **Generative domain adaptation for face anti-spoofing** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650328.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11917164576597623324&hl=en)

- `SDA-FAS` [Liu et al., Proc. ECCV 2022] **Source-free domain adaptation with contrastive domain alignment and self-supervised exploration for face anti-spoofing** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720506.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13216320534230331303&hl=en) [[CODE]](https://github.com/YuchenLiu98/ECCV2022-SDA-FAS)

### Occluded Face Recognition
- `SFOFR` [Zhang et al.,Proc. ICASSP 2022] **Free lunch for cross-domain occluded face recognition without source data** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9746642/) [[G-Scholar--]]()

### Facial Expression Recognition
- `CluP` [Conti et al., Proc. BMVC 2022] **Cluster-level pseudo-labelling for source-free cross-domain facial expression recognition** [[PDF]](https://bmvc2022.mpi-inf.mpg.de/0486.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6739844971812107667&hl=en) [[CODE]](https://github.com/altndrr/clup)


## Other CV Applications
### Person ReID
- `MtASD` [Wu et al., Proc. CVPR 2019] **Distilled person re-identification: Towards a more scalable system** [[PDF]](https://openaccess.thecvf.com/content_CVPR_2019/html/Wu_Distilled_Person_Re-Identification_Towards_a_More_Scalable_System_CVPR_2019_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4580639918930348414&hl=en)

- `MSFDA-PT` [Ding et al., The Visual Computer 2021] **Source-free unsupervised multi-source domain adaptation via proxy task for person re-identification** [[PDF]](https://link.springer.com/article/10.1007/s00371-021-02246-8) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17612309789629474685&hl=en)

### Cross-modality
- `SOCKET` [Ahmed et al., Proc. ECCV 2022] **Cross-modal knowledge transfer without task-relevant source data** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940108.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8131184106801888753&hl=en) [[CODE]](https://github.com/merlresearch/SOCKET)

- `PopNet` [Wu et al., Arxiv 2022] **Source-free depth for object pop-out** [[PDF]](https://arxiv.org/abs/2212.05370) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14863581017412360599&hl=en) [[CODE--]](https://github.com/Zongwei97/PopNet)

### Image Dehazing
- `DRN` [Yu et al., Proc. ACMMM 2022] **Source-free domain adaptation for real-world image dehazing** [[PDF]](https://arxiv.org/abs/2207.06644) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16555277816059371930&hl=en)

### Image Harmonization
- `Harmonizing-Flows` [Beizaee et al., Arxiv 2023] **Harmonizing flows: Unsupervised MR harmonization based on normalizing flows** [[PDF]](https://arxiv.org/abs/2301.11551) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14941931549061751891&hl=en) [[CODE]](https://github.com/farzad-bz/Harmonizing-Flows)

### Video Quality Enhancement
- `CVQE-MT` [Wang, Proc. ICCWAMTIP 2022] **An unsupervised domain adaptation method for compressed video quality enhancement** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10016616/) [[G-Scholar--]]()

### Image Quality Assessment
- `SFDA-SSLBN` [Liu et al., Arxiv 2022] **Source-free unsupervised domain adaptation for blind image quality assessment** [[PDF]](https://arxiv.org/abs/2207.08124) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2138500387139877671&hl=en)

### Road Segmentation (binary)
- `SS-SFDA` [Kothandaraman et al., Proc. ICCV Workshops 2021] **SS-SFDA: Self-supervised source-free domain adaptation for road segmentation in hazardous environments** [[PDF]](https://openaccess.thecvf.com/content/ICCV2021W/AVVision/html/Kothandaraman_SS-SFDA_Self-Supervised_Source-Free_Domain_Adaptation_for_Road_Segmentation_in_Hazardous_ICCVW_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2325306153552113178&hl=en) [[CODE]](https://github.com/divyakraman/SS-SFDA-Self-Supervised-Source-Free-Domain-Adaptation-for-Road-Segmentation-in-Hazardous-Environme)

### Sign Segmentation
- `CMPL` [Renz et al., Proc. CVPR Workshops 2021] **Sign segmentation with changepoint-modulated pseudo-labelling** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021W/ChaLearn/html/Renz_Sign_Segmentation_With_Changepoint-Modulated_Pseudo-Labelling_CVPRW_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10843136778842689752&hl=en) [[CODE]](https://github.com/RenzKa/sign-segmentation)

### Visual Document Understanding
- `DocTTA` [Ebrahimi et al., Arxiv 2022] **Test-time adaptation for visual document understanding** [[PDF]](https://arxiv.org/abs/2206.07240) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4974275319186080260&hl=en) [[DATA]](https://sites.google.com/berkeley.edu/doctta/)

### 2D Keypoint detection (Pose estimation)
- `MAPS` [Ding et al., Arxiv 2023] **MAPS: A noise-robust progressive learning approach for source-free domain adaptive keypoint detection** [[PDF]](https://arxiv.org/abs/2302.04589) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13949106311988540827&hl=en)

### Anomaly detection
- `CaSA` [Bozorgtabar et al., Proc. BMVC 2022] **Anomaly detection and localization using attention-guided synthetic anomaly and test-time adaptation** [[PDF]](https://bmvc2022.mpi-inf.mpg.de/0472.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=209397539357448856&hl=en)

## Beyond CV Applications
### 2020
- `...` [Laparra et al., JAMIA open 2020] **Rethinking domain adaptation for machine learning over clinical language** [[PDF]](https://academic.oup.com/jamiaopen/article/3/2/146/5831556) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15011224356081547243&hl=en)

### 2021
- `CdKD` [Zhao et al., Proc. ACL 2021] **Matching distributions between model and data: Cross-domain knowledge distillation for unsupervised domain adaptation** [[PDF]](https://aclanthology.org/2021.acl-long.421/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16829742576573810731&hl=en)

- `ActiveST` [Su et al., Proc. ACL SemEval 2021] **The University of Arizona at SemEval-2021 task 10: Applying self-training, active learning and data augmentation to source-free domain adaptation** [[PDF]](https://aclanthology.org/2021.semeval-1.56/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15617873900739629649&hl=en)

- `...` [Laparra et al., Proc. ACL SemEval 2021] **SemEval-2021 task 10: Source-free domain adaptation for semantic processing** [[PDF]](https://aclanthology.org/2021.semeval-1.42/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3826840294377233499&hl=en)

  ----------

- `e-SHOT-CE` [Cao et al., IEEE TVT 2021] **Towards cross-environment human activity recognition based on radar without source data** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9760113/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6452327194388265947&hl=en)

- `GCN-SOGA` [Mao et al., Arxiv 2021] **Source free unsupervised graph domain adaptation** [[PDF]](https://arxiv.org/abs/2112.00955) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8057939358946355621&hl=en)

### 2022
- `...` [Su et al., Proc. ACL 2022] **A comparison of strategies for source-free domain adaptation** [[PDF]](https://aclanthology.org/2022.acl-long.572/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4321860393076444396&hl=en) [[CODE]](https://github.com/xinsu626/SourceFreeDomainAdaptation)

- `MDMAML` [Li et al., IEEE CIM 2022] **Meta-learning for fast and privacy-preserving source knowledge transfer of EEG-based BCIs** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9942685) [[G-Scholar--]]()

- `MSDT` [Zhang et al., IEEE TNSRE 2022] **Multi-source decentralized transfer for privacy-preserving BCIs** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9894428/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2150739430618555059&hl=en)

- `LSFT` [Zhang and Wu, IEEE TCDS 2022] **Lightweight source-free transfer for privacy-preserving motor imagery classification** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9840893/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15691682036339231302&hl=en)

- `ASFA` [Xia et al., IEEE TBE 2022] **Privacy-preserving domain adaptation for motor imagery-based brain-computer interfaces** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9760113/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13402357178362327681&hl=en) [[CODE]](https://github.com/xkazm/ASFA)

- `T-ISTGNN` [Qi et al., IEEE TITS 2022] **Privacy-preserving cross-area traffic forecasting in ITS: A transferable spatial-temporal graph neural network approach** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9928430/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1841703851715000157&hl=en)

- `DP-SFDA` [An et al., IEEE TITS 2022] **A privacy-preserving unsupervised domain adaptation framework for clinical text analysis** [[PDF]](https://arxiv.org/abs/2201.07317) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15348410852649744691&hl=en)

- `SFAD` [Jiao et al., IEEE TII 2022] **Source-free adaptation diagnosis for rotating machinery** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9997572/) [[G-Scholar--]]()

- `scEMAIL` [Wan et al., Genomics, Proteomics and Bioinformatics 2022] **scEMAIL: Universal and source-free annotation method for scRNA-seq data with novel cell-type perception** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1672022922001747) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1698595785369986836&hl=en) [[CODE]](https://github.com/aster-ww/scEMAIL)

- `...` [Wang et al., Chinese Journal of Aeronautics 2022] **Source free unsupervised domain adaptation for electro-mechanical actuator fault diagnosis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1000936123000493) [[G-Scholar--]]()

- `IDANI` [Antverg et al., Arxiv 2022] **IDANI: Inference-time domain adaptation via neuron-level interventions** [[PDF]](https://aclanthology.org/2022.deeplo-1.3/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10046849600588003301&hl=en) [[CODE]](https://github.com/technion-cs-nlp/idani)

- `MDAQA` [Yin et al., Arxiv 2022] **Source-free domain adaptation for question answering with masked self-training** [[PDF]](https://arxiv.org/abs/2212.09563) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6098149583071335403&hl=en)

### 2023
- `...` [Lee et al., Proc. BCI 2023] **Source-free cross-domain state of charge estimation of lithium-ion batteries at different ambient temperatures** [[PDF]](https://arxiv.org/abs/2301.08448) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4013259541683787047&hl=en) [[CODE]](https://github.com/DeepBCI/Deep-BCI)

- `SFTTN` [Shen et al., IEEE TPEL 2023] **Source-free cross-domain state of charge estimation of lithium-ion batteries at different ambient temperatures** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10058040/) [[G-Scholar--]]()

- `HSSC-EMM` [Zhang et al., Mechanical Systems and Signal Processing 2023] **Universal source-free domain adaptation method for cross-domain fault diagnosis of machines** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0888327023000663) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9778377080450704864&hl=en)

- ~~[Boudiaf et al., Misc 2023] **NOTELA: A generalizable method for source free domain adaptation** [[PDF]](https://openreview.net/forum?id=aOBs18ycBr)~~
- `NOTELA` [Boudiaf et al., Arxiv 2023] **In search for a generalizable method for source free domain adaptation** [[PDF]](https://arxiv.org/abs/2302.06658) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12424145282212014491&hl=en)

## Misc
- [Yang et al., Proc. ACM-MM2007] **Cross-domain video concept detection using adaptive svms** [[PDF]](https://dl.acm.org/doi/abs/10.1145/1291233.1291276) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4589454669556425406&hl=en)
- [Aytal and Zisserman, Proc. ICCV 2011] **Tabula rasa: Model transfer for object category detection** [[PDF]](https://ieeexplore.ieee.org/document/6126504/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13106480027062040527&hl=en)
- [Kuzborskij et al., Proc. ICML 2013] **Stability and hypothesis transfer learning** [[PDF]](https://proceedings.mlr.press/v28/kuzborskij13.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5642234637780837688&hl=en)
- [Tommasi et al., IEEE TPAMI 2013] **Learning categories from few examples with multi model knowledge transfer** [[PDF]](https://ieeexplore.ieee.org/abstract/document/6620871/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10892813110202908253&hl=en)
- `AdaBN` [Li et al., Proc. ICLR 2017] **Revisiting batch normalization for practical domain adaptation** [[PDF]](https://openreview.net/forum?id=Hk6dkJQFx) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11679251260326951806&hl=en)
- `...` [Burns and Steinhardt, Proc. CVPR 2021] **Limitations of post-hoc feature alignment for robustness** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Burns_Limitations_of_Post-Hoc_Feature_Alignment_for_Robustness_CVPR_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10007615184186415315&hl=en) [[CODE]](https://github.com/collin-burns/feature-alignment)
- `DARE` [Rosenfeld et al., Proc. NeurIPS Workshops 2022] **Domain-adjusted regression or: ERM may already learn features sufficient for out-of-distribution generalization** [[PDF]](https://arxiv.org/abs/2202.06856) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18354400836987334001&hl=en)
- `GDSDA` [Ao et al., Proc. AAAI 2017] **Fast generalized distillation for semi-supervised domain adaptation** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/10848) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11001527589625859954&hl=en)
- `MapNet+` [Brahmbhatt et al., Proc. CVPR 2018] **Geometry-aware learning of maps for camera localization** [[PDF]](https://openaccess.thecvf.com/content_cvpr_2018/html/Brahmbhatt_Geometry-Aware_Learning_of_CVPR_2018_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15361942550307476955&hl=en)
- `dkdHTL` [Yu et al., Arxiv 2020] **Dynamic knowledge distillation for black-box hypothesis transfer learning** [[PDF]](https://arxiv.org/abs/2007.12355) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4102832996867063478&hl=en)
- `TOHAN` [Chi et al., Proc. NeurIPS 2021] **TOHAN: A one-step approach towards few-shot hypothesis adaptation** [[PDF]](https://openreview.net/forum?id=vrkQ07gp0kq) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3362363617253826009&hl=en) [[CODE]](https://github.com/Haoang97/TOHAN)
- `LCCS` [Zhang et al., Proc. IJCAI 2022] **Few-shot adaptation of pre-trained networks for domain shift** [[PDF]](https://arxiv.org/abs/2205.15234) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17927210508667621786&hl=en) [[CODE]](https://github.com/zwenyu/lccs)
- `CIDA` [Kundu et al., Proc. ECCV 2020] **Class-incremental domain adaptation** [[PDF]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580052.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15757977957260800975&hl=en)
- `TIDo` [Ambastha and Yun, Arxiv 2023] **TIDo: Source-free task incremental learning in non-stationary environments** [[PDF]](https://arxiv.org/abs/2301.12055) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17872927398350991456&hl=en)
- `ALeN` [Ambastha and Yun, Arxiv 2023] **Adversarial learning networks: Source-free unsupervised domain incremental learning** [[PDF]](https://arxiv.org/abs/2301.12055) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3178251369340369001&hl=en)