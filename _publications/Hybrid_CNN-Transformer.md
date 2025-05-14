---
title: "A Hybrid CNN-Transformer Surrogate Model for the Multi-Objective Robust Optimization of Geological Carbon Sequestration"
collection: publications
category: manuscripts
permalink: /publication/Hybrid_CNN-Transformer
excerpt: 'In this paper, we propose a hybrid CNN-Transformer surrogate model to accelerate the well control optimization in GCS applications. Pareto optimal well controls are determined based on Non-dominated Sorting-based Genetic Algorithm II (NSGA-II)'
date: 2025/1/17
venue: 'Advances in Water Resources'
paperurl: '/assets/files/CNN-Transformer_paper.pdf'
citation: 'Feng, Z., Yan, B., Shen, X., Zhang, F., Tariq, Z., Ouyang, W., & Han, Z. (2025). A Hybrid CNN-Transformer Surrogate Model for the Multi-Objective Robust Optimization of Geological Carbon Sequestration. Advances in Water Resources, 104897.'
---
## :page_facing_up: **Abstract:**  
The optimization of well controls over time constitutes an essential step in the design of cost-effective and safe geological carbon sequestration (GCS) projects. However, the computational expense of these optimization problems, due to the extensive number of simulation evaluations, presents significant challenges for real-time decision-making. In this paper, we propose a hybrid CNN-Transformer surrogate model to accelerate the well control optimization in GCS applications. The surrogate model encompasses a Convolution Neural Network (CNN) encoder to compress high-dimensional geological parameters, a Transformer processor to learn global patterns inherent in the well controls over time, and a CNN decoder to map the latent variables to the target solution variables. The surrogate model is trained to predict the spatiotemporal evolution of CO2 saturation and pressure within 3D heterogeneous permeability fields under dynamic CO2 injection rates. Results demonstrate that the surrogate model exhibits satisfactory performance in the context of prediction accuracy, computation efficiency, data scalability, and out-of-distribution generalizability. The surrogate model is further integrated with Multi-Objective Robust Optimization (MORO). Pareto optimal well controls are determined based on Non-dominated Sorting-based Genetic Algorithm II (NSGA-II), which maximize the storage efficiency and minimize the induced over-pressurization across an ensemble of uncertain geological realizations. The surrogate-based MORO reduces computational time by 99.99 % compared to simulation-based optimization. The proposed workflow not only highlights the feasibility of applying the CNN-Transformer model for complex subsurface flow systems but also provides a practical solution for real-time decision-making in GCS projects.  

<figure>
  <img src="/assets/images/CNN-Transformer_net.png" alt="My figure" style="width:80%">
  <figcaption style="text-align:center; font-size:90%;">Neural Network Architecture</figcaption>
</figure>

<figure>
  <img src="/assets/images/MORO_framework.png" alt="My figure" style="width:80%">
  <figcaption style="text-align:center; font-size:90%;">Multi-Objective Robust Optimization Framework</figcaption>
</figure>


## :computer: **Code:** [github](https://github.com/fengzhao1239/CNN-Transformer)