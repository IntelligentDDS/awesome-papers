# Fault Tolerance

**Content**

- [Fault Tolerance](#fault-tolerance)
  - [Cloud System](#cloud-system)
    - [Failure Analysis](#failure-analysis)
    - [Fault Injection](#fault-injection)
    - [Fault Recovery](#fault-recovery)
  - [AI System](#ai-system)
    - [Failure Analysis](#failure-analysis-1)
      - [Mixed layer](#mixed-layer)
      - [Service](#service)
      - [Model](#model)
      - [Framework](#framework)
      - [Tooolkits](#tooolkits)
      - [Platform](#platform)
      - [Infrastructure](#infrastructure)
    - [Fault Injection](#fault-injection-1)
      - [Service](#service-1)
      - [Model](#model-1)
      - [Framework](#framework-1)
      - [Toolkits](#toolkits)
      - [Platform](#platform-1)
      - [Infrastructure](#infrastructure-1)

## Cloud System

### Failure Analysis
-24_DSN_Mutiny! How does Kubernetes fail, and what can we do about it? [[paper]](https://arxiv.org/abs/2404.11169) [[code]](https://zenodo.org/records/10275036)
- 23_Eurosys_Fail through the Cracks: Cross-System Interaction Failures in Modern Cloud Systems [[paper]](https://tianyin.github.io/pub/csi-failures.pdf) [[code]](https://github.com/xlab-uiuc/csi-ae)
- 22_ICSE-SEIP_An Empirical Study on Change-induced Incidents of Online Service Systems [[paper]](https://ieeexplore.ieee.org/document/10172709)
- 22_SoCC_How to Fight Production Incidents? An Empirical Study on a Large-scale Cloud Service [[paper]](https://dl.acm.org/doi/10.1145/3542929.3563482) Awarded Best Paper! 👍
- 22_ISSRE_Going through the Life Cycle of Faults in Clouds:Guidelines on Fault Handling [[paper]](https://yuxiaoba.github.io/publication/incident22/incident22.pdf) [[code]](https://github.com/IntelligentDDS/Post-mortems-Analysis)
- 21_SOSP_Understanding and Detecting Software Upgrade Failures in Distributed Systems [[paper]](https://www.cs.purdue.edu/homes/yonglezh/pub/upgrade-sosp21.pdf)
- 21_DSN_Examining Failures and Repairs on Supercomputers with Multi-GPU Compute Nodes [[paper]](https://ieeexplore.ieee.org/document/9505081) [[data]](http://doi.org/10.5281/zenodo.4606221)
- 20_FSE_Towards Intelligent Incident Management: Why We Need It and How We Make It [[paer]](https://dl.acm.org/doi/pdf/10.1145/3368089.3417055)
- 19_ICSE-SEIP_An Empirical Investigation of Incident Triage for Online Service Systems [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8804464)
- 18_OSDI_An Analysis of Network-Partitioning Failures in Cloud Systems [[paper]](https://www.usenix.org/system/files/osdi18-alquraan.pdf)
- 17_TPDS_Failure Diagnosis for Distributed Systems Using Targeted Fault Injection [[paper]](https://ieeexplore.ieee.org/document/7484300)
- 16_SIGCOM_Taking the Blame Game out of Data Centers Operations with NetPoirot [[paper]](https://dl.acm.org/doi/10.1145/2934872.2934884)

### Fault Injection

- 24_Neural Fault Injection: Generating Software Faults from Natural Language [[paper]](https://arxiv.org/pdf/2404.07491.pdf) 
- 24_S&P_Chronos: Finding Timeout Bugs in Practical Distributed Systems by Deep-Priority Fuzzing with Transient Delay [[paper]](http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/paper_from_24/Chronos_sp24.pdf) [[code]](https://github.com/SecTechTool/Chronos)
- 24_TDSC_MicroFI: Non-Intrusive and Prioritized Request-Level Fault Injection for Microservice Applications [[paper]](https://yuxiaoba.github.io/publication/microfi24/microfi24.pdf)
- 23_SOSP_Acto: Automatic End-to-End Testing for Operation Correctness of Cloud System Management [[paper]](https://www.cs.cornell.edu/~legunsen/pubs/GuETAlActoSOSP23.pdf) [[code]](https://github.com/xlab-uiuc/acto)
- 23_CCS_Phoenix: Detect and Locate Resilience Issues in Blockchain via Context-Sensitive Chaos [[paper]](http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/CCS23.pdf)
- 23_Failure Identification Using Model-Implemented Fault Injection with Domain Knowledge-Guided Reinforcement Learning [[paper]](https://www.mdpi.com/1424-8220/23/4/2166)
- 23_ICSE_Coverage Guided Fault Injection for Cloud Systems [[paper]](http://www.tcse.cn/~gaoyu15/paper/2023-icse-crashfuzz.pdf) [[code]](https://github.com/tcseiscas/crashfuzz)
- 23_NSDI_Push-Button Reliability Testing for Cloud-Backed Applications with Rainmaker [[paper]](https://www.usenix.org/system/files/nsdi23-chen-yinfang.pdf) [[code]](https://github.com/xlab-uiuc/rainmaker)
- 23_Eurosys_Fail through the Cracks: Cross-System Interaction Failures in Modern Cloud Systems [[paper]](https://tianyin.github.io/pub/csi-failures.pdf) [[code]](https://github.com/xlab-uiuc/csi-ae)
- 22_OSDI_Automatic Reliability Testing for Cluster Management Controllers [[paper]](https://www.usenix.org/conference/osdi22/presentation/sun) [[code]](https://github.com/sieve-project/sieve)
- 22_FSE_IBIR: Bug Report driven Fault Injection [[paper]](https://arxiv.org/pdf/2012.06506.pdf) [[code]](https://github.com/serval-uni-lu/IBIR)
- 22_ISSRE_SlowCoach Mutating Code to Simulate Performance Bugs [[paper]](https://ssg.lancs.ac.uk/wp-content/uploads/yq-slowcoach.pdf)
- 22_SBES_Towards a Fault Taxonomy for Microservices-Based Applications [[paper]](https://dl.acm.org/doi/fullHtml/10.1145/3555228.3555245)
- 21_PPoPP_Understanding a Program’s Resiliency Through Error Propagation [[paper]](https://dl.acm.org/doi/pdf/10.1145/3437801.3441589)
- 20_ASE_CoFI: Consistency-Guided Fault Injection for Cloud Systems [[paper]](https://dl.acm.org/doi/pdf/10.1145/3324884.3416548) [[code]](https://hanseychen.github.io/CoFI/)
- 20_ISSRE_How Far Have We Come in Detecting Anomalies in Distributed Systems? An Empirical Study with a Statement-level Fault Injection Method [[paper]](https://ieeexplore.ieee.org/document/9251065)
- 20_DSN_ProFIPy: Programmable Software Fault Injection as-a-Service [[paper]](https://dl.acm.org/doi/10.1145/2841425)
- 20_ASE_CoFI: Consistency-Guided Fault Injection for Cloud Systems [[paper]](https://web.cse.ohio-state.edu/~qin.34/pub-papers/CoFI-ASE20.pdf) [[code]](https://hanseychen.github.io/CoFI/)
- 20_ICWS_Fitness-guided Resilience Testing of Microservice-based Applications [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9283918)
- 19_HotCloud_Co-evolving Tracing and Fault Injection with Box of Pain [[paper]](https://www.usenix.org/system/files/hotcloud19-paper-bittman.pdf)
- 19_ChaosRCA_Observability and Chaos Engineering on System [[paper]](https://arxiv.org/abs/1907.13039)
- 19_Chaos_TRIPLE AGENT- Monitoring, Perturbation and  Failure-obliviousness for Automated Resilience Improvement in Java Applications [[paper]](https://arxiv.org/abs/1812.10706)
- 18_Chaos_A Program-Aware Fault-Injection Method for Dependability Evaluation Against Soft-Error Using Genetic Algorithm [[paper]](https://www.worldscientific.com/doi/10.1142/S021812661850144X)
- 18_TDSC_Faultprog: Testing the Accuracy of Binary-Level Software Fault Injection [[paper]](https://ieeexplore.ieee.org/document/7394118/)
- 16_SoCC_Automating Failure Testing Research at Internet Scale [[paper]](https://dl.acm.org/doi/10.1145/2987550.2987555)
- 16_Survey_Assessing Dependability with Software Fault Injection: A Survey [[paper]](https://dl.acm.org/doi/10.1145/2841425)
- 15_SIGMOD_Lineage-driven Fault Injection [[paper]](https://dl.acm.org/doi/10.1145/2723372.2723711)

### Fault Recovery
- 24_SoCC_Deoxys: A Causal Inference Engine for Unhealthy Node Mitigation in Large-scale Cloud Infrastructure [[paper]](https://arxiv.org/abs/2410.17709)
- 24_Eurosys_Atlas: Hybrid Cloud Migration Advisor for Interactive Microservices [[paper]](https://arxiv.org/pdf/2311.06962.pdf)
- 22_KDD_NENYA: Cascade Reinforcement Learning for Cost-Aware Failure Mitigation at Microsoft 365 [[paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539127)
- 22_SoCC_Method Overloading the Circuit [[paper]](https://dl.acm.org/doi/abs/10.1145/3542929.3563466) [[video]](https://www.youtube.com/watch?v=A3FWuvDEZJI)
- 21_DSN_FIRestarter: Practical Software Crash Recovery with Targeted Library-level Fault Injection [[paper]](https://download.vusec.net/papers/firestarter_dsn21.pdf) [[code]](https://github.com/vusec/firestarter)
- 20_OSDI_Narya: Predictive and Adaptive Failure Mitigation to Avert Production Cloud VM Interruptions [[paper]](https://www.usenix.org/conference/osdi20/presentation/levy)
  
  

## AI System

### Failure Analysis

#### Mixed layer

- 23_ICSE-SEIP_An Empirical Study on Quality Issues of Deep Learning Platform [[paper]](https://arxiv.org/abs/2206.14322)
- 23_TOSEM_Rise of Distributed Deep Learning Training in the Big Model Era: From a Software Engineering Perspective [[paper]](https://dl.acm.org/doi/10.1145/3597204)
- 22_FSE_Understanding Performance Problems in Deep Learning Systems [[paper]](https://arxiv.org/abs/2112.01771) [[code]](https://zenodo.org/record/7060209)
- 20_ICSE_An Empirical Study on Program Failures of Deep Learning Jobs [[paper]](https://dl.acm.org/doi/10.1145/3377811.3380362)
- 19_Analysis of Large-Scale Multi-Tenant GPU Clusters for DNN Training Workloads [[paper]](https://www.usenix.org/conference/atc19/presentation/jeon)

#### Service

- 21_EDBT_JENGA - A Framework to Study the Impact of Data Errors on the Predictions of Machine Learning Models [[paper]](https://openproceedings.org/2021/conf/edbt/p134.pdf)
- 23_QRS_Online Data Drift Detection for Anomaly Detection Services based on Deep Learning towards Multivariate Time Series [[paper]](https://ieeexplore.ieee.org/document/10366704)
- 22_EMNLP_On the Impact of Temporal Concept Drift on Model Explanations [[paper]](https://aclanthology.org/2022.findings-emnlp.298/)
- 19_IOP_An Overview of Overfitting and its Solutions [[paper]](https://iopscience.iop.org/article/10.1088/1742-6596/1168/2/022022)
- 23_How is ChatGPT’s behavior changing over time? [[paper]](https://arxiv.org/pdf/2307.09009)
- 22_ISSRE_LLTFI: Framework Agnostic Fault Injection for Machine Learning Applications (Tools and Artifact Track) [[paper]](https://ieeexplore.ieee.org/document/9978979) [[code]](https://github.com/DependableSystemsLab/LLTFI)
- 23_MPGemmFI: A Fault Injection Technique for Mixed Precision GEMM in ML Applications [[paper]](https://arxiv.org/abs/2311.05782)
- 22_Systematic literature review on software quality for AI-based software [[paper]](https://link.springer.com/article/10.1007/s10664-021-10105-2)
- 21_SWQD_Software Quality for AI: Where We Are Now? [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-65854-0_4)
- 21_ICSE_Are Machine Learning Cloud APIs Used Correctly? [[paper]](https://ieeexplore.ieee.org/document/9402073)
- 23_AI for Cybersecurity: A Study on Machine Learning and DoS Attacks AI Robustness and Bypassing Detection Methods [[paper]](https://hh.diva-portal.org/smash/get/diva2:1777110/FULLTEXT02.pdf)
- 23_Tricking llms into disobedience: Understanding, analyzing, and preventing jailbreaks [[paper]](https://arxiv.org/abs/2305.14965)
- 21_Advances in Adversarial Attacks and Defenses in Computer Vision: A Survey [[paper]](https://ieeexplore.ieee.org/document/9614158)
- 24_AAAI_Visual Adversarial Examples Jailbreak Aligned Large Language Models [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/30150)

#### Model

- 22_Faults in deep reinforcement learning programs: a taxonomy and a detection approach [[paper]](https://link.springer.com/article/10.1007/s10515-021-00313-x)
- 23_ICSE_Data Quality for Software Vulnerability Datasets [[paper]](https://ieeexplore.ieee.org/document/10172650)
- 22_Author Correction: Advances, challenges and opportunities in creating data for trustworthy AI [[paper]](https://www.nature.com/articles/s42256-022-00548-7)
- 22_A review: Data pre-processing and data augmentation techniques [[paper]](https://www.sciencedirect.com/science/article/pii/S2666285X22000565)
- 23_VLDB_Data collection and quality challenges in deep learning: a data-centric AI perspective [[paper]](https://link.springer.com/article/10.1007/s00778-022-00775-9)
- 20_Impact of fully connected layers on performance of convolutional neural networks for image classification [[paper]](https://www.sciencedirect.com/science/article/pii/S0925231219313803)
- 20_INMIC_Effects of hidden layers on the efficiency of neural networks [[paper]](https://ieeexplore.ieee.org/document/9318195)
- 24_ShortGPT: Layers in Large Language Models are More Redundant Than You Expect [[paper]](https://arxiv.org/abs/2403.03853)
- 23_Finding Neurons in a Haystack: Case Studies with Sparse Probing [[paper]](https://arxiv.org/abs/2305.01610)
- 19_NeurIPS_Control Batch Size and Learning Rate to Generalize Well: Theoretical and Empirical Evidence [[paper]](https://proceedings.neurips.cc/paper/2019/hash/dc6a70712a252123c40d2adba6a11d84-Abstract.html)
- 23_Exploring the Relationship Between Learning Rate, Batch Size, and Epochs in Deep Learning: An Experimental Study [[paper]](https://link.springer.com/chapter/10.1007/978-981-19-6525-8_16)
- 23_A Comprehensive Overview and Comparative Analysis on Deep Learning Models: CNN, RNN, LSTM, GRU [[paper]](https://arxiv.org/abs/2305.17473)
- 22_Activation functions in deep learning: A comprehensive survey and benchmark [[paper]](https://linkinghub.elsevier.com/retrieve/pii/S0925231222008426)
- 22_A comprehensive survey on regularization strategies in machine learning [[paper]](https://linkinghub.elsevier.com/retrieve/pii/S156625352100230X)
- 21_Comparison of optimization techniques based on gradient descent algorithm: A review [[paper]](https://www.researchgate.net/publication/349573260_COMPARISON_OF_OPTIMIZATION_TECHNIQUES_BASED_ON_GRADIENT_DESCENT_ALGORITHM_A_REVIEW_PJAEE_18_4_2021_COMPARISON_OF_OPTIMIZATION_TECHNIQUES_BASED_ON_GRADIENT_DESCENT_ALGORITHM_A_REVIEW_Comparison_Of_Opti)
- 20_A comprehensive survey of loss functions in machine learning [[paper]](https://link.springer.com/article/10.1007/s40745-020-00253-5)
- 22_Ideal dataset splitting ratios in machine learning algorithms: general concerns for data scientists and data analysts [[paper]](https://www.researchgate.net/publication/358284895_IDEAL_DATASET_SPLITTING_RATIOS_IN_MACHINE_LEARNING_ALGORITHMS_GENERAL_CONCERNS_FOR_DATA_SCIENTISTS_AND_DATA_ANALYSTS)

#### Framework

- 24_ESE_Silent Bugs in Deep Learning Frameworks: An Empirical Study of Keras and TensorFlow [[paper]](https://arxiv.org/abs/2112.13314) [[code]](https://github.com/amin-nikanjam/SilentBugsInTensorFlowKeras)
- 23_ICPC_Understanding Bugs in Multi-Language Deep Learning Frameworks [[paper]](https://arxiv.org/abs/2303.02695)
- 23_TOSEM_Toward Understanding Deep Learning Framework Bugs [[paper]](https://arxiv.org/pdf/2203.04026.pdf)
- 22_ICSME_An Empirical Study on Performance Bugs in Deep Learning Frameworks [[paper]](https://petertsehsun.github.io/papers/performance_issues_study.pdf)
- 20_ICSE_Taxonomy of Real Faults in Deep Learning Systems [[paper]](https://arxiv.org/pdf/1910.11015.pdf)
- 19_FSE_A Comprehensive Study on Deep Learning Bug Characteristics [[paper]](https://arxiv.org/abs/1906.01388)
- 18_FSE_An Empirical Study on TensorFlow Program Bugs [[paper]](https://dl.acm.org/doi/10.1145/3213846.3213866)
- 24_NSDI_Characterization of Large Language Model Development in the Datacenter [[paper]](https://www.usenix.org/system/files/nsdi24-hu.pdf)
- 22_INFSOF_A comprehensive empirical study on bug characteristics of deep learning frameworks [[paper]](https://dl.acm.org/doi/10.1016/j.infsof.2022.107004)
- 22_ASE_Towards Understanding the Faults of JavaScript-Based Deep Learning Systems [[paper]](https://dl.acm.org/doi/abs/10.1145/3551349.3560427)
- 20_ICSE_An empirical study on program failures of deep learning jobs [[paper]](https://dl.acm.org/doi/10.1145/3377811.3380362)
- 12_ISSRE_An Empirical Study of Bugs in Machine Learning Systems [[paper]](https://ieeexplore.ieee.org/document/6405375)
- 23_TCAD_Statistical Modeling of Soft Error Influence on Neural Networks [[paper]](https://ieeexplore.ieee.org/abstract/document/10098868/)
- 23_Towards efficient generative large language model serving: A survey from algorithms to systems [[paper]](https://arxiv.org/abs/2312.15234)
- 20_DFT_A Pipelined Multi-Level Fault Injector for Deep Neural Networks [[paper]](https://ieeexplore.ieee.org/abstract/document/9250866/)
- 20_ICSE_An empirical study on program failures of deep learning jobs [[paper]](https://dl.acm.org/doi/10.1145/3377811.3380362)
- 23_ISCE_An Empirical Study on Quality Issues of Deep Learning Platform [[paper]](https://ieeexplore.ieee.org/iel7/10172485/10172344/10172667.pdf)

#### Tooolkits

- 13_ESOP_Interleaving and lock-step semantics for analysis and verification of GPU kernels [[paper]](https://link.springer.com/chapter/10.1007/978-3-642-37036-6_16)
- 19_ASE_Automating CUDA Synchronization via Program Transformation [[paper]](https://ieeexplore.ieee.org/document/8952529)
- 18_ISSRE_Bugaroo: Exposing Memory Model Bugs in Many-Core Systems [[paper]](https://ieeexplore.ieee.org/document/8539080)
- 19_SP_SoK: Sanitizing for Security [[paper]](https://oaklandsok.github.io/papers/song2019.pdf)
- 23_PLDI_cuCatch: A Debugging Tool for Efficiently Catching Memory Safety Violations in CUDA Applications [[paper]](https://dl.acm.org/doi/abs/10.1145/3591225)
- 23_FSE_Demystifying Dependency Bugs in Deep Learning Stack [[paper]](https://dl.acm.org/doi/abs/10.1145/3611643.3616325)
- 23_ISCE_An Empirical Study on Quality Issues of Deep Learning Platform [[paper]](https://ieeexplore.ieee.org/iel7/10172485/10172344/10172667.pdf)
- 24_NSDI_Characterization of Large Language Model Development in the Datacenter [[paper]](https://www.usenix.org/system/files/nsdi24-hu.pdf)
- 19_ATC_Analysis of Large-Scale Multi-Tenant GPU Clusters for DNN Training Workloads [[paper]](https://www.usenix.org/conference/atc19/presentation/jeon)
- 14_PLDI_Accurate application progress analysis for large-scale parallel debugging [[paper]](https://dl.acm.org/doi/abs/10.1145/2666356.2594336)
- 04_SC_Assessing Fault Sensitivity in MPI Applications [[paper]](https://ieeexplore.ieee.org/abstract/document/1392967/)
- 16_TECS_CUDA Leaks: A Detailed Hack for CUDA and a (Partial) Fix [[paper]](https://dl.acm.org/doi/abs/10.1145/2801153)
- 18_PLDI_CURD: a dynamic CUDA race detector [[paper]](https://dl.acm.org/doi/abs/10.1145/3296979.3192368)
- 17_JSA_Evaluation of transient errors in GPGPUs for safety critical applications: An effective simulation-based fault injection environment [[paper]](https://www.sciencedirect.com/science/article/pii/S1383762117300528)
- 14_DAC_Exploring the Heterogeneous Design Space for both Performance and Reliability [[paper]](https://dl.acm.org/doi/abs/10.1145/2593069.2596680)
- 14_LATW_Implementation and experimental evaluation of a CUDA core under single event effects [[paper]](https://ieeexplore.ieee.org/abstract/document/6841913/)
- 17_PVM_What does fault tolerant deep learning need from MPI? [[paper]](https://dl.acm.org/doi/abs/10.1145/3127024.3127037)

#### Platform

- 21_ACCESS_Diaspore: Diagnosing Performance Interference in Apache Spark [[paper]](https://ieeexplore.ieee.org/document/9490641)
- 15_HPCC-CSS-ICESS_Performance Prediction for Apache Spark Platform [[paper]](https://ieeexplore.ieee.org/document/7336160)
- 17_ICWS_Log-based Abnormal Task Detection and Root Cause Analysis for Spark [[paper]](https://ieeexplore.ieee.org/document/8029786)
- 23_ICSE-SEIP_An Empirical Study on Quality Issues of Deep Learning Platform [[paper]](https://www.computer.org/csdl/proceedings-article/icse-seip/2023/003700a455/1OH5KriGABa)

#### Infrastructure

- 21_DSN_Examining Failures and Repairs on Supercomputers with Multi-GPU Compute Nodes [[paper]](https://ieeexplore.ieee.org/document/9505081)
- 20_SC_GPU Lifetimes on Titan Supercomputer: Survival Analysis and Reliability [[paper]](https://ieeexplore.ieee.org/document/9355319)
- 17_SC_Failures in Large Scale Systems: Long-Term Measurement, Analysis, and Implications [[paper]](https://dl.acm.org/doi/pdf/10.1145/3126908.3126937)
- 15_SC_Reliability Lessons Learned From GPU Experience With The Titan Supercomputer at Oak Ridge Leadership Computing Facility [[paper]](https://ieeexplore.ieee.org/document/7832812)
- 16_HPCA_A large-scale study of soft-errors on GPUs in the field [[paper]](https://ieeexplore.ieee.org/document/7446091)
- 17_MASCOTS_Characterizing Temperature, Power, and Soft-Error Behaviors in Data Center Systems: Insights, Challenges, and Opportunities [[paper]](https://ieeexplore.ieee.org/document/8107428)
- 15_HPCA_Understanding GPU errors on large-scale HPC systems and the implications for system design and operation [[paper]](https://ieeexplore.ieee.org/document/7056044)
- 14_DSN_Lessons Learned from the Analysis of System Failures at Petascale: The Case of Blue Waters [[paper]](https://ieeexplore.ieee.org/document/6903615)
- 20_ICSE_An empirical study on program failures of deep learning jobs [[paper]](https://dl.acm.org/doi/10.1145/3377811.3380362)
- 23_SYSTOR_Predicting GPU Failures With High Precision Under Deep Learning Workloads [[paper]](https://dl.acm.org/doi/10.1145/3579370.3594777)
- 14_LISAT_Reliability and fault tolerance analysis of FPGA platforms [[paper]](https://ieeexplore.ieee.org/document/6845211)
- 16_J_NET_Field Programmable Gate Array Reliability Analysis Using the Dynamic Flowgraph Methodology [[paper]](https://doi.org/10.1016/j.net.2016.03.004)
- 10_TII_Component-Based Safety Analysis of FPGAs [[paper]](https://ieeexplore.ieee.org/document/5422708)
- 21_TVLSI_Reliability Evaluation and Analysis of FPGA-Based Neural Network Acceleration System [[paper]](https://ieeexplore.ieee.org/document/9316989)
- 24_TNS_Tensor Processing Unit Reliability Dependence on Temperature and Radiation Source [[paper]](https://ieeexplore.ieee.org/document/10415538)
- 22_RADECS_Sensitivity of Google’s Tensor Processing Units to High-Energy, Mono-Energetic, and Thermal Neutrons [[paper]](https://ieeexplore.ieee.org/document/10412572)
- 22_DATE_Reliability of Google's Tensor Processing Units for Embedded Applications [[paper]](https://ieeexplore.ieee.org/document/9774600)

### Fault Injection

- 22_SANER_How Do Injected Bugs Affect Deep Learning? [[paper]](https://www.cs.sjtu.edu.cn/~zhonghao/paper/saner-mutation.pdf) [[code]](https://github.com/bugdataupload/deeplearningbugs)

#### Service

- 24_ICSE_Not what you’ve signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection [[paper]](https://arxiv.org/abs/2302.12173)
- 15_ICLR_Explaining and Harnessing Adversarial Examples [[paper]](https://arxiv.org/abs/1412.6572) [[code]](https://github.com/Harry24k/FGSM-pytorch)
- 18_ICLR_Towards Deep Learning Models Resistant to Adversarial Attacks [[paper]](https://openreview.net/forum?id=rJzIBfZAb) [[code]](https://github.com/Harry24k/PGD-pytorch)
- 22_DI-AA: An interpretable white-box attack for fooling deep neural networks [[paper]](https://www.sciencedirect.com/science/article/pii/S0020025522008520)
- 20_SP_HopSkipJumpAttack: A Query-Efficient Decision-Based Attack [[paper]](https://ieeexplore.ieee.org/document/9152788) [[code]](https://github.com/ngoctnq/hopskipjumpattack)
- 21_ICML_PopSkipJump: Decision-Based Attack for Probabilistic Classifiers [[paper]](http://proceedings.mlr.press/v139/simon-gabriel21a.html) [[code]](https://github.com/cjsg/PopSkipJump)
- 20_CVPR_GeoDA: A Geometric Framework for Black-Box Adversarial Attacks [[paper]](https://ieeexplore.ieee.org/document/9157133) [[code]](https://github.com/SCLBD/BlackboxBench?tab=readme-ov-file)
- 23_I See Dead People: Gray-Box Adversarial Attack on Image-To-Text Models [[paper]](https://arxiv.org/abs/2306.07591)
- 23_Promptaid: Prompt exploration, perturbation, testing and iteration using visual analytics for large language models [[paper]](https://arxiv.org/abs/2304.01964)
- 23_Prompt Injection attack against LLM-integrated Applications [[paper]](https://arxiv.org/abs/2306.05499)
- 24_Goal-guided Generative Prompt Injection Attack on Large Language Models [[paper]](https://arxiv.org/abs/2404.07234)
- 20_DSN_PyTorchFI: A Runtime Perturbation Tool for DNNs [[paper]](https://ieeexplore.ieee.org/document/9151812) [[code]](https://github.com/pytorchfi/pytorchfi)
- 18_ISSRE_TensorFI: A Configurable Fault Injector for TensorFlow Applications [[paper]](https://ieeexplore.ieee.org/document/8539213) [[code]](https://github.com/DependableSystemsLab/TensorFI)
- 21_DeepTest_TF-DM: Tool for Studying ML Model Resilience to Data Faults [[paper]](https://ieeexplore.ieee.org/document/9476897) [[code]](https://github.com/DependableSystemsLab/TF-DM)
- 21_ISSREW_MindFI: A Fault Injection Tool for Reliability Assessment of MindSpore Applicacions [[paper]](https://ieeexplore.ieee.org/document/9700393)
- 18_DAC_Ares: a framework for quantifying the resilience of deep neural networks [[paper]](https://dl.acm.org/doi/10.1145/3195970.3195997) [[code]](https://github.com/alugupta/ares)
- 19_SC_BinFI : an efficient fault injector for safety-critical machine learning systems [[paper]](https://dl.acm.org/doi/10.1145/3295500.3356177) [[code]](https://github.com/DependableSystemsLab/TensorFI-BinaryFI)

#### Model

- 18_ISSRE_DeepMutation: Mutation Testing of Deep Learning Systems [[paper]](https://ieeexplore.ieee.org/document/8539073) [[code]](https://github.com/tkuo-tkuo/DeepMutationOperators)
- 19_ASE_DeepMutation++: A Mutation Testing Framework for Deep Learning Systems [[paper]](https://ieeexplore.ieee.org/document/8952248)
- 18_QRS_MuNN: Mutation Analysis of Neural Networks [[paper]](https://ieeexplore.ieee.org/document/8431960)
- 21_ISSTA_DeepCrime: Mutation Testing of Deep Learning Systems Based on Real Faults [[paper]](https://dl.acm.org/doi/10.1145/3460319.3464825) [[code]](https://github.com/dlfaults/deepcrime)
- 22_Towards mutation testing of Reinforcement Learning systems [[paper]](https://linkinghub.elsevier.com/retrieve/pii/S1383762122001977)
- 23_ICST_Mutation Testing of Deep Reinforcement Learning Based on Real Faults [[paper]](https://ieeexplore.ieee.org/document/10132198)
- 22_SETTA_MTUL: Towards Mutation Testing of Unsupervised Learning Systems [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-21213-0_2)

#### Framework

- 20_ISSRE_TensorFI: Flexible Fault Injection Framework for TensorFlow Applications [[paper]]([CSDL | IEEE Computer Society](https://www.computer.org/csdl/proceedings-article/issre/2020/987000a426/1oFGJJ92Fy0)) [[code]](https://github.com/DependableSystemsLab/TensorFI)
- 22_TDSC_Fault Injection for TensorFlow Applications [[paper]]([Fault Injection for TensorFlow Applications | IEEE Journals &amp; Magazine | IEEE Xplore](https://ieeexplore.ieee.org/document/9831186)) [[code]](https://github.com/DependableSystemsLab/TensorFI2)
- 20_Fault Injectors for TensorFlow: Evaluation of the Impact of Random Hardware Faults on Deep CNNs [[paper]]([[2012.07037] Fault Injectors for TensorFlow: Evaluation of the Impact of Random Hardware Faults on Deep CNNs](https://arxiv.org/abs/2012.07037)) [[code]](https://github.com/mbsa-tud/InjectTF)
- 20_LASCAS_Reliability Evaluation of Compressed Deep Learning Models [[paper]](https://ieeexplore.ieee.org/document/9069026) [[code]](https://github.com/bfgoldstein/torchfi)
- 20_DSN_PyTorchFI: A Runtime Perturbation Tool for DNNs [[paper]](https://ieeexplore.ieee.org/document/9151812) [[code]](https://github.com/pytorchfi/pytorchfi)
- 22_TR_SNIFF: Reverse Engineering of Neural Networks With Fault Attacks [[paper]](https://ieeexplore.ieee.org/document/9530205)
- 21_ISSREW_MindFI: A Fault Injection Tool for Reliability Assessment of MindSpore Applicacions [[paper]](https://ieeexplore.ieee.org/document/9700393)
- 22_IROS_enpheeph: A Fault Injection Framework for Spiking and Compressed Deep Neural Networks [[paper]](https://ieeexplore.ieee.org/iel7/9981026/9981028/09982181.pdf) [[code]](https://github.com/Alexei95/enpheeph)
- 23_TC_Fast and Accurate Error Simulation for CNNs Against Soft Errors [[paper]](https://arxiv.org/abs/2206.02051)
- 17_ICCAD_Fault injection attack on deep neural network [[paper]](https://ieeexplore.ieee.org/abstract/document/8203770/)
- 22_ISSRE_LLTFI: Framework Agnostic Fault Injection for Machine Learning Applications (Tools and Artifact Track) [[paper]](https://ieeexplore.ieee.org/document/9978979) [[code]](https://github.com/DependableSystemsLab/LLTFI)
- 23_ETS_SCI-FI: a Smart, aCcurate and unIntrusive Fault-Injector for Deep Neural Networks [[paper]](https://ieeexplore.ieee.org/abstract/document/10173957/)

#### Toolkits

- 15_Cluster_Fast Fault Injection and Sensitivity Analysis for Collective Communications [[paper]](https://ieeexplore.ieee.org/document/7307578)
- 20_ICSE_Simulee: detecting CUDA synchronization bugs via memory-access modeling [[paper]](https://dl.acm.org/doi/10.1145/3377811.3380358) [[code]](https://github.com/Lebronmydx/Simulee)
- 20_COMPSAC_CUDAsmith: A Fuzzer for CUDA Compilers [[paper]](https://ieeexplore.ieee.org/document/9202798) [[code]](https://github.com/gongbell/CUDAsmith)
- 15_SIGPLAN_Many-core compiler fuzzing [[paper]](https://dl.acm.org/doi/10.1145/2737924.2737986) [[code]](https://github.com/ChrisLidbury/CLSmith/)
- 00_IPDPS_FIMD-MPI: a tool for injecting faults into MPI application [[paper]](https://ieeexplore.ieee.org/abstract/document/845991/)

#### Platform

- 22_STVR_TRANSMUT-Spark: Transformation mutation for Apache Spark [[paper]](https://onlinelibrary.wiley.com/doi/10.1002/stvr.1809)
- 23_FSE_Co-dependence Aware Fuzzing for Dataflow-Based Big Data Analytics [[paper]](https://dl.acm.org/doi/10.1145/3611643.3616298)

#### Infrastructure

- 17_ISPASS_SASSIFI: An architecture-level fault injection tool for GPU application resilience evaluation [[paper]](https://doi.org/10.1109/ISPASS.2017.7975296)
- 14_ISPASS_GPU-Qin: A methodology for evaluating the error resilience of GPGPU applications [[paper]](https://ieeexplore.ieee.org/document/6844486/)
- 21_DSN_NVBitFI: Dynamic Fault Injection for GPUs[[paper]](https://ieeexplore.ieee.org/document/9505068)
- 16_SC_Understanding Error Propagation in GPGPU Applications [[paper]](https://ieeexplore.ieee.org/document/7877099)
- 17_SC_Understanding error propagation in deep learning neural network (DNN) accelerators and applications [[paper]](https://dl.acm.org/doi/10.1145/3126908.3126964)
- 17_HPCA_RadiationInduced Error Criticality in Modern HPC Parallel Accelerators [[paper]](https://doi.org/10.1109/HPCA.2017.41)
- 18_SBAC-PAD_On the Resilience of RTL NN Accelerators: Fault Characterization and Mitigation [[paper]](https://ieeexplore.ieee.org/document/8645906)
- 12_ISCA_A defect-tolerant accelerator for emerging high-performance applications [[paper]](https://ieeexplore.ieee.org/document/6237031)
- 21_VTS_Combining Architectural Simulation and Software Fault Injection for a Fast and Accurate CNNs Reliability Evaluation on GPUs [[paper]](https://ieeexplore.ieee.org/document/9441044)
- 02_DFT_Using run-time reconfiguration for fault injection in hardware prototypes [[paper]](https://ieeexplore.ieee.org/document/1173521)
- 12_DFT_Fast single-FPGA fault injection platform [[paper]](https://ieeexplore.ieee.org/document/6378216)
- 14_J.MICROEL_A fast, flexible, and easy-to-develop FPGA-based fault injection technique [[paper]](https://doi.org/10.1016/J.MICROREL.2014.01.002)
- 01_ATS_FPGA-based fault injection for microprocessor systems [[paper]](https://ieeexplore.ieee.org/document/990301)
- 20_Desgin&Test_Enabling Timing Error Resilience for Low-Power Systolic-Array Based Deep Learning Accelerators [[paper]](https://ieeexplore.ieee.org/document/8868188)
- 21_ATS_GPU-Accelerated Timing Simulation of Systolic-Array-Based AI Accelerators [[paper]](https://ieeexplore.ieee.org/document/9668210)
- Lightning: Leveraging DVFS-induced Transient Fault Injection to Attack Deep Learning Accelerator of GPUs [[paper]](https://dl.acm.org/doi/10.1145/3617893)
