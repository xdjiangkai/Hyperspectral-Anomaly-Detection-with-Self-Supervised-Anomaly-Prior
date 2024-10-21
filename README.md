# Hyperspectral-Anomaly-Detection-with-Self-Supervised-Anomaly-Prior
Hyperspectral Anomaly Detection with Self-Supervised Anomaly Prior

## Abstract
Hyperspectral anomaly detection (HAD) can identify and locate the targets without any known information and is widely applied in Earth observation and military fields. The majority of existing HAD methods use the low-rank representation (LRR) model to separate the background and anomaly through mathematical optimization, in which the anomaly is optimized with a handcrafted sparse prior (e.g., $\ell_{2,1}$-norm). However, this may not be ideal since they overlook the spatial structure present in anomalies and make the detection result largely dependent on manually set sparsity. To tackle these problems, we redefine the optimization criterion for the anomaly in the LRR model with a self-supervised network called self-supervised anomaly prior (SAP). This prior is obtained by the pretext task of self-supervised learning, which is customized to learn the characteristics of hyperspectral anomalies. Specifically, this pretext task is a classification task to distinguish the original hyperspectral image (HSI) and the pseudo-anomaly HSI, where the pseudo-anomaly is generated from the original HSI and designed as a prism with arbitrary polygon bases and arbitrary spectral bands. In addition, a dual-purified strategy is proposed to provide a more refined background representation with an enriched background dictionary, facilitating the separation of anomalies from complex backgrounds. Extensive experiments on various hyperspectral datasets demonstrate that the proposed SAP offers a more accurate and interpretable solution than other advanced HAD methods.

## Citation
```
@misc{liu2024hyperspectralanomalydetectionselfsupervised,
      title={Hyperspectral Anomaly Detection with Self-Supervised Anomaly Prior}, 
      author={Yidan Liu and Weiying Xie and Kai Jiang and Jiaqing Zhang and Yunsong Li and Leyuan Fang},
      year={2024},
      eprint={2404.13342},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2404.13342}, 
}
```
