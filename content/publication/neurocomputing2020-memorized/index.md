---
title: "Memorized Sparse Backpropagation"
date: 2020-11-20
publishDate: 2020-09-26T08:04:30.047125Z
authors: ["Zhiyuan Zhang", "Pengcheng Yang", "**Xuancheng Ren**", "Qi Su", "Xu Sun"]
publication_types: ["2"]
abstract: "Neural network learning is usually time-consuming since backpropagation needs to compute full gradients and backpropagate them across multiple layers. Despite its success of existing works in accelerating propagation through sparseness, the relevant theoretical characteristics remain under-researched and empirical studies found that they suffer from the loss of information contained in unpropagated gradients. To tackle these problems, this paper presents a unified sparse backpropagation framework and provides a detailed analysis of its theoretical characteristics. Analysis reveals that when applied to a multilayer perceptron, our framework essentially performs gradient descent using an estimated gradient similar enough to the true gradient, resulting in convergence in probability under certain conditions. Furthermore, a simple yet effective algorithm named memorized sparse backpropagation (MSBP) is proposed to remedy the problem of information loss by storing unpropagated gradients in memory for learning in the next steps. Experimental results demonstrate that the proposed MSBP is effective to alleviate the information loss in traditional sparse backpropagation while achieving comparable acceleration."
featured: false
publication: "*Neurocomputing*"
publication_short: "**Neurocomputing** 415"
url_pdf: "https://doi.org/10.1016/j.neucom.2020.08.055"
url_arxiv: "https://arxiv.org/abs/1905.10194"
doi: "10.1016/j.neucom.2020.08.055"
---

