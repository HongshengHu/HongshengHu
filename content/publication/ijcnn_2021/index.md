---
title: "EAR: An Enhanced Adversarial Regularization Approach against Membership Inference Attacks"
# date: 2021-06-11
publishDate: 2021-09-23
authors:
- admin
- Zoran Salcic
- Gillian Dobbie
- Yi Chen
- Xuyun Zhang
publication_types: 
- "1"
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false
abstract: "Membership inference attacks on a machine learning model aim to determine whether a given data record is a member of the training set. They pose severe privacy risks to individuals, e.g., identifying an individual's participation in a hospital's health analytic training set reveals that this individual was once a patient in that hospital. Adversarial regularization (AR) is one of the state-of-the-art defense methods that mitigate such attacks while preserving a model's prediction accuracy. AR adds membership inference attacks as a new regularization term to the target model during the training process. It is an adversarial training algorithm that is trained on a defended model which is essentially the same as training the generator of generative adversarial networks (GANs). We observe that many GAN variants are able to generate higher quality samples and offer more stability during the training phase than GANs. However, whether these GAN variants are available to improve the effectiveness of AR has not been investigated. In this paper, we propose an enhanced adversarial regularization (EAR) method based on Least Square GANs (LSGANs). The new EAR surpasses the existing AR in offering more powerful defensive ability while preserving the same prediction accuracy of the protected classifiers. We systematically evaluate EAR on five datasets with different target classifiers under four different attack methods and compare it with four other defense methods. We experimentally show that our new method performs the best among other defense methods."
publication: "*2021 International Joint Conference on Neural Networks (IJCNN)*"
url_pdf: "https://ieeexplore.ieee.org/abstract/document/9534381"
---
