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
- 20_IWQoS_Localizing Failure Root Causes in a Microservice through Causality Inference [[paper]](https://ieeexplore.ieee.org/document/9213058)
- 20_NOMS_MicroRCA: Root Cause Localization of Performance Issues in Microservices [[paper]](https://ieeexplore.ieee.org/document/9110353) [[code]](https://github.com/elastisys/MicroRCA)
- 18_ICSOC_Microscope: Pinpoint Performance Issues with Causal Graphs in Micro-service Environments [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-03596-9_1)
- 14_NSDI_Adtributor: Revenue Debugging in Advertising Systems [[paper]](https://www.usenix.org/system/files/conference/nsdi14/nsdi14-paper-bhagwan.pdf)

## Log

- 21_ISSTA_Faster, Deeper, Easier: Crowdsourcing Diagnosis of Microservice Kernel Failure from User Space [[paper]](https://dl.acm.org/doi/abs/10.1145/3460319.3464805) [[code]](https://github.com/PanYicheng/dycause_rca)
- 20_ICSE-SEIP_DeCaf: Diagnosing and Triaging Performance Issues in Large-Scale Cloud Services [[paper]](https://dl.acm.org/doi/pdf/10.1145/3377813.3381353) [[code]](https://github.com/SEALABQualityGroup/replication_delag/blob/main/techniques/decaf/decaf.py)
- 19_ICSE_Mining Historical Test Logs to Predict Bugs and Localize Faults in the Test Logs [[paper]](https://dl.acm.org/doi/pdf/10.1109/ICSE.2019.00031)
- Identifying Impactful Service System Problems via Log Analysis [[paper]](https://dl.acm.org/doi/10.1145/3236024.3236083) [code](https://github.com/logpai/Log3C)
- 18_ESEM_Spectrum-Based Log Diagnosis [[paper]](https://dl.acm.org/doi/pdf/10.1145/3382494.3410684)
- 14_Cluster_Digging Deeper into Cluster System Logs for Failure Prediction and Root Cause Diagnosis [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6968768)
  

## Trace

- 22_ESE_Enjoy your observability: an industrial survey of microservice tracing and analysis [[paper]](https://link.springer.com/article/10.1007/s10664-021-10063-9) 
- 21_Usenix ATC_Argus: Debugging Performance Issues in Modern Desktop Applications with Annotated Causal Tracing [[paper]](https://www.usenix.org/system/files/atc21-weng.pdf) [[code]](https://github.com/columbia/ArgusDebugger) Awarded Best Paper! 👍
- 21_WWW_MicroRank: End-to-End Latency Issue Localization with Extended Spectrum Analysis in Microservice Environments [[paper]](https://dl.acm.org/doi/10.1145/3442381.3449905) [[code]](https://github.com/IntelligentDDS/MicroRank)
- 21_JSEP_TraceRank: Abnormal service localization with dis‐aggregated end‐to‐end tracing data in cloud native systems [[paper]](https://onlinelibrary.wiley.com/doi/full/10.1002/smr.2413)
- 20_CCGrid_T-Rank:A Lightweight Spectrum based Fault Localization Approach for Microservice Systems [[paper]](https://ieeexplore.ieee.org/abstract/document/9499404)
- 18_Asplos_FCatch: Automatically Detecting Time-of-fault Bugs in Cloud Systems [[paper]](https://dl.acm.org/doi/10.1145/3296957.3177161)
- 18_ATC_Troubleshooting Transiently-Recurring Problems in Production Systems with Blame-Proportional Logging [[paper]](https://www.usenix.org/conference/atc18/presentation/luo)
- 14_OSDI_The Mystery Machine: End-to-end performance analysis of large-scale Internet services [[paper]](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-chow.pdf)

## Metric and Trace
- 21_ASPLOS_Sage: Practical & Scalable ML-Driven Performance Debugging in Microservices [[paper]](https://www.csl.cornell.edu/~delimitrou/papers/2021.asplos.sage.pdf)

## Metric, Log and Trace
- 22_ICSE_PerfSig: Extracting Performance Bug Signatures via Multi-modality Causal Analysis [[paper]](https://jhe16.github.io/files/ICSE22.pdf) [[code]](https://github.com/jhe16/PerfSig)
- 20_ESOCC_Multi-source Distributed System Data for AI-Powered Analytics [[paper]](https://link.springer.com/content/pdf/10.1007/978-3-030-44769-4_13.pdf) [[[data]](https://zenodo.org/record/3549604#.YkJeszNBy3I) [[code]](https://github.com/snedelkoski/multi-source-observability-dataset)

## Network
- 20_Sigcomm_Microscope: Queue-based Performance Diagnosis for Network Functions [[paper]](https://dl.acm.org/doi/pdf/10.1145/3387514.3405876)

## Alert
- 20_Infocom_Automatically and Adaptively Identifying Severe Alerts for Online Service Systems [[paper]](https://netman.aiops.org/wp-content/uploads/2020/07/alertrank_camera-ready.pdf)