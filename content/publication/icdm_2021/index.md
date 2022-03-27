---
title: "Source Inference Attacks in Federated Learning"
# date: 2021-06-11
publishDate: 2021-12-07
authors:
- admin
- Zoran Salcic
- Lichao Sun
- Gillian Dobbie
- Xuyun Zhang
publication_types: 
- "1"
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false
abstract: "Federated learning (FL) has emerged as a promising privacy-aware paradigm that allows multiple clients to jointly train a model without sharing their private data. Recently, many studies have shown that FL is vulnerable to membership inference attacks (MIAs) that can distinguish the training members of the given model from the non-members. However, existing MIAs ignore the source of a training member, i.e., the information of the client owning the training member, while it is essential to explore source privacy in FL beyond membership privacy of examples from all clients. The leakage of source information can lead to severe privacy issues. For example, identification of the hospital contributing to the training of an FL model for the COVID-19 pandemic can render the owner of a data record from this hospital more prone to discrimination if the hospital is in a high risk region. In this paper, we propose a new inference attack called source inference attack (SIA), which can derive an optimal estimation of the source of a training member. Specifically, we innovatively adopt the Bayesian perspective to demonstrate that an honest-but-curious server can launch an SIA to steal non-trivial source information of the training members without violating the FL protocol. The server leverages the prediction loss of local models on the training members to achieve the attack effectively and non-intrusively. We conduct extensive experiments on one synthetic and five real datasets to evaluate the key factors in an SIA, and the results show the efficacy of the proposed source inference attack."
publication: "*2021 IEEE International Conference on Data Mining (ICDM)*"
url_pdf: "https://ieeexplore.ieee.org/abstract/document/9679121"
url_code: "https://github.com/HongshengHu/source-inference-FL"
---
