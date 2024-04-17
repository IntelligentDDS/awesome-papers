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
      - [Tooolkits](#tooolkits-1)
      - [Platform](#platform-1)
      - [Infrastructure](#infrastructure-1)


## Cloud System

### Failure Analysis

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
-24_Eurosys_Atlas: Hybrid Cloud Migration Advisor for Interactive Microservices [[paper]](https://arxiv.org/pdf/2311.06962.pdf)
- 22_KDD_NENYA: Cascade Reinforcement Learning for Cost-Aware Failure Mitigation at Microsoft 365 [[paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539127)
- 22_SoCC_Method Overloading the Circuit [[paper]](https://dl.acm.org/doi/abs/10.1145/3542929.3563466) [[video]](https://www.youtube.com/watch?v=A3FWuvDEZJI)
- 21_DSN_FIRestarter: Practical Software Crash Recovery with Targeted Library-level Fault Injection [[paper]](https://download.vusec.net/papers/firestarter_dsn21.pdf) [[code]](https://github.com/vusec/firestarter)




## AI System

### Failure Analysis

#### Mixed layer

- 23_ICSE-SEIP_An Empirical Study on Quality Issues of Deep Learning Platform [[paper]](https://arxiv.org/abs/2206.14322)
- 23_TOSEM_Rise of Distributed Deep Learning Training in the Big Model Era: From a Software Engineering Perspective [[paper]](https://dl.acm.org/doi/10.1145/3597204)
- 22_FSE_Understanding Performance Problems in Deep Learning Systems [[paper]](https://arxiv.org/abs/2112.01771) [[code]](https://zenodo.org/record/7060209)
- 20_ICSE_An Empirical Study on Program Failures of Deep Learning Jobs [[paper]](https://dl.acm.org/doi/10.1145/3377811.3380362)
- 19_Analysis of Large-Scale Multi-Tenant GPU Clusters for DNN Training Workloads [[paper]](https://www.usenix.org/conference/atc19/presentation/jeon)

#### Service 

#### Model 


#### Framework
- 24_ESE_Silent Bugs in Deep Learning Frameworks: An Empirical Study of Keras and TensorFlow [[paper]](https://arxiv.org/abs/2112.13314) [[code]](https://github.com/amin-nikanjam/SilentBugsInTensorFlowKeras)
- 23_ICPC_Understanding Bugs in Multi-Language Deep Learning Frameworks [[paper]](https://arxiv.org/abs/2303.02695)
- 23_TOSEM_Toward Understanding Deep Learning Framework Bugs [[paper]](https://arxiv.org/pdf/2203.04026.pdf)
- 22_ICSME_An Empirical Study on Performance Bugs in Deep Learning Frameworks [[paper]](https://petertsehsun.github.io/papers/performance_issues_study.pdf)
- 20_ICSE_Taxonomy of Real Faults in Deep Learning Systems [[paper]](https://arxiv.org/pdf/1910.11015.pdf)
- 19_FSE_A Comprehensive Study on Deep Learning Bug Characteristics [[paper]](https://arxiv.org/abs/1906.01388)
- 18_FSE_An Empirical Study on TensorFlow Program Bugs [[paper]](https://dl.acm.org/doi/10.1145/3213846.3213866)

#### Tooolkits

#### Platform


#### Infrastructure

- 21_DSN_Examining Failures and Repairs on Supercomputers with Multi-GPU Compute Nodes [[paper]](https://ieeexplore.ieee.org/document/9505081)
- 20_SC_GPU Lifetimes on Titan Supercomputer: Survival Analysis and Reliability [[paper]](https://ieeexplore.ieee.org/document/9355319)
- 17_SC_Failures in Large Scale Systems: Long-Term Measurement, Analysis, and Implications [[paper]](https://dl.acm.org/doi/pdf/10.1145/3126908.3126937)
- 15_SC_Reliability Lessons Learned From GPU Experience With The Titan Supercomputer at Oak Ridge Leadership Computing Facility [[paper]](https://ieeexplore.ieee.org/document/7832812)


### Fault Injection

- 22_SANER_How Do Injected Bugs Affect Deep Learning? [[paper]](https://www.cs.sjtu.edu.cn/~zhonghao/paper/saner-mutation.pdf) [[code]](https://github.com/bugdataupload/deeplearningbugs)

#### Service 

- 24_ICSE_Not what you’ve signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection [[paper]](https://arxiv.org/abs/2302.12173)


#### Model 



#### Framework


#### Tooolkits

- 15_Cluster_Fast Fault Injection and Sensitivity Analysis for Collective Communications [[paper]](https://ieeexplore.ieee.org/document/7307578)

#### Platform

#### Infrastructure


- Lightning: Leveraging DVFS-induced Transient Fault Injection to Attack Deep Learning Accelerator of GPUs [[paper]](https://dl.acm.org/doi/10.1145/3617893)










