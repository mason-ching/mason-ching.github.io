---
title: "IB-AdCSCNet: Adaptive Convolutional Sparse Coding Network Driven by Information Bottleneck"
collection: publications
category: preprint
# permalink: /publications/2024-05-23-IBAdCSCNet
excerpt: |
    <div style="display: flex; align-items: center; width: 97%;">
        <img src='/files/papers/IB-AdCSCNet/IB-AdCSCNet.png' style="max-width: 300px; margin-right: 10px;">
        <p style="font-size: 16px; margin: 5px 0 0 20px; margin-left: 0px; color: #666; text-align: justify;">
            In neural network models, the perpetual challenge remains in retaining task-relevant information while effectively discarding redundant data during propagation. In this paper, we introduce IB-AdCSCNet, a deep learning model grounded in information bottleneck theory. IB-AdCSCNet seamlessly integrates the information bottleneck trade-off strategy into deep networks, and dynamically adjusts the trade-off hyperparameter λ by FISTA algorithm. By optimizing the compressive excitation loss induced by the information bottleneck principle, IB-AdCSCNet achieves an optimal balance between compression and fitting at a global level, approximating the globally optimal representation feature. This information bottleneck trade-off strategy driven by downstream tasks not only helps to learn effective features of the input data, but also improves the generalization of deep models. Experimental results on CIFAR-10 and CIFAR-100 demonstrate that IB-AdCSCNet not only matches the performance of deep residual convolutional networks but also outperforms them when handling corrupted data. Through the inference of the IB trade-off, the model’s robustness is notably enhanced.
        </p>
    </div>
date: 2024-05-23
# prefix-venue: 'In'
venue: 'arXiv:2405.14192'
authors: "He Zou, Meng'en Qin, Yu Song, Xiaohui Yang (corresponding author)."
# slidesurl: ''
paperurl: 'https://arxiv.org/pdf/2405.14192'
# code: ''
bibtexurl: 'http://mason-ching.github.io/files/papers/IB-AdCSCNet/IB-AdCSCNet.bib'
# APA format
# citation: 'Zou, H., Qin, M. E., Song, Y., & Yang, X. (2024). &quot;IB-AdCSCNet: Adaptive Convolutional Sparse Coding Network Driven by Information Bottleneck.&quot; <i>arXiv preprint</i> arXiv:2405.14192.'
---