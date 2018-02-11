---
layout: post
title:  "test"
date:   2018-02-10
desc: "The framework of Auto-encoder"
keywords: "Auto-encoder"
categories: [machinelearning]
tags: [Auto-encoder]
icon: icon-machine-learning
---

<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-black.css">

<!-- img_path: /YouYueHuang.github.io/static/assets/img/blog  -->

<div class="w3-twothird w3-container">
  <h1 class="w3-text-teal">Autoencoder</h1>
  <img src="{{ site.img_path }}/blog_machine_learning/Autoencoding.png" width="100%">
  <p>Autoencoding(AE) is an automatic data compression and decompression algorithm. In machine learning, it belongs to unsupervised learning. Both PCA and autoencoder can do dimension reduction and make the information lossy. PCA is maion used for finding low dimension representations, and it only uses linear operations as opposed to autoencoding. Autoencoding can have nonlinear enoder/decoders.
  </p>
  <p> If no non-linear function is used in the AE and the number of neurons in the hidden layer is of smaller dimension then that of the input then PCA and AE can yield the same result. Otherwise the AE may find a different subspace. If the dimension of hidden layer is 2, it can be used for visualization. 
  </p>
  <p>
  The hidden layer in an AE can be of greater dimensionality than that of the input. In such cases AE's may not be doing dimensionality reduction. Instead, we perceive them as doing a transformation from one feature space to the new feature space which might disentangle factors of variation. 
  </p>
  <p>  A single layer auto-encoder with linear transfer function is nearly equivalent to PCA, where "nearly" means that the W found by AE and PCA won't be the same--but the subspace spanned by the respective W's will. Hidden layer might memorize the original input. One solution is to apply L2 regularizer to the output of hidden layer. If the hidden unit is far from 0 after activation, that means the unit can recognize the input. The activated units of these input can be regarded as the units which own te capability of processing those signals.
  </p>
  <p> When training a good neural network, one of the challenges is to find a good sets of parameters for initialization. Autoencoder can do pretraining to memorize the layer-wise features as the input of the neural network.
  </p>
  <p>Autoencoders are data-specific, so it is hard to generalize them. That makes it impractical for real-world data compression problems unless data is similar or large amount of real-world data was trained.
  </p>
  <h1 class="w3-text-teal">Autoencoder for convolutional neural network</h1>
  <img src="{{ site.img_path }}/blog_machine_learning/Autoencoder_for_convolutional_neural_network.png" width="100%">
  
  <p>
  Application: image search: find similar images, text retrieval: retrieve relevant document based on query, audio compression. 
  </p>
</div>
