---
title: "An encoder-decoder ConvLSTM surrogate model for simulating geological CO2 sequestration with dynamic well controls"
collection: publications
category: manuscripts
permalink: /publication/ED-ConvLSTM
excerpt: ''
date: 2024/5/1
venue: 'Gas Science and Engineering'
paperurl: 'https://doi.org/10.1016/j.jgsce.2024.205314'
codeurl: 'https://github.com/fengzhao1239/ED-ConvLSTM'
---
**Abstract:**
In Geological Carbon Sequestration (GCS), effectively managing the project requires predicting state variables such as pressure and saturation. However, numerical simulation of multiphase flow in subsurface porous media involves solving large linear algebra systems, resulting in a substantial computational burden. This can make it impractical for real-time history matching or optimization. Meanwhile, deep learning-based surrogate models are emerging as fast and accurate approximators. This study delves into the application of the Encoder-Decoder Convolutional Long Short-Term Memory (ED-ConvLSTM) neural network for predicting the complex evolution of state variables under dynamic CO2 injection schemes. Inception blocks enhanced with light-weighted attention modules are introduced in the encoder to extract high-dimensional input features. ConvLSTM is employed to propagate spatial temporal information in the low-dimensional latent space. Further, progressive upsampling blocks are used to reconstruct the latent features for the desired output. Instead of taking discrete time steps as an input feature, the proposed network captures the dynamic dependencies with the inherent ConvLSTM cell. The network has access to data at only portion of the initial time steps during training stage, while it is used to predict the state variables at unseen time steps during testing stage. Results show that the network can produce excellent predictions for both pressure and saturation, even at unseen future time steps. The remarkable generalizability to different geological permeability fields is also evaluated. ED-ConvLSTM outperforms the standard U-Net by far, especially when predicting beyond the training time period. These numerical experiments demonstrate the advantages of ED-ConvLSTM in terms of prediction accuracy, extrapolability and generalizability. This study highlights the importance of incorporating recurrent connections into the deep neural networks for simulating time-dependent multiphase flow problems. The proposed methodology has great potential in GCS surrogate modeling and offers a possible approach for real-time optimization of CO2 injection.
