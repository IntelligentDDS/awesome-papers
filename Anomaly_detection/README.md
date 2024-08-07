# Anomaly detetion 

**Content**
- [Anomaly detetion](#anomaly-detetion)
  - [Supervised anomaly detection](#supervised-anomaly-detection)
    - [Log](#log)
    - [Trace](#trace)
    - [Metric](#metric)
  - [Semi-supervised anomaly detection](#semi-supervised-anomaly-detection)
    - [Metric](#metric-1)
    - [Log](#log-1)
  - [Unsupervised anomaly detection](#unsupervised-anomaly-detection)
    - [Metric](#metric-2)
    - [Trace](#trace-1)
    - [Log](#log-2)
    - [Metric and log](#metric-and-log)
  - [Evaluation](#evaluation)

## Supervised anomaly detection

### Log
- 22_TPDS_SwissLog: Robust Anomaly Detection and Localization for Interleaved Unstructured Logs [[paper]](https://ieeexplore.ieee.org/abstract/document/9744513/) [[code]](https://github.com/IntelligentDDS/SwissLog)
- 22_KDD_Augmenting Log-based Anomaly Detection Models to Reduce False Anomalies with Human Feedback [[paper]](https://dl.acm.org/doi/abs/10.1145/3534678.3539106)

### Trace
- 23_WWW_Unsupervised Anomaly Detection on Microservice Traces through Graph VAE [[paper]](https://netman.aiops.org/wp-content/uploads/2023/02/TraceVAE.pdf) 
- 22_ICSE_DeepTraLog: Trace-Log Combined Microservice Anomaly Detection through Graph-based Deep Learning [[paper]](https://cspengxin.github.io/publications/icse22-DeepTraLog.pdf) [[code]](https://fudanselab.github.io/DeepTraLog/)

### Metric
- Detecting Spacecraft Anomalies Using LSTMs and Nonparametric Dynamic Thresholding [[paper]](https://arxiv.org/abs/1802.04431) [[code]](https://github.com/khundman/telemanom)


## Semi-supervised anomaly detection
### Metric
- 22_WWW_A Semi-Supervised VAE Based Active Anomaly Detection Framework in Multivariate Time Series for Online Systems [[paper]](https://dl.acm.org/doi/10.1145/3485447.3511984)
- 20_SIGMOD_Human-in-the-loop Outlier Detection [[paper]](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/sigmod20-outlier.pdf)

### Log
- 21_ICSE_Semi-supervised Log-based Anomaly Detection via Probabilistic Label Estimation [[paper]](https://ieeexplore.ieee.org/document/9401970)

## Unsupervised anomaly detection

### Metric
24_AAAI_High Significant Fault Detection in Azure Core Workload Insights [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/30312)
23_ICDE_DBCatcher: A Cloud Database Online Anomaly Detection System based on Indicator Correlation [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10184680)
23_KDD_AlerTiger: Deep Learning for AI Model Health Monitoring at LinkedIn [[paper]](https://arxiv.org/abs/2306.01977) [[code]](https://github.com/linkedin/AlerTiger/blob/main/alertiger/src/features.py)
- 22_ICWS_TS-InvarNet: Anomaly Detection and Localization based on Tempo-spatial KPI Invariants in Distributed Services [[paper]](https://yuxiaoba.github.io/publication/tsinvarnet22/tsInvarNet22.pdf)
- 21_Sigcomm_A Composition Framework for Change Management [[paper]](https://dl.acm.org/doi/abs/10.1145/3452296.3472901)
- 21_TNNLS_A Spatiotemporal Deep Learning Approach for Unsupervised Anomaly Detection in Cloud Systems [[paper]](https://ieeexplore.ieee.org/document/9228885) [[dataset]](https://github.com/IntelligentDDS/TopoMAD)
- 21_ATC_Jump-Starting Multivariate Time Series Anomaly Detection for Online Service Systems [[paper]](https://www.usenix.org/system/files/atc21-ma.pdf)
- 20_KDD_USAD: UnSupervised Anomaly Detection on Multivariate Time Series [[paper]](https://dl.acm.org/doi/10.1145/3394486.3403392) [[code]]
- 16_ICML_Robust random cut forest based anomaly detection on streams [[paper]](https://proceedings.mlr.press/v48/guha16.pdf) [[code]](https://klabum.github.io/rrcf/)
- 15_CoNEXT_Rapid and Robust Impact Assessment of Software Changes in Large Internet-based Services [[paper]](https://conferences2.sigcomm.org/co-next/2015/img/papers/conext15-final2.pdf)
- 13_CoNEXT_Robust Assessment of Changes in Cellular Networks [[paper]](https://dl.acm.org/doi/abs/10.1145/2535372.2535382)
- 11_Conext_Rapid Detection of Maintenance Induced Changes in Service Performance [[paper]](https://www.cs.utexas.edu/~yzhang/papers/prism-conext11.pdf)
- 10_SIGCOM_Detecting the Performance Impact of Upgrades in Large Operational Networks [[paper]](https://www.cs.utexas.edu/~yzhang/papers/mercury-sigc10.pdf)

### Trace

- 22_FSE_TraceCRL: Contrastive Representation Learning for Microservice Trace Analysis [[paper]](https://dl.acm.org/doi/pdf/10.1145/3540250.3549146) [[code]](https://fudanselab.github.io/TraceCRL/)
- 20_ISSRE_Unsupervised Detection of Microservice Trace Anomalies through Service-Level Deep Bayesian Networks [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9251058) [[code]](https://github.com/NetManAIOps/TraceAnomaly)


### Log
- 22_SIGMOD_Unsupervised Contextual Anomaly Detection for Database Systems [[paper]](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/anomaly-detection-sigmod2022.pdf) [[code]](https://github.com/UCAD3/core.)
- 22_Eurosys_Hybrid Anomaly Detection and Prioritization for Network Logs at Cloud Scale [[paper]](https://dl.acm.org/doi/10.1145/3492321.3519566)
- 21_DSN_Sentiment Analysis based Error Detection for Large-Scale Systems [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9505163)
- 20_NSDI_Gandalf: An Intelligent, End-To-End Analytics Service for Safe Deployment in Large-Scale Cloud Infrastructure [[paper]](https://www.usenix.org/conference/nsdi20/presentation/li)

### Metric and log
- 22_Heterogeneous Anomaly Detection for Software Systems via Attentive Multi-modal Learning [[paper]]()https://arxiv.org/abs/2207.02918
- 21_FSE_Identifying Bad Software Changes via Multimodal Anomaly Detection for Online Service Systems [[paper]](https://dl.acm.org/doi/pdf/10.1145/3468264.3468543) [[code]](https://github.com/FSEwork/SCWarn)


## Evaluation

- 22_AAAI_Towards a Rigorous Evaluation of Time-series Anomaly Detection [[paper](https://arxiv.org/pdf/2109.05257.pdf)]

