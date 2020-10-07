---
title: "RNNPool: Efficient Non-linear Pooling for RAM Constrained Inference"
collection: publications
permalink: /publication/rnnpool
excerpt: 'Standard Convolutional Neural Networks (CNNs) designed for computer vision
tasks tend to have large intermediate activation maps which require large work3 ing RAM which makes them unsuitable for deployment on resource-constrained
processors typically used for inference on the edge. Downsampling the images
via pooling or strided convolutions can address the problem, but when used inde6 pendently, such methods can significantly lower accuracy as the standard pooling
operators reduce feature size via gross aggregation. In this paper, we introduce
RNNPool, a novel pooling operator based on Recurrent Neural Networks (RNNs),
that efficiently aggregates features over large patches of an image and rapidly
downsamples activation maps. Empirical evaluation indicates that an RNNPool
layer can effectively replace multiple blocks in a variety of architectures such as
MobileNets, DenseNet and can be used for several vision tasks like image
classification and face detection. That is, RNNPool can significantly decrease
computational complexity and peak memory usage for inference while retaining
comparable accuracy. We use RNNPool with the standard S3FD architecture
to construct a face detection method that achieves state-of-the-art MAP for tiny
Cortex-M4 class devices with under 256 KB of RAM.'
date: 2020-09-30
venue: 'Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://arxiv.org/pdf/2002.11921.pdf'
---
