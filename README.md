# Awesome-GNN-Research

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/XunKaiLi/Awesome-GNN-Research)

# 1. Scalable GNN

- ICML 2019 Simplifying Graph Convolutional Networks [[Paper](https://arxiv.org/abs/1902.07153v1)] [[Code](https://github.com/Tiiiger/SGC)] [[Link](https://zhuanlan.zhihu.com/p/411236675)]
- ICLR 2019 Predict Then Propagate: Graph Neural Networks Meet Personalized PageRank [[Paper](https://arxiv.org/abs/1810.05997v5)] [[Code](https://github.com/benedekrozemberczki/APPNP)] [[Link](https://zhuanlan.zhihu.com/p/419843669)]
- Arxiv 2021 Graph Attention Multi-Layer Perceptron [[Paper](https://arxiv.org/abs/2108.10097)] [[Code](https://github.com/PKU-DAIR/GAMLP)] [[Link](https://zhuanlan.zhihu.com/p/426485085)]

- NIPS 2017 Inductive Representation Learning on Large Graphs [[Paper](https://arxiv.org/abs/1706.02216v2)] [[Code](https://github.com/williamleif/GraphSAGE)] [[Link](https://zhuanlan.zhihu.com/p/411612848)]

- ICLR 2018 FASTGCN: Fast Learning With Graph Convolutional Networks Via Importance Sampling [[Paper](https://arxiv.org/abs/1801.10247)] [[Code](https://github.com/matenure/FastGCN)] [[Link](https://zhuanlan.zhihu.com/p/412020874)]

- KDD 2014 DeepWalk: Online Learning of Social Representations [[Paper](https://arxiv.org/abs/1403.6652)] [[Code](https://github.com/phanein/deepwalk)] [[Link](https://zhuanlan.zhihu.com/p/412713441)]
- WWW 2015 LINE: Large-scale Information Network Embedding [[Paper](https://arxiv.org/abs/1503.03578)] [[Code](https://github.com/snowkylin/line)] [[Link](https://zhuanlan.zhihu.com/p/412787557)]
- KDD 2016 node2vec: Scalable Feature Learning for Networks [[Paper](https://arxiv.org/abs/1607.00653)] [[Code](https://github.com/eliorc/node2vec)] [[Link](https://zhuanlan.zhihu.com/p/413046898)]
- NIPS 2013  Distributed Representations of Words and Phrases and their Compositionality [[Paper](https://arxiv.org/abs/1310.4546)] [[Code](https://github.com/brijml/mikolov_word2vec)] [[Link](https://zhuanlan.zhihu.com/p/413169135)]
- KDD 2016 Structural Deep Network Embedding [[Paper](http://www.kdd.org/kdd2016/papers/files/rfp0191-wangAemb.pdf)] [[Code](https://github.com/suanrong/SDNE)] [[Link](https://zhuanlan.zhihu.com/p/413468532)]

# 2. GNN + (Local) Differential Privacy

## 2.1 Overview and Survey

- introduction [[Link](https://zhuanlan.zhihu.com/p/416264898)]
- Local Differential Privacy: a tutorial [[Paper](https://arxiv.org/abs/1907.11908)] [[Link](https://zhuanlan.zhihu.com/p/416556008)]
- 本地化差分隐私研究综述 [[Paper](https://wenku.baidu.com/view/ca901cf8876fb84ae45c3b3567ec102de3bddf84?fr=xueshu)] [[Link](https://zhuanlan.zhihu.com/p/417209747)]
- 差分隐私 -- Laplace mechanism、Gaussian mechanism、Composition theorem [[Link](https://zhuanlan.zhihu.com/p/425732159)]
- 矩母函数 GMF 及矩的概念 -- 期望、方差、归一化矩、偏态、峰度 [[Link](https://zhuanlan.zhihu.com/p/425898950)] [[Reference](https://towardsdatascience.com/moment-generating-function-explained-27821a739035)]
- Moments Accountant 的理解 [[Link](https://zhuanlan.zhihu.com/p/425780267)] [[Reference](https://zhuanlan.zhihu.com/p/264779199)]
- 基于 GNN 的隐私计算（差分隐私）Review（一）[[Link](https://zhuanlan.zhihu.com/p/426267637)]

## 2.2 Important Algorithms (Principles and Framework)

- SIGSAC 2016 Deep Learning with Differential Privacy [[Paper](https://arxiv.org/abs/1607.00133v1)] [[Code](https://github.com/lingyunhao/Deep-Learning-with-Differential-Privacy)] [[Link](https://zhuanlan.zhihu.com/p/419216660)]
- ICLR 2017 Semi-supervised Knowledge Transfer for Deep Learning from Private Training Data [[Paper](https://arxiv.org/abs/1610.05755)] [[Code](https://github.com/kamathhrishi/PATE)] [[Link](https://zhuanlan.zhihu.com/p/423009101)]
- ICLR 2018 Scalable Private Learning With PATE [[Paper](https://arxiv.org/abs/1802.08908)] [[Code](https://github.com/kamathhrishi/PATE)] [[Link](https://zhuanlan.zhihu.com/p/423063552)]

## 2.3 DP with Generative Model (Graph Generation)

- IJCAI 2021 Secure Deep Graph Generation with Link Differential Privacy [[Paper](https://arxiv.org/abs/2005.00455v3)] [[Code](https://github.com/haonan3/Secure-Network-Release-with-Link-Privacy)] [[Link](https://zhuanlan.zhihu.com/p/417555475)]

## 2.4 DP/LDP with Graph representation learning

- CCS 2021 Locally Private Graph Neural Networks [[Paper](https://arxiv.org/pdf/2006.05535.pdf)] [[Code](https://github.com/sisaman/LPGNN)] [[Link](https://zhuanlan.zhihu.com/p/423444455)]
- Arxiv 2020  When Differential Privacy Meets Graph Neural Networks [[Paper](https://arxiv.org/pdf/2006.05535v1.pdf)]  [[Code](https://github.com/sisaman/LPGNN)]  [[Link](https://zhuanlan.zhihu.com/p/423868946)]
- Arxiv 2021 Releasing Graph Neural Networks with Differential Privacy [[Paper](https://arxiv.org/abs/2109.08907)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/424463019)]

# 3. Federated Learning Based on GNN 

## 3.1 Overview and Survey

- 联邦学习综述：Federated Machine Learning: Concept and Applications [[Paper](https://arxiv.org/abs/1902.04885)] [[Link](https://zhuanlan.zhihu.com/p/427770121)]

## 3.2 Important Algorithms (Principles and Framework)

- 论文笔记：JMLR 2017 Communication-Efficient Learning of Deep Networks from Decentralized Data [[Paper](http://proceedings.mlr.press/v54/mcmahan17a/mcmahan17a.pdf)] [[Code](https://github.com/AshwinRJ/Federated-Learning-PyTorch)] [[Link](https://zhuanlan.zhihu.com/p/429370255)]

## 3.3 FL Based on GNN for Privacy-Preserving

- 论文笔记：Big Data 2019 SGNN: A Graph Neural Network Based Federated Learning Approach by Hiding Structure [[Paper](https://ieeexplore.ieee.org/abstract/document/9005983)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/430953193)] 
- 论文笔记：Arxiv 2021 Vertically Federated Graph Neural Network for Privacy-Preserving Node Classification [[Paper](https://arxiv.org/abs/2005.11903)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/428406637)]
- 论文笔记：ICML 2021 FedGNN: Federated Graph Neural Network for Privacy-Preserving Recommendation [[Paper](https://arxiv.org/abs/2102.04925)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/428783383)]
- 论文笔记：Arxiv 2021 FedGL: Federated Graph Learning Framework with Global Self-Supervision [[Paper](https://arxiv.org/abs/2105.03170)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/431049080)]
- 论文笔记：PPNA 2021 ASFGNN: Automated Separated-Federated Graph Neural Network [[Paper](https://arxiv.org/abs/2011.03248)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/431283541)]

## 3.4 FL Based on GNN (Graphs)

- 论文笔记：IJCAI 2021 Decentralized Federated Graph Neural Networks [[Paper](https://federated-learning.org/fl-ijcai-2021/FTL-IJCAI21_paper_20.pdf)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/430508567)]
- 论文笔记：NIPS 2021 Federated Graph Classification over Non-IID Graphs [[Paper](https://arxiv.org/abs/2106.13423)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/430623053)]
- 论文笔记：ICML 2021 SpreadGNN: Serverless Multi task Federated Learning for Graph Neural Networks [[Paper](https://arxiv.org/abs/2106.02743)] [[Code](https://github.com/FedML-AI/SpreadGNN)] [[Link](https://zhuanlan.zhihu.com/p/429720860)]
- 论文笔记：NIPS 2021 Subgraph Federated Learning with Missing Neighbor Generation [[Paper](https://arxiv.org/abs/2106.13430)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/430789355)]
- 论文笔记：ICML 2021 Personalized Federated Learning using Hypernetworks [[Paper](https://arxiv.org/abs/2103.04628)] [[Code](https://github.com/AvivSham/pFedHN)] [[Link](https://zhuanlan.zhihu.com/p/431130945)]
- 论文笔记：Arxiv 2020 GraphFL: A Federated Learning Framework for Semi-Supervised Node Classification on Graphs [[Paper](https://arxiv.org/abs/2012.04187)] [No Code] [[Link](https://zhuanlan.zhihu.com/p/431479904)]

## 3.5 FL Sys on Graph

- 论文笔记：ICLR 2021 FedGraphNN: A Federated Learning Benchmark System for Graph Neural Networks [[Paper](https://arxiv.org/abs/2104.07145)] [[Code](https://github.com/FedML-AI/FedGraphNN)] [[Link](https://zhuanlan.zhihu.com/p/429220636)]

# 4. GNN library

- Graph library -- PyG、GarphGallery [[Link](https://zhuanlan.zhihu.com/p/420587332)]
- Graph library -- DIG、AutoGL、CogDL [[Link](https://zhuanlan.zhihu.com/p/422082239)]
- PyTorch Geometric（一）：数据加载 [[Link](https://zhuanlan.zhihu.com/p/425974734)]
- PyTorch Geometric（二）：模型搭建 [[Link](https://zhuanlan.zhihu.com/p/427083823)]

