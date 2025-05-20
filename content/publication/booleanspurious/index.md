---
abstract: Existing research often posits spurious features as easier to learn than core features in neural network optimization, but the impact of their relative simplicity remains under-explored. Moreover, studies mainly focus on end performance rather than the learning dynamics of feature learning. In this paper, we propose a theoretical framework and an associated synthetic dataset grounded in boolean function analysis. This setup allows for fine-grained control over the relative complexity (compared to core features) and correlation strength (with respect to the label) of spurious features to study the dynamics of feature learning under spurious correlations. Our findings uncover several interesting phenomena (1) stronger spurious correlations or simpler spurious features slow down the learning rate of the core features, (2) two distinct subnetworks are formed to learn core and spurious features separately, (3) learning phases of spurious and core features are not always separable, (4) spurious features are not forgotten even after core features are fully learned. We demonstrate that our findings justify the success of retraining the last layer to remove spurious correlation and also identifies limitations of popular debiasing algorithms that exploit early learning of spurious features. We support our empirical findings with theoretical analyses for the case of learning XOR features with a one-hidden-layer ReLU network.

authors:
- Guanwen Qiu
- Da Kuang
- Surbhi Goel
# date: "2013-07-01T00:00:00Z"
image: 
  preview_only: false
  filename: "featured.jpg"
publication: ICML
publication_short: In *ICW*
publication_types:
- paper-conference
publishDate: "2024-01-01T00:00:00Z"
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
title: Complexity Matters - Dynamics of Feature Learning in the Presence of Spurious Correlations
# url_code: https://github.com/HugoBlox/hugo-blox-builder
# url_dataset: https://github.com/HugoBlox/hugo-blox-builder
url_pdf: "https://arxiv.org/abs/2403.03375"
url_poster: ""
url_project: ""
url_slides: ""
---