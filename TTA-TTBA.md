# Awesome Test-Time Instance Adaptation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome test-time instance/ batch adaptation resources. Your contributions are always welcome!

## Contents
- [Test Time Instance Adaptation](#Instance-level)
- [Test Time Batch Adaptation](#Batch-level)

## Instance-level
### Image classification
- `GeOS` [D'Innocente et al., Arxiv 2019] **Learning to generalize one sample at a time with self-supervision** [[PDF]](https://arxiv.org/abs/1910.03915) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3203292870958646989&hl=en)

- `TTT` [Sun et al., Proc. ICML 2020] **Test-time training with self-supervision for generalization under distribution shifts** [[PDF]](http://proceedings.mlr.press/v119/sun20b.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=670518589461670180&hl=en) [[CODE-1]](https://github.com/yueatsprograms/ttt_cifar_release) [[CODE-2]](https://github.com/yueatsprograms/ttt_imagenet_release)

- `PredBN` [Nado et al., Proc. ICML Workshops 2020] **Evaluating prediction-time batch normalization for robustness under covariate shift** [[PDF]](https://arxiv.org/abs/2006.10963) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14977393793616273583&hl=en)

- `PredBN+` [Schneider et al., Proc. NeurIPS 2020] **Improving robustness against common corruptions by covariate shift adaptation** [[PDF]](https://proceedings.neurips.cc/paper/2020/hash/85690f81aadc1749175c187784afc9ee-Abstract.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3624568905947100464&hl=en) [[CODE]](https://github.com/bethgelab/robustness)

- `DSON` [Seo et al., Proc. ECCV 2020] **Learning to optimize domain specific normalization for domain generalization** [[PDF]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670069.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14663179004963922658&hl=en)

- `SSDN-TTT` [Cohen et al., Arxiv 2020] **Self-supervised dynamic networks for covariate shift robustness** [[PDF]](https://arxiv.org/abs/2006.03952) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15130495263371965518&hl=en)

- `CNGRAD` [Alet et al., Proc. NeurIPS 2021] **Tailoring: Encoding inductive biases by optimizing unsupervised objectives at prediction time** [[PDF]](https://openreview.net/forum?id=8pOPKfibVN) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7588760173472055006&hl=en) [[CODE--]](https://www.lis.csail.mit.edu/tailoring)

- `ITTP` [Pandey et al., Proc. CVPR 2021] **Generalization on unseen domains via inference-time label-preserving target projections** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Pandey_Generalization_on_Unseen_Domains_via_Inference-Time_Label-Preserving_Target_Projections_CVPR_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4237814808212148329&hl=en) [[CODE]](https://github.com/yys-Polaris/InferenceTimeDG)

- `AugBN` [Khurana et al., Arxiv 2021] **SITA: Single image test-time adaptation** [[PDF]](https://arxiv.org/abs/2112.02355) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14130758976638079758&hl=en)

- `SSGen` [Xiao et al., Proc. ICLR 2022] **Learning to generalize across domains on single test samples** [[PDF]](https://arxiv.org/abs/2202.08045) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10799367073706985191&hl=en) [[CODE]](https://github.com/zzzx1224/SingleSampleGeneralization-ICLR2022)

- `MEMO` [Zhang et al., Proc. NeurIPS 2022] **MEMO: Test time robustness via adaptation and augmentation** [[PDF]](https://openreview.net/forum?id=XrGEkCOREX2) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1448618539109048791&hl=en) [[CODE]](https://github.com/zhangmarvin/memo)

- `TTT-MAE` [Gandelsman et al., Proc. NeurIPS 2022] **Test-time training with masked autoencoders** [[PDF]](https://openreview.net/forum?id=SHMi1b7sjXk) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2544097260576053446&hl=en) [[CODE]](https://github.com/yossigandelsman/test_time_training_mae)

- `DDG` [Sun et al., Proc. IJCAI 2022] **Dynamic domain generalization** [[PDF]](https://arxiv.org/abs/2205.13913) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4234489258058037285&hl=en) [[CODE]](https://github.com/MetaVisionLab/DDG)

- `TAF-Cal` [Zhao et al., Proc. IJCAI 2022] **Test-time fourier style calibration for domain generalization** [[PDF]](https://arxiv.org/abs/2205.06427) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15047408040728759993&hl=en) [[CODE--]](https://github.com/xingchenzhao/TAF-Cal)

- `TTCP++` [Sarkar et al., Proc. WACV 2022] **Leveraging test-time consensus prediction for robustness against unseen noise** [[PDF]](https://openaccess.thecvf.com/content/WACV2022/html/Sarkar_Leveraging_Test-Time_Consensus_Prediction_for_Robustness_Against_Unseen_Noise_WACV_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3457983965127110405&hl=en)

- `MT3` [Bartler et al., Proc. AISTATS 2022] **MT3: Meta test-time training for self-supervised test-time adaption** [[PDF]](https://proceedings.mlr.press/v151/bartler22a.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12491470083550671341&hl=en) [[CODE]](https://github.com/AlexanderBartler/MT3)

- `TTAPS` [Bartler et al., Proc. IJCNN 2022] **TTAPS: Test-time adaption by aligning prototypes using self-supervision** [[PDF]](https://arxiv.org/abs/2205.08731) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2871857874504831163&hl=en) [[CODE]](https://github.com/AlexanderBartler/TTAPS)

- `DoPrompt` [Zheng et al., Arxiv 2022] **Prompt vision transformer for domain generalization** [[PDF]](https://arxiv.org/abs/2208.08914) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12229109798487228669&hl=en) [[CODE]](https://github.com/zhengzangw/DoPrompt)

- `DCN` [Jiang et al., Proc. ECCV Workshops 2022] **Domain-Conditioned normalization for test-time domain generalization** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-25085-9_17#chapter-info) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15238737988084445775&hl=en)

- `BNE` [Segu et al., Pattern Recognition 2022] **Batch normalization embeddings for deep domain generalization** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0031320322005957) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1822183098800604393&hl=en)

- `GDU` [Föll et al., Arxiv 2022] **Gated domain units for multi-source domain generalization** [[PDF]](https://arxiv.org/abs/2206.12444) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18003235731039545119&hl=en) [[CODE]](https://github.com/im-ethz/pub-gdu4dg)

- `TTN` [Lim et al., Proc. ICLR 2023] **TTN: A domain-shift aware batch normalization in test-time adaptation** [[PDF]](https://openreview.net/forum?id=EQfeudmWLQ) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12984514498411836030&hl=en)

- `ESA` [Xiao et al., Proc. ICLR 2023] **Energy-based test sample adaptation for domain generalization** [[PDF]](https://openreview.net/forum?id=3dnrKbeVatv) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3027943185987486652&hl=en)

- `DDA` [Gao et al., Proc. CVPR 2023] **Back to the source: Diffusion-driven adaptation to test-time corruption** [[PDF]](https://arxiv.org/abs/2207.03442) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8145404192355562400&hl=en) [[CODE]](https://github.com/shiyegao/DDA)
  ~~[Gao et al., Proc. Workshops 2023] **Back to the source: Diffusion-driven test-time adaptation** [[PDF]](https://arxiv.org/abs/2207.03442) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8145404192355562400&hl=en) [[CODE]](https://github.com/shiyegao/DDA)~~

- `TSB` [Park et al., Proc. ICML 2023] **Test-time style shifting: Handling arbitrary styles in domain generalization** [[PDF]](https://arxiv.org/abs/2306.04911) [[G-Scholar--]]()
  ~~[Park et al., Proc. ICML Workshops 2022] **Style balancing and test-time style shifting for domain generalization** [[PDF]](https://openreview.net/forum?id=7_3oRsaogr) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17482138953832830259&hl=en)~~

- `...` [Feng et al., Proc. ICASSP 2023] **Test-time training-free domain adaptation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10096430/) [[G-Scholar--]]()

- `TT-NSS` [Mehra et al., Proc. ICML Workshops 2023] **Risk-averse predictions on unseen domains via neural style smoothing** [[PDF]](https://openreview.net/forum?id=YVwW5yBISo) [[G-Scholar--]]()

- `...` [Taesiri et al., Arxiv 2023] **Zoom is what you need: An empirical study of the power of zoom and spatial biases in image classification** [[PDF]](https://arxiv.org/abs/2304.05538) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15555449545168821035&hl=en)

- `DRM` [Zhang et al., Misc 2023] **Domain-specific risk minimization for out-of-distribution generalization** [[PDF]](https://openreview.net/forum?id=vCVTZYFcmCm) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15694323213451390034&hl=en)

### Segmentation
- `DIEM` [Wang et al., Arxiv 2019] **Dynamic scale inference by entropy minimization** [[PDF]](https://arxiv.org/abs/1908.03182) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11939087491312325887&hl=en)

- `SDA-Net` [He et al., Proc. MICCAI 2020] **Self domain adapted network** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-030-59710-8_43) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12719162110862116889&hl=en) [[CODE]](https://github.com/YufanHe/self-domain-adapted-network)

- `TTA-DAE` [Karani et al., Medical Image Analysis 2021] **Test-time adaptable neural networks for robust medical image segmentation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1361841520302711) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2632312078020561304&hl=en) [[CODE]](https://github.com/neerakara/test-time-adaptable-neural-networks-for-domain-generalization)

- `TTA-AE` [He et al., Medical Image Analysis 2021] **Autoencoder based self-supervised test-time adaptation for medical image analysis** [[PDF]](https://www.sciencedirect.com/science/article/pii/S1361841521001821) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15615377724531071348&hl=en) [[CODE]](https://github.com/YufanHe/self-domain-adapted-network)

- `OST` [Termöhlen, et al., Proc. ITSC 2021] **Continual unsupervised domain adaptation for semantic segmentation by online frequency domain style transfer** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9564566/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14006547918247195683&hl=en)

- `CBNA` [Klingner et al., IEEE TITS 2022] **Continual batchnorm adaptation (CBNA) for semantic segmentation** [[PDF]](https://arxiv.org/abs/2203.01074) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5694873096901715648&hl=en) [[CODE]](https://github.com/ifnspaml/CBNA)

- `PSR` [Li et al., Proc. MICCAI Workshops 2022] **Plug-and-play shape refinement framework for multi-site and lifespan brain skull stripping** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-21014-3_9) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2432667356722388433&hl=en)

- `TTA-FoE` [Karani et al., Arxiv 2022] **A field of experts prior for adapting neural networks at test time** [[PDF]](https://arxiv.org/abs/2202.05271) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11048304683105308159&hl=en)

- `AdvTTT` [Valvano et al., Journal of Machine Learning for Biomedical Imaging 2022] **Re-using adversarial mask discriminators for test-time training under distribution shifts** [[PDF]](https://arxiv.org/abs/2108.11926) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8356965890664373190&hl=en) [[CODE]](https://github.com/gvalvano/adversarial-test-time-training)
  ~~[Valvano et al., Proc. MICCAI Workshops 2021] **Stop throwing away discriminators! Re-using adversaries for test-time training** [[PDF]](https://arxiv.org/abs/2108.12280) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15163581574152833546&hl=en)~~

- `DCAC` [Hu et al., IEEE TMI 2022] **Domain and content adaptive convolution based multi-source domain generalization in medical image segmentation** [[PDF]](https://arxiv.org/abs/2109.05676) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7895018487155935722&hl=en) [[CODE]](https://github.com/ShishuaiHu/DCAC/)

- `InstCal` [Zou et al., Proc. ECCV 2022] **Learning instance-specific adaptation for cross-domain segmentation** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-19827-4_27) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3479758947644774894&hl=en) [[CODE]](https://github.com/Yuliang-Zou/InstCal-Pano)

- `TTO-AE` [Li et al., Proc. MICCAI Workshops 2022] **Self-supervised test-time adaptation for medical image segmentation** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-17899-3_4) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3683863853167815626&hl=en) [[CODE--]](https://github.com/HaoLi12345/TTA)

- `TASD` [Liu et al., Proc. AAAI 2022] **Single-domain generalization in medical image segmentation via test-time adaptation from shape dictionary** [[PDF]](https://arxiv.org/abs/2206.14467) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5193566977778450536&hl=en)

- `MALL` [Reddy et al., Proc. ECCV 2022] **Master of all: Simultaneous generalization of urban-scene segmentation to all adverse weather conditions** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136990051.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16396707704713565964&hl=en)

- `SaN` [Bahmani et al., Proc. ECCV Workshops 2022] **Semantic self-adaptation: Enhancing generalization with a single sample** [[PDF]](https://arxiv.org/abs/2208.05788) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2543684660991769866&hl=en) [[CODE]](https://github.com/visinf/self-adaptive)

- `SR-TTT` [Lyu et al., IEEE TMI 2022] **Learning from synthetic CT images via test-time training for liver tumor segmentation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9754550/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13052647575651297623&hl=en) [[CODE]](https://github.com/FeiLyu/SR-TTT)

- `Slot-TTA` [Prabhudesai et al., Proc. ICML 2023] **Test-time adaptation with slot-centric models** [[PDF]](https://openreview.net/forum?id=b8F8xz6_DuX) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14308566097544119245&hl=en) [[CODE]](https://github.com/mihirp1998/Slot-TTA)
  ~~[Prabhudesai et al., Proc. NeurIPS Workshops 2022] **Test-time adaptation with slot-centric models** [[PDF]](https://openreview.net/forum?id=b8F8xz6_DuX) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14308566097544119245&hl=en)~~

- `DIGA` [Wang et al., Proc. CVPR 2023] **Dynamically instance-guided adaptation: A backward-free approach for test-time domain adaptive semantic segmentation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Dynamically_Instance-Guided_Adaptation_A_Backward-Free_Approach_for_Test-Time_Domain_Adaptive_CVPR_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5310249894401773826&hl=en) [[CODE]](https://github.com/Waybaba/DIGA)

- `Adaptive-UNet` [Valanarasu et al., Proc. MIDL 2023] **On-the-fly test-time adaptation for medical image segmentation** [[PDF]](https://arxiv.org/abs/2203.05574) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2402009671021470527&hl=en) [[CODE]](https://github.com/jeya-maria-jose/On-The-Fly-Adaptation)

- `WOSA-AugSelf` [Huang et al., Computer Methods and Programs in Biomedicine 2023] **Test-time bi-directional adaptation between image and model for robust segmentation** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0169260723001438) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14768083414195901454&hl=en)

- `AdaAtlas` [Guo et al., Arxiv 2023] **Pay attention to the atlas: Atlas-guided test-time adaptation method for robust 3D medical image segmentation** [[PDF]](https://arxiv.org/abs/2307.00676) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3681859989801585957&hl=en)

- `TTA-SEG` [Janouskova., Master Thesis 2023] **Test-time adaptation for segmentation** [[PDF]]() [[G-Scholar--]]() [[CODE]](https://github.com/klarajanouskova/TTA-SEG)

### Detection
- `OSHOT` [D'Innocente et al., Proc. ECCV 2020] **One-shot unsupervised cross-domain detection** [[PDF]](https://link.springer.com/chapter/10.1007/978-3-030-58517-4_43) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7600955351500947376&hl=en) [[CODE]](https://github.com/VeloDC/oshot_detection)

- `Full-OSHOT` [Borlino et al., Computer Vision and Image Understanding 2022] **Self-supervision & meta-learning for one-shot unsupervised cross-domain detection** [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S1077314222001278) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4649311116991136777&hl=en) [[CODE]](https://github.com/FrancescoCappio/OSHOT-meta-learning)

- `...` [Veksler., Proc. CVPR 2023] **Test time adaptation with regularized loss for weakly supervised salient object detection** [[PDF]](http://openaccess.thecvf.com/content/CVPR2023/html/Veksler_Test_Time_Adaptation_With_Regularized_Loss_for_Weakly_Supervised_Salient_CVPR_2023_paper.html) [[G-Scholar--]]()

### Defense
- `SOAP` [Shi et al., Proc. ICLR 2021] **Online adversarial purification based on self-supervision** [[PDF]](https://openreview.net/forum?id=_i3ASPp12WS) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17641828899893011240&hl=en) [[CODE]](https://github.com/Mishne-Lab/SOAP)

- `ADP` [Yoon et al., Proc. ICML 2021] **Adversarial purification with score-based generative models** [[PDF]](http://proceedings.mlr.press/v139/yoon21a.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1510322463041774819&hl=en) [[CODE]](https://github.com/jmyoon1/adp)

- `SSRA` [Mao et al., Proc. ICCV 2021] **Adversarial attacks are reversible with natural supervision** [[PDF]](http://openaccess.thecvf.com/content/ICCV2021/html/Mao_Adversarial_Attacks_Are_Reversible_With_Natural_Supervision_ICCV_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13382217456224684062&hl=en) [[CODE]](https://github.com/cvlab-columbia/SelfSupDefense)

- `Hedge` [Wu et al., Arxiv 2021] **Attacking adversarial attacks as a defense** [[PDF]](https://arxiv.org/abs/2106.04938) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13139092335359588465&hl=en)

- `Anti-Adv` [Alfarra et al., Proc. AAAI 2022] **Combating adversaries with anti-adversaries** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/20545) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15633095022559915646&hl=en) [[CODE]](https://github.com/MotasemAlfarra/Combating-Adversaries-with-Anti-Adversaries)

- `Equ-Defense` [Mao et al., Arxiv 2022] **Robust perception through equivariance** [[PDF]](https://arxiv.org/abs/2212.06079) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6052114939161464594&hl=en)

- `Mask-Defense` [McDermott et al., Proc. ICLR Workshops 2023] **Robustifying language models with test-time adaptation** [[PDF]](https://openreview.net/forum?id=MOe6swbU2Ab) [[G-Scholar--]]()

- `DRAM` [Tsai et al., Arxiv 2023] **Test-time defense against adversarial attacks: Detection and reconstruction of adversarial examples via masked autoencoder** [[PDF]](https://arxiv.org/abs/2303.12848) [[G-Scholar--]]() 
  ~~[Tsai et al., Proc. CVPR Workshops 2023] **Test-time detection and repair of adversarial samples via masked autoencoder** [[PDF]](https://robustart.github.io/long_paper/22.pdf) [[G-Scholar--]]()~~

- `TETRA` [Blau et al., Arxiv 2023] **Classifier robustness enhancement Via test-time transformation** [[PDF]](https://arxiv.org/abs/2303.15409) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10076827701044004595&hl=en)

- `ZIP` [Shi et al., Arxiv 2023] **Black-box backdoor defense via zero-shot image purification** [[PDF]](https://arxiv.org/abs/2303.12175) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10966958864337456240&hl=en)

- `BDMAE` [Sun et al., Arxiv 2023] **Mask and restore: Blind backdoor defense at test time with masked autoencoder** [[PDF]](https://arxiv.org/abs/2303.15564) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12419213242412958636&hl=en)

- `RFI` [Singh et al., Arxiv 2023] **Fast adaptive test-time defense with robust features** [[PDF]](https://arxiv.org/abs/2307.11672) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14379984320874878216&hl=en)

- `MAT` [Huang et al., Misc 2023] **Test-time adaptation for better adversarial robustness** [[PDF]](https://openreview.net/forum?id=rUxKM6u8WER) [[G-Scholar--]]()

### Pose estimation
- `ISO` [Zhang et al., Proc. NeurIPS 2020] **Inference stage optimization for cross-scenario 3d human pose estimation** [[PDF]](https://proceedings.neurips.cc/paper/2020/hash/1943102704f8f8f3302c2b730728e023-Abstract.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1453780569346725768&hl=en)

- `SCIO` [Kan et al., Proc. ECCV 2022] **Self-constrained inference optimization on structural groups for human pose estimation** [[PDF]](https://arxiv.org/abs/2207.02425) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15020898979543983018&hl=en)

- `ZPT` [Wang et al., Proc. ECCV 2022] **Zero-shot pose transfer for unrigged stylized 3D characters** [[PDF]](http://openaccess.thecvf.com/content/CVPR2023/html/Wang_Zero-Shot_Pose_Transfer_for_Unrigged_Stylized_3D_Characters_CVPR_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8806852905737296920&hl=en)

- `...` [Azarian et al., Proc. WACV Workshops 2023] **Test-time adaptation vs. training-time generalization: A case study in human instance segmentation using keypoints estimation** [[PDF]](https://openaccess.thecvf.com/content/WACV2023W/DNOW/html/Azarian_Test-Time_Adaptation_vs._Training-Time_Generalization_A_Case_Study_in_Human_WACVW_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7504295780791163610&hl=en)

- `...` [Chen et al., IEEE TMM 2023] **Multi-person 3D pose esitmation with occlusion reasoning** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10117604/) [[G-Scholar--]]()

### Retrieval 
- `Sketch3T` [Sain et al., Proc. CVPR 2022] **Sketch3t: Test-time training for zero-shot SBIR** [[PDF]](http://openaccess.thecvf.com/content/CVPR2022/html/Sain_Sketch3T_Test-Time_Training_for_Zero-Shot_SBIR_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3412435374622527568&hl=en)

- `TTT-UCDR` [Paul et al., Arxiv 2022] **TTT-UCDR: Test-time training for universal cross-domain retrieval** [[PDF]](https://arxiv.org/abs/2208.09198) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6906804282191188125&hl=en) [[CODE]](https://github.com/mvp18/TTT-UCDR)

- `META` [Xu et al., Proc. ECCV 2022] **Mimic embedding via adaptive aggregation: Learning generalizable person re-identification** [[PDF]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136740362.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8699042944012178592&hl=en) [[CODE]](https://github.com/xbq1994/META)

### Low-level vision
- `ZSSR` [Shocher et al., Proc. CVPR 2018] **"zero-shot" super-resolution using deep internal learning** [[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/html/Shocher_Zero-Shot_Super-Resolution_Using_CVPR_2018_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8866449317373150101&hl=en) [[CODE]](https://github.com/assafshocher/ZSSR)

- `MLSR` [Park et al., Proc. ECCV 2020] **Fast adaptation to super-resolution networks via meta-learning** [[PDF]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720749.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2341211698472321158&hl=en) [[CODE]](https://github.com/parkseobin/MLSR)

- `MZSR` [Soh et al., Proc. CVPR 2020] **Meta-transfer learning for zero-shot super-resolution** [[PDF]](https://openaccess.thecvf.com/content_CVPR_2020/html/Soh_Meta-Transfer_Learning_for_Zero-Shot_Super-Resolution_CVPR_2020_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4901353720515503142&hl=en) [[CODE]](https://github.com/JWSoh/MZSR)

- `LIDIA` [Vaksman et al., Proc. CVPR Workshops 2020] **Lidia: Lightweight learned image denoising with instance adaptation** [[PDF]](https://openaccess.thecvf.com/content_CVPRW_2020/html/w31/Vaksman_LIDIA_Lightweight_Learned_Image_Denoising_With_Instance_Adaptation_CVPRW_2020_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8763212900791323920&hl=en) [[CODE]](https://github.com/grishavak/LIDIA-denoiser)

- `SURE-FT` [Soltanayev and Chun, Arxiv 2021] **Training deep learning based denoisers without ground truth data** [[PDF]](https://proceedings.neurips.cc/paper/2018/hash/c0560792e4a3c79e62f76cbf9fb277dd-Abstract.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10949844547317882495&hl=en) [[CODE]](https://github.com/Shakarim94/Net-SURE)

- `Gaintuning` [Mohan et al., Proc. NeurIPS 2021] **Adaptive denoising via gaintuning** [[PDF]](https://openreview.net/forum?id=0BHU7WvZ29) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7653306197808807036&hl=en) [[CODE--]](https://github.com/sreyas-mohan/gaintuning)

- `MetaAT` [Chi et al., Proc. CVPR 2021] **Test-time fast adaptation for dynamic scene deblurring via meta-auxiliary learning** [[PDF]](http://openaccess.thecvf.com/content/CVPR2021/html/Chi_Test-Time_Fast_Adaptation_for_Dynamic_Scene_Deblurring_via_Meta-Auxiliary_Learning_CVPR_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11696149511628418844&hl=en)

- `...` [Liu et al., Proc. CVPR 2022] **Towards multi-domain single image dehazing via test-time training** [[PDF]](http://openaccess.thecvf.com/content/CVPR2022/html/Liu_Towards_Multi-Domain_Single_Image_Dehazing_via_Test-Time_Training_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16896024038546207959&hl=en)

- `MetaTL` [Gunawan et al., Arxiv 2022] **Test-time adaptation for real image denoising via meta-transfer learning** [[PDF]](https://arxiv.org/abs/2207.02066) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12620165808171507902&hl=en) [[CODE]](https://github.com/agusgun/TTAID)

- `...` [Hatem et al., Proc. IROS 2023] **Test-time adaptation for point cloud upsampling using meta-learning** [[PDF]](https://arxiv.org/abs/2308.16484) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18088448039758938963&hl=en)

### Inverse problem
- `R&R+` [Gilton et al., IEEE TCI 2021] **Model adaptation for inverse problems in imaging** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9477112/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1317665702275783452&hl=en)

- `IAGAN-BP` [Hussein et al., Proc. AAAI 2020] **Image-adaptive GAN based reconstruction** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/5708) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2031873828919537613&hl=en) [[CODE]](https://github.com/shadyabh/IAGAN)

- `...` [Darestani et al., Proc. ICML 2022] **Test-time training can close the natural distribution shift performance gap in deep learning based compressed sensing** [[PDF]](https://proceedings.mlr.press/v162/darestani22a.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17586372982715627644&hl=en) [[CODE]](https://github.com/MLI-lab/ttt_for_deep_learning_cs)

- `PINER` [Song et al., Proc. WACV 2023] **PINER: Prior-informed implicit neural representation learning for test-time adaptation in sparse-view CT reconstruction** [[PDF]](https://openaccess.thecvf.com/content/WACV2023/html/Song_PINER_Prior-Informed_Implicit_Neural_Representation_Learning_for_Test-Time_Adaptation_in_WACV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8086782344774079473&hl=en)

### Face detection
- `GPR` [Jain and Learned-Miller, Proc. CVPR 2011] **Online domain adaptation of a pre-trained cascade of classifiers** [[PDF]](https://people.cs.umass.edu/~elm/papers/cvpr11adaptive.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1871527275360315634&hl=en)

### Mapping between paired images
- `SSMSR` [Zhu et al., Proc. ICRA 2021] **Test-time training for deformable multi-scale image registration** [[PDF]](https://arxiv.org/abs/2103.13578) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6326490607378414181&hl=en)

- `...` [Baum et al., Proc. MICCAI Workshops 2022] **Meta-registration: Learning test-time optimization for single-pair image registration** [[PDF]](https://arxiv.org/abs/2207.10996) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11250524502938556610&hl=en)

- `DMP` [Hong and Kim, Proc. ICCV 2021] **Deep matching prior: Test-time optimization for dense correspondence** [[PDF]](https://openaccess.thecvf.com/content/ICCV2021/html/Hong_Deep_Matching_Prior_Test-Time_Optimization_for_Dense_Correspondence_ICCV_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7012757512151073041&hl=en) [[CODE--]](https://github.com/SunghwanHong/Deep-Matching-Prior)

- `...` [Hatem et al., Proc. ICCV 2023] **Point-TTA: Test-time adaptation for point cloud registration using multitask meta-auxiliary learning** [[PDF]](https://arxiv.org/abs/2308.16481) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3287028425275958276&hl=en)

- `...` [Min et al., Proc. WACV 2023] **Meta-learning for adaptation of deep optical flow networks** [[PDF]](https://openaccess.thecvf.com/content/WACV2023/html/Min_Meta-Learning_for_Adaptation_of_Deep_Optical_Flow_Networks_WACV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18408757945365502559&hl=en)

- `...` [Sang et al., Medical Physics 2023] **Target‐oriented deep learning‐based image registration with individualized test‐time adaptation** [[PDF]](https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.16477) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1343161448571720939&hl=en)

### Generative modeling
- `GIP` [Bau et al., ACM TOG 2019] **Semantic photo manipulation with a generative image prior** [[PDF]](https://arxiv.org/abs/2005.07727) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6750293979132878511&hl=en)

- `INR-st` [Kim et al., Arxiv 2022] **Controllable style transfer via test-time training of implicit neural representation** [[PDF]](https://arxiv.org/abs/2210.07762) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6128992105506775450&hl=en) [[CODE]](https://github.com/KU-CVLAB/INR-st)

- `SiSTA` [Subramanyam et al., Proc. ICML 2023] **Target-aware generative augmentations for single-shot adaptation** [[PDF]](https://openreview.net/forum?id=K26zQKvXiR) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15168577856501871450&hl=en) [[CODE]](https://github.com/Rakshith-2905/SiSTA)
  ~~[Subramanyam et al., Arxiv 2022] **Single-shot domain adaptation via target-aware generative augmentation** [[PDF]](https://arxiv.org/abs/2210.16692) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14023566347726420541&hl=en)~~

- `MODIFY` [Ding et al., Proc. ICASSP 2023] **MODIFY: Model-driven face stylization without style images** [[PDF]](https://arxiv.org/abs/2303.09831) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2582576045423085678&hl=en)

### Consistency
- `SSL-MOCAP` [Tung et al., Proc. NeurIPS 2017] **Self-supervised learning of motion capture** [[PDF]](https://proceedings.neurips.cc/paper/7108-self-supervised-learning-of-motion-capture) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11316472994665815439&hl=en) [[CODE]](https://github.com/htung0101/3d_smpl)

- `MetaVFI` [Choi et al., Proc. CVPR 2020] **Scene-adaptive video frame interpolation via meta-learning** [[PDF]](http://openaccess.thecvf.com/content_CVPR_2020/html/Choi_Scene-Adaptive_Video_Frame_Interpolation_via_Meta-Learning_CVPR_2020_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2749309242157904592&hl=en)

- `REFINE` [Leung et al., Proc. CVPR Workshops 2022] **Black-box test-time shape REFINEment for single view 3D reconstruction** [[PDF]](https://openaccess.thecvf.com/content/CVPR2022W/L3D-IVU/html/Leung_Black-Box_Test-Time_Shape_REFINEment_for_Single_View_3D_Reconstruction_CVPRW_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14768608972107159837&hl=en) [[CODE]](https://github.com/b7leung/REFINE)

- `MetaVFI` [Choi et al., IEEE TPAMI 2021] **Test-time adaptation for video frame interpolation via meta-learning** [[PDF]](https://ieeexplore.ieee.org/abstract/document/9625774) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4253219786252969489&hl=en)

- `VFI_Adapter` [Wu et al., Arxiv 2023] **Boost video frame interpolation via motion adaptation** [[PDF]](https://arxiv.org/abs/2306.13933) [[G-Scholar--]]() [[CODE]](https://github.com/haoningwu3639/VFI_Adapter)

### NLP 
- `TTL-EQA` [Banerjee et al., Proc. NAACL 2021] **Self-supervised test-time learning for reading comprehension** [[PDF]](https://aclanthology.org/2021.naacl-main.95/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7170102090609189822&hl=en)

- `EMEA` [Wang et al., Proc. EMNLP-Findings 2021] **Efficient test time adapter ensembling for low-resource language varieties** [[PDF]](https://arxiv.org/abs/2109.04877) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12192753397006273283&hl=en)

- `PADA` [Ben-David et al., TACL 2022] **PADA: Example-based prompt learning for on-the-fly adaptation to unseen domains** [[PDF]](https://mitp.silverchair.com/tacl/article-pdf/doi/10.1162/tacl_a_00468/2008061/tacl_a_00468.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7952516094945703287&hl=en) [[CODE]](https://github.com/eyalbd2/PADA)

- `Hyper-PADA` [Volk et al., Arxiv 2022] **Example-based hypernetworks for out-of-distribution generalization** [[PDF]](https://arxiv.org/abs/2203.14276) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14176770453923615063&hl=en) [[CODE]](https://github.com/TomerVolk/Hyper-PADA)

- `TTT-NN` [Hardt and Sun, Arxiv 2023] **Test-time training on nearest neighbors for large language models** [[PDF]](https://arxiv.org/abs/2305.18466) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13923028688883164038&hl=en) [[CODE]](https://github.com/socialfoundations/tttlm)

### Graph
- `GT3` [Wang et al., Arxiv 2022] **Test-time training for graph neural networks** [[PDF]](https://arxiv.org/abs/2210.08813) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4459392671520994454&hl=en)

- `GTRANS` [Jin et al., Proc. ICLR 2023] **Empowering graph representation learning with test-time graph transformation** [[PDF]](https://openreview.net/forum?id=Lnxl5pr018) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12479531068894109978&hl=en)

### Misc
- `PAD` [Hansen et al., Proc. ICLR 2021] **Self-supervised policy adaptation during deployment** [[PDF]](https://openreview.net/forum?id=o_V-MjyyGV_) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10107448604973336784&hl=en) [[CODE]](https://github.com/nicklashansen/policy-adaptation-during-deployment)

- `RoMA` [Yu et al., Proc. NeurIPS 2021] **RoMA: Robust model adaptation for offline model-based optimization** [[PDF]](https://openreview.net/forum?id=VH0TRmnqUc) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1579009087385407860&hl=en) [[CODE]](https://github.com/sihyun-yu/RoMA)

- `ZSDA-HTL` [Sakai, Proc. ECML-PKDD 2021] **Source hypothesis transfer for zero-shot domain adaptation** [[PDF]](https://2021.ecmlpkdd.org/wp-content/uploads/2021/07/sub_301.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17201510186080842888&hl=en)

- `VoP` [Kim et al., Proc. ICML 2022] **Variational on-the-fly personalization** [[PDF]](https://proceedings.mlr.press/v162/kim22e.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2963772835076607567&hl=en)

- `TPT` [Shu et al., Proc. NeurIPS 2022] **Test-time prompt tuning for zero-shot generalization in vision-language models** [[PDF]](https://openreview.net/forum?id=e8PVEkSa4Fq) [[G-Scholar]](https://scholar.google.com/scholar?cluster=213109028691722316&hl=en) [[CODE]](https://github.com/azshue/TPT)

- `OST` [Chen et al., Proc. NeurIPS 2022] **OST: Improving generalization of DeepFake detection via one-shot test-time training** [[PDF]](https://openreview.net/forum?id=YPoRoad6gzY) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5928389911055380884&hl=en) [[CODE]](https://github.com/liangchen527/OST)

- `...` [Özer and Müller, Proc. ISMIR 2022] **Source separation of piano concertos with test-time adaptation** [[PDF]](https://www.audiolabs-erlangen.de/content/05-fau/professor/00-mueller/03-publications/2022_OezerM_PianoSepAdapt_ISMIR_ePrint.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10343177797016236066&hl=en)

- `...` [Sang et al., International Journal of Radiation Oncology, Biology, Physics 2022] **Inference-time adaptation for improved transfer ability and generalization in deformable image registration deep learning** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0360301622016236) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10634714491331957313&hl=en)

- `DFA` [Mirza et al., Proc. ICML 2023] **Diagnosis, feedback, adaptation: A human-in-the-loop framework for test-time policy adaptation** [[PDF]](https://arxiv.org/abs/2307.06333) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4093024291231214911&hl=en)

- `PAFF` [Ge et al., Proc. CVPR 2023] **Policy adaptation from foundation model feedback** [[PDF]](https://openaccess.thecvf.com/content/WACV2023/html/Min_Meta-Learning_for_Adaptation_of_Deep_Optical_Flow_Networks_WACV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=4093024291231214911&hl=en)

- `MATE` [Mirza et al., Proc. ICCV 2023] **MATE: Masked autoencoders are online 3D test-time learners** [[PDF]](https://arxiv.org/abs/2211.11432) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17319713522651218187&hl=en) [[CODE]](https://github.com/jmiemirza/MATE)

- `DiffTPT` [Feng et al., Proc. ICCV 2023] **Test-time prompt tuning for zero-shot generalization in vision-language models** [[PDF]](https://arxiv.org/abs/2308.06038) [[G-Scholar--]]() [[CODE--]](https://github.com/chunmeifeng/DiffTPT)

- `...` [Liu et al., Proc. WACV 2023] **Meta-auxiliary learning for future depth prediction in videos** [[PDF]](https://openaccess.thecvf.com/content/WACV2023/html/Min_Meta-Learning_for_Adaptation_of_Deep_Optical_Flow_Networks_WACV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=9083144572156364990&hl=en)

- `TDS` [Wen et al., IEEE TMM 2023] **Test-time model adaptation for visual question answering with debiased self-supervisions** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10173554/) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3117843961096530913&hl=en)

- `SRR-MAML` [Huo et al., Arxiv 2023] **Learning adaptable risk-sensitive policies to coordinate in multi-agent general-sum games** [[PDF]](https://arxiv.org/abs/2304.02162) [[G-Scholar]](https://scholar.google.com/scholar?cluster=146325397292652498&hl=en)

- `ARSP` [Liu and Fang, Arxiv 2023] **Learning to recover spectral reflectance from
RGB images** [[PDF]](https://arxiv.org/abs/2303.07850) [[G-Scholar]](https://scholar.google.com/scholar?cluster=146325397292652498&hl=en)

- `RLCF` [Zhao et al., Arxiv 2023] **Test-time adaptation with CLIP reward for zero-shot generalization in vision-language models** [[PDF]](https://arxiv.org/abs/2305.18010) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13354273242354297247&hl=en) [[CODE--]]()

- `DROP` [Liu et al., Arxiv 2023] **Design from policies: Conservative test-time adaptation for offline policy optimization** [[PDF]](https://arxiv.org/abs/2306.14479) [[G-Scholar--]]()

- `MoVie` [Yang et al., Arxiv 2023] **MoVie: Visual model-based policy adaptation for view generalization** [[PDF]](https://arxiv.org/abs/2307.00972) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8702194818732254776&hl=en) [[CODE]](https://github.com/yangsizhe/MoVie)

- `...` [Dumpala et al., Arxiv 2023] **Test-time training for speech** [[PDF]](https://arxiv.org/abs/2309.10930) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1240093156897083970&hl=en)

## Batch-level
### Classification
- `ARM` [Zhang et al., Proc. NeurIPS 2021] **Adaptive risk minimization: Learning to adapt to domain shift** [[PDF]](https://openreview.net/forum?id=-zgb2v8vV_w) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6509702681777063562&hl=en) [[CODE]](https://github.com/henrikmarklund/arm)

- `DA-ERM` [Dubey et al., Proc. CVPR 2021] **Adaptive methods for real-world domain generalization** [[PDF]](https://openaccess.thecvf.com/content/CVPR2021/html/Dubey_Adaptive_Methods_for_Real-World_Domain_Generalization_CVPR_2021_paper.html?ref=https://githubhelp.com) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5099951170799095029&hl=en) [[CODE]](https://github.com/abhimanyudubey/PrototypicalDomainGeneralization)

- `...` [Benz et al., Proc. WACV 2021] **Revisiting batch normalization for improving corruption robustness** [[PDF]](http://openaccess.thecvf.com/content/WACV2021/html/Benz_Revisiting_Batch_Normalization_for_Improving_Corruption_Robustness_WACV_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3152355758391484923&hl=en) [[CODE]](https://github.com/phibenz/batch_norm_adaptation.pytorch)

- `...` [Nandy et al., Proc. ICLR Workshops 2021] **Covariate shift adaptation for adversarially robust classifier** [[PDF]](https://aisecure-workshop.github.io/aml-iclr2021/papers/2.pdf) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11626818507596612411&hl=en)

- `Meta-DMoE` [Zhong et al., Proc. NeurIPS 2022] **Meta-DMoE: Adapting to domain shift by meta-distillation from mixture-of-experts** [[PDF]](https://openreview.net/forum?id=_ekGcr07Dsp) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18362067030660551332&hl=en) [[CODE]](https://github.com/n3il666/Meta-DMoE)

- `LAME` [Boudiaf et al., Proc. CVPR 2022] **Parameter-free online test-time adaptation** [[PDF]](http://openaccess.thecvf.com/content/CVPR2022/html/Boudiaf_Parameter-Free_Online_Test-Time_Adaptation_CVPR_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2855726690492926827&hl=en) [[CODE]](https://github.com/fiveai/LAME)

- `TTAwPCA` [Cordier et al., Proc. ECML/PKDD Workshops 2022] **Test-time adaptation with principal component analysis** [[PDF]](https://arxiv.org/abs/2209.05779) [[G-Scholar]](https://scholar.google.com/scholar?cluster=684086728189075944&hl=en)

- `L2GP` [Duboudin et al., Arxiv 2022] **Learning less generalizable patterns with an asymmetrically trained double classifier for better test-time adaptation** [[PDF]](https://arxiv.org/abs/2210.09834) [[G-Scholar]](https://scholar.google.com/scholar?cluster=1844003267836965379&hl=en)

- `TTTFlow` [Osowiechi et al., Proc. WACV 2023] **TTTFlow: Unsupervised test-time training with normalizing flow** [[PDF]](https://openaccess.thecvf.com/content/WACV2023/html/Osowiechi_TTTFlow_Unsupervised_Test-Time_Training_With_Normalizing_Flow_WACV_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15158703704163101963&hl=en) [[CODE]](https://github.com/GustavoVargasHakim/TTTFlow)

- `ShiftMatch` [Wang and Aitchison, Proc. ICLR 2023] **Robustness to corruption in pre-trained Bayesian neural networks** [[PDF]](https://openreview.net/forum?id=kUI41mY8bHl) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12854599053728566431&hl=en)

- `DomainAdaptor` [Zhang et al., Proc. ICCV 2023] **DomainAdaptor: A novel approach to test-time adaptation** [[PDF]](https://arxiv.org/abs/2308.10297) [[G-Scholar--]]() [[CODE--]](https://github.com/koncle/DomainAdaptor)

- `DILAM` [Leitner et al., Proc. IEEE Intelligent Vehciles Symposium 2023] **Sit back and relax: Learning to drive incrementally in all weather conditions** [[PDF]](https://arxiv.org/abs/2305.18953) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8435946811898296972&hl=en) [[CODE]](https://github.com/jmiemirza/DILAM)

- `CVP` [Tsai et al., Arxiv 2023] **Self-supervised convolutional visual prompts** [[PDF]](https://arxiv.org/abs/2303.00198) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10433190878679136798&hl=en)

- `ContextViT` [Bao and Karaletsos, Arxiv 2023] **Contextual vision transformers for robust representation learning** [[PDF]](https://arxiv.org/abs/2305.19402) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12070186471925200805&hl=en)

### Video processing (multiple frames)
- `PGO` [Brahmbhatt et al., Proc. CVPR 2018] **Geometry-aware learning of maps for camera localization** [[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/html/Brahmbhatt_Geometry-Aware_Learning_of_CVPR_2018_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=15361942550307476955&hl=en) [[CODE]](https://github.com/NVlabs/geomapnet)

- `Struct2depth` [Casser et al., Proc. AAAI 2019] **Depth prediction without the sensors: Leveraging structure for unsupervised learning from monocular videos** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/4801) [[G-Scholar]](https://scholar.google.com/scholar?cluster=6085012098967393966&hl=en) [[CODE]](https://github.com/tensorflow/models/tree/archive/research/struct2depth)

- `GLNet` [Chen et al., Proc. ICCV 2019] **Self-supervised learning with geometric constraints in monocular video: Connecting flow, depth, and camera** [[PDF]](http://openaccess.thecvf.com/content_ICCV_2019/html/Chen_Self-Supervised_Learning_With_Geometric_Constraints_in_Monocular_Video_Connecting_Flow_ICCV_2019_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=10432443504968714818&hl=en)

- `ACMR-vid` [Li et al., Proc. NeurIPS 2020] **Online adaptation for consistent mesh reconstruction in the wild** [[PDF]](https://proceedings.neurips.cc/paper/2020/hash/aba3b6fd5d186d28e06ff97135cade7f-Abstract.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5047130699502440342&hl=en)

- `CVD` [Luo et al., ACM TOG 2020] **Consistent video depth estimation** [[PDF]](https://arxiv.org/abs/2004.15021) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16267050670902151763&hl=en) [[CODE]](https://github.com/facebookresearch/consistent_depth)

- `Deep3D` [Lee et al., Proc. CVPR 2021] **3D video stabilization with depth estimation by CNN-based optimization** [[PDF]](http://openaccess.thecvf.com/content/CVPR2021/html/Lee_3D_Video_Stabilization_With_Depth_Estimation_by_CNN-Based_Optimization_CVPR_2021_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13595361912865724842&hl=en)

- `GCVD` [Lee et al., Arxiv 2022] **Globally consistent video depth and pose estimation with efficient test-time training** [[PDF]](https://arxiv.org/abs/2208.02709) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7306691990551013000&hl=en) [[CODE]](https://github.com/yaochih/GCVD-release)

- `...` [Azimi et al., Proc. WACV 2022] **Self-supervised test-time adaptation on video data** [[PDF]](https://openaccess.thecvf.com/content/WACV2022/html/Azimi_Self-Supervised_Test-Time_Adaptation_on_Video_Data_WACV_2022_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=11449570492704365767&hl=en)

- `...` [Yeh et al., Proc. CVPR 2023] **Meta-personalizing vision-language models to find named instances in video** [[PDF]](http://openaccess.thecvf.com/content/CVPR2023/html/Yeh_Meta-Personalizing_Vision-Language_Models_To_Find_Named_Instances_in_Video_CVPR_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5736801019110688089&hl=en)

- `CycleAdapt` [Nam et al., Proc. ICCV 2023] **Cyclic test-time adaptation on monocular video
for 3D human mesh reconstruction** [[PDF]](https://arxiv.org/abs/2308.06554) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5480263647326292275&hl=en) [[CODE]](https://github.com/hygenie1228/CycleAdapt_RELEASE)

- `...` [Mutlu et al., Arxiv 2023] **TempT: Temporal consistency for test-time adaptation** [[PDF]](https://arxiv.org/abs/2303.10536) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13961877707627428919&hl=en)

- `Meta-VPL` [Ambekar et al., Arxiv 2023] **Learning variational neighbor labels for test-time domain generalization** [[PDF]](https://arxiv.org/abs/2307.04033) [[G-Scholar]](https://scholar.google.com/scholar?cluster=17881603264637544125&hl=en)

### Misc
- `TTP` [Li et al., Proc. NeurIPS 2021] **Test-time personalization with a transformer for human pose estimation** [[PDF]](https://openreview.net/forum?id=cwSkaedP-wz) [[G-Scholar]](https://scholar.google.com/scholar?cluster=8881142280914530303&hl=en) [[CODE]](https://github.com/harry11162/TTP)

- `BNTA` [Han et al., Proc. AAAI 2022] **Generalizable person re-identification via self-supervised batch norm test-time adaption** [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/19963) [[G-Scholar]](https://scholar.google.com/scholar?cluster=2418291620221336553&hl=en)

- `TTAS` [Bateson et al., Proc. MICCAI 2022] **Test-time adaptation with shape moments for image segmentation** [[PDF]](https://arxiv.org/abs/2205.07983) [[G-Scholar]](https://scholar.google.com/scholar?cluster=18007426859983116683&hl=en) [[CODE]](https://github.com/mathilde-b/TTA)

- `SUTA` [Lin et al., Proc. Interspeech 2022] **Listen, adapt, better WER: Source-free single-utterance test-time adaptation for automatic speech recognition** [[PDF]](https://arxiv.org/abs/2203.14222) [[G-Scholar]](https://scholar.google.com/scholar?cluster=7797707155623619852&hl=en) [[CODE]](https://github.com/DanielLin94144/Test-time-adaptation-ASR-SUTA)

- `...` [Cui et al., Proc. AAAI2023] **Meta-auxiliary learning for adaptive human pose prediction** [[PDF]](https://arxiv.org/abs/2304.06411) [[G-Scholar--]]()

- `...` [Cui et al., Proc. ICCV 2023] **Test-time personalizable forecasting of 3D human poses** [[PDF--]]() [[G-Scholar--]]()

- `MyStyle` [Nitzan et al., ACM TOG 2022] **MyStyle: A personalized generative prior** [[PDF]](https://arxiv.org/abs/2203.17272) [[G-Scholar]](https://scholar.google.com/scholar?cluster=5043776863260191811&hl=en) [[CODE]](https://github.com/google/mystyle)

- `MetaSSN` [Kim et al., Expert Systems with Applications 2022] **Style selective normalization with meta learning for test-time adaptive face anti-spoofing** [[PDF]](https://www.sciencedirect.com/science/article/pii/S0957417422021248) [[G-Scholar]](https://scholar.google.com/scholar?cluster=16916146254562612393&hl=en)

- `LSTM` [Benmalek et al., Misc 2022] **Learning to adapt to semantic shift** [[PDF]](https://openreview.net/forum?id=ZFWwI5ahxud) [[G-Scholar--]]()

- `DIA` [Wu et al., Proc. ICML 2023] **Uncovering adversarial risks of test-time adaptation** [[PDF]](https://arxiv.org/abs/2301.12576) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13284981397235504725&hl=en)

- `SCIA` [Kan et al., Proc. CVPR 2023] **Self-correctable and adaptable inference for generalizable human pose estimation** [[PDF]](https://openaccess.thecvf.com/content/CVPR2023/html/Kan_Self-Correctable_and_Adaptable_Inference_for_Generalizable_Human_Pose_Estimation_CVPR_2023_paper.html) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13052005330920059778&hl=en)

- `TTA-IQA` [Roy et al., Proc. ICCV 2023] **Test time adaptation for blind image quality assessment** [[PDF]](https://arxiv.org/abs/2307.14735) [[G-Scholar]](https://scholar.google.com/scholar?cluster=12191992079677417512&hl=en) [[CODE--]](https://github.com/Shankhanil006/TTA-IQA)

- `...` [Cui et al., Proc. AAAI 2023] **Meta-auxiliary learning for adaptive human pose prediction** [[PDF]](https://arxiv.org/abs/2304.06411) [[G-Scholar]](https://scholar.google.com/scholar?cluster=14630011385813471433&hl=en)

- `...` [Yi and Kim, Proc. ICRA 2023] **Test-time synthetic-to-real adaptive depth estimation** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10160773/) [[G-Scholar--]]()

- `LD-BN-ADAPT` [Bhardwaj et al., Proc. DATE 2023] **Real-time fully unsupervised domain adaptation for lane detection in autonomous driving** [[PDF]](https://ieeexplore.ieee.org/abstract/document/10136937/) [[G-Scholar--]]()

- `SGEM` [Kim et al., Proc. Interspeech 2023] **SGEM: Test-time adaptation for automatic speech recognition via sequential-level generalized entropy minimization** [[PDF]](https://arxiv.org/abs/2306.01981) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13829873231059396752&hl=en) [[CODE]](https://github.com/drumpt/SGEM)

- `TTS` [Bissoto et al., Proc. MICCAI Workshops 2023] **Test-time selection for robust skin lesion analysis** [[PDF]](https://arxiv.org/abs/2308.05595) [[G-Scholar]](https://scholar.google.com/scholar?cluster=3545620692718587238&hl=en)

- `...` [Mehra et al., Arxiv 2023] **On the fly neural style smoothing for risk-averse domain generalization** [[PDF]](https://arxiv.org/abs/2307.08551) [[G-Scholar]](https://scholar.google.com/scholar?cluster=13314865066099160761&hl=en)

- `...` [Tula et al., Arxiv 2023] **Is it an i or an l: Test-time adaptation of text line recognition models** [[PDF]](https://arxiv.org/abs/2308.15037) [[G-Scholar--]]()