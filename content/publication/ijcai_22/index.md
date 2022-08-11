---
title: "Membership Inference via Backdooring"
# date: 2021-3-14
publishDate: 2022-03-25
authors:
- admin
- Zoran Salcic
- Gillian Dobbie
- Jinjun Chen
- Lichao Sun
- Xuyun Zhang
publication_types: ["1"]
abstract: "Recently issued data privacy regulations like GDPR (General Data Protection Regulation) grant individuals the right to be forgotten. In the context of machine learning, this requires a model to forget about a training data sample if requested by the data owner (i.e., machine unlearning). As an essential step prior to machine unlearning, it is still a challenge for a data owner to tell whether or not her data have been used by an unauthorized party to train a machine learning model. Membership inference is a recently emerging technique to identify whether a data sample was used to train a target model, and seems to be a promising solution to this challenge. However, straightforward adoption of existing membership inference approaches fails to address the challenge effectively due to being originally designed for attacking membership privacy and suffering from several severe limitations such as low inference accuracy on well-generalized models. In this paper, we propose a novel membership inference approach inspired by the backdoor technology to address the said challenge. Specifically, our approach of Membership Inference via Backdooring (MIB) leverages the key observation that a backdoored model behaves very differently from a clean model when predicting on deliberately marked samples created by a data owner. Appealingly, MIB requires data owners' marking a small number of samples for membership inference and only black-box access to the target model, with theoretical guarantees for inference results. We perform extensive experiments on various datasets and deep neural network architectures, and the results validate the efficacy of our approach, e.g., marking only 0.1% of the training dataset is practically sufficient for effective membership inference."
featured: false
image:
  preview_only: false
publication: "*2022 International Joint Conference on Artificial Intelligence*"
url_pdf: "https://www.ijcai.org/proceedings/2022/0532.pdf"
url_code: "https://github.com/HongshengHu/membership-inference-via-backdooring"
---
