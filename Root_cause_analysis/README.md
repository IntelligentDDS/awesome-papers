# Root cause analysis in distributed system

**Content**
- [Root cause analysis in distributed system](#root-cause-analysis-in-distributed-system)
  - [Metric](#metric)
  - [Log](#log)
  - [Trace](#trace)
  - [Metric and Trace](#metric-and-trace)
  - [Metric, Log and Trace](#metric-log-and-trace)
  - [Network](#network)
  - [Alert](#alert)


## Metric
- 22_DSN_RAPMiner: A Generic Anomaly Localization Mechanism for CDN System with Multi-dimensional KPIs [[paper]](https://ieeexplore.ieee.org/document/9833589/) [[code]](https://github.com/liuchangsophie/RAPMiner)
- 22_ASE_Graph based Incident Extraction and Diagnosis in Large-Scale Online Systems [[paper]](https://yuxiaoba.github.io/publication/gied22/gied22.pdf) [[code]](https://github.com/IntelligentDDS/GIED)
- 22_FSE_Actionable and Interpretable Fault Localization for Recurring Failures in Online Service Systems [[paper]](https://arxiv.org/abs/2207.09021) [[code]](https://github.com/NetManAIOps/DejaVu)
- 21_ICSE Workshop_MicroDiag: Fine-grained Performance Diagnosis for Microservice Systems [[paper]](https://hal.inria.fr/hal-03155797/document)
- 21_ICSE Workshop_MicroHECL: High-Efﬁcient Root Cause Localization in Large-Scale Microservice Systems [[paper]](https://arxiv.org/pdf/2103.01782.pdf)
- 21_ISSRE_Identifying Root-Cause Metrics for Incident Diagnosis in Online Service Systems [[paper]](http://netman.aiops.org/wp-content/uploads/2021/10/wch_ISSRE-1.pdf)
- 20_ASE_ImpAPTr: A Tool For Identifying The Clues To Online Service Anomalies [[paper]](https://dl.acm.org/doi/10.1145/3324884.3415301) [[code]](https://github.com/wanghaoUp/ImpAPTr)
- 20_VLDB_VLDB_Diagnosing Root Causes of Intermittent Slow Queries in Cloud Databases [[paper]](http://www.vldb.org/pvldb/vol13/p1176-ma.pdf) [[code]](https://github.com/NetManAIOps/DejaVu/blob/master/iSQUAD/iSQ.py)
- 20_IWQoS_Localizing Failure Root Causes in a Microservice through Causality Inference [[paper]](https://ieeexplore.ieee.org/document/9213058)
- 20_NOMS_MicroRCA: Root Cause Localization of Performance Issues in Microservices [[paper]](https://ieeexplore.ieee.org/document/9110353) [[code]](https://github.com/elastisys/MicroRCA)
- 16_ICSE_iDice: Problem Identification for Emerging Issues [[paper]](http://hongyujohn.github.io/iDice.pdf)
- 18_ICSOC_Microscope: Pinpoint Performance Issues with Causal Graphs in Micro-service Environments [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-03596-9_1)
- 18_OSDI_Orca: Differential Bug Localization in Large-Scale Services [[paper]](https://www.usenix.org/conference/osdi18/presentation/bhagwan) Awarded Best Paper! 👍
- 14_NSDI_Adtributor: Revenue Debugging in Advertising Systems [[paper]](https://www.usenix.org/system/files/conference/nsdi14/nsdi14-paper-bhagwan.pdf)

## Log

- 21_ISSTA_Faster, Deeper, Easier: Crowdsourcing Diagnosis of Microservice Kernel Failure from User Space [[paper]](https://dl.acm.org/doi/abs/10.1145/3460319.3464805) [[code]](https://github.com/PanYicheng/dycause_rca)
- 20_ICSE-SEIP_DeCaf: Diagnosing and Triaging Performance Issues in Large-Scale Cloud Services [[paper]](https://dl.acm.org/doi/pdf/10.1145/3377813.3381353) [[code]](https://github.com/SEALABQualityGroup/replication_delag/blob/main/techniques/decaf/decaf.py)
- 19_ICSE_Mining Historical Test Logs to Predict Bugs and Localize Faults in the Test Logs [[paper]](https://dl.acm.org/doi/pdf/10.1109/ICSE.2019.00031)
- 18_FSE_Identifying Impactful Service System Problems via Log Analysis [[paper]](https://dl.acm.org/doi/10.1145/3236024.3236083) [code](https://github.com/logpai/Log3C)
- 18_ESEM_Spectrum-Based Log Diagnosis [[paper]](https://dl.acm.org/doi/pdf/10.1145/3382494.3410684)
- 14_Cluster_Digging Deeper into Cluster System Logs for Failure Prediction and Root Cause Diagnosis [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6968768)
  

## Trace

- 22_Cloud_Localizing and Explaining Faults in Microservices Using Distributed Tracing [[paper]](https://ieeexplore.ieee.org/document/9860589/)
- 22_ICSOC_MicroSketch: Lightweight and Adaptive Sketch based Performance Issue Detection and Localization in Microservice Systems [[paper]](https://yuxiaoba.github.io/publication/microsketch22/microsketch22.pdf)
- 22_ESE_Enjoy your observability: an industrial survey of microservice tracing and analysis [[paper]](https://link.springer.com/article/10.1007/s10664-021-10063-9) 
- 21_Usenix ATC_Argus: Debugging Performance Issues in Modern Desktop Applications with Annotated Causal Tracing [[paper]](https://www.usenix.org/system/files/atc21-weng.pdf) [[code]](https://github.com/columbia/ArgusDebugger) Awarded Best Paper! 👍
- 21_WWW_MicroRank: End-to-End Latency Issue Localization with Extended Spectrum Analysis in Microservice Environments [[paper]](https://dl.acm.org/doi/10.1145/3442381.3449905) [[code]](https://github.com/IntelligentDDS/MicroRank)
- 21_JSEP_TraceRank: Abnormal service localization with dis‐aggregated end‐to‐end tracing data in cloud native systems [[paper]](https://onlinelibrary.wiley.com/doi/full/10.1002/smr.2413)
- 20_CCGrid_T-Rank:A Lightweight Spectrum based Fault Localization Approach for Microservice Systems [[paper]](https://ieeexplore.ieee.org/abstract/document/9499404)
- 18_Asplos_FCatch: Automatically Detecting Time-of-fault Bugs in Cloud Systems [[paper]](https://dl.acm.org/doi/10.1145/3296957.3177161)
- 18_ATC_Troubleshooting Transiently-Recurring Problems in Production Systems with Blame-Proportional Logging [[paper]](https://www.usenix.org/conference/atc18/presentation/luo)
- 16_TPDS_Failure Diagnosis for Distributed Systems using Targeted Fault Injection [[paper]](https://ieeexplore.ieee.org/document/7484300/)
- 14_OSDI_The Mystery Machine: End-to-end performance analysis of large-scale Internet services [[paper]](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-chow.pdf)
- 02_DSN_Pinpoint: Problem Determination in Large, Dynamic Internet Services [[paper]](https://ieeexplore.ieee.org/document/1029005)

## Metric and Trace
- 21_ASPLOS_Sage: Practical & Scalable ML-Driven Performance Debugging in Microservices [[paper]](https://www.csl.cornell.edu/~delimitrou/papers/2021.asplos.sage.pdf)

## Metric, Log and Trace
- 23_ICSE_Eadro: An End-to-End Troubleshooting Framework for Microservices on Multi-source Data 
- 22_ICSE_PerfSig: Extracting Performance Bug Signatures via Multi-modality Causal Analysis [[paper]](https://jhe16.github.io/files/ICSE22.pdf) [[code]](https://github.com/jhe16/PerfSig)
- - 21_IPDSP_Diagnosing Performance Issues in Microservices with Heterogeneous Data Source [[paper]](http://www.cloud-conf.net/ispa2021/proc/pdfs/ISPA-BDCloud-SocialCom-SustainCom2021-3mkuIWCJVSdKJpBYM7KEKW/264600a493/264600a493.pdf)
- 20_ESOCC_Multi-source Distributed System Data for AI-Powered Analytics [[paper]](https://link.springer.com/content/pdf/10.1007/978-3-030-44769-4_13.pdf) [[[data]](https://zenodo.org/record/3549604#.YkJeszNBy3I) [[code]](https://github.com/snedelkoski/multi-source-observability-dataset)

## Network
- 20_Sigcom_Microscope: Queue-based Performance Diagnosis for Network Functions [[paper]](https://dl.acm.org/doi/pdf/10.1145/3387514.3405876)
- 16_Sigcom_The Good, the Bad, and the Differences: Better Network Diagnostics with Differential Provenance [[paper]](https://dl.acm.org/doi/10.1145/2934872.2934910)

## Alert
- 20_ICSE_Understanding and handling alert storm for online service systems [[paper]](https://dl.acm.org/doi/abs/10.1145/3377813.3381363) 
- 20_INFOCOM_Automatically and Adaptively Identifying Severe Alerts for Online Service Systems [[paper]](https://netman.aiops.org/wp-content/uploads/2020/07/alertrank_camera-ready.pdf)