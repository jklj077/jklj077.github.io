---
title: "Towards Easier and Faster Sequence Labeling for Natural Language Processing: A Search-Based Probabilistic Online Learning Framework (SAPO)"
date: 2019-04-01
publishDate: 2019-12-23T08:04:29.914123Z
authors: ["Xu Sun", "Shuming Ma", "Yi Zhang", "**Xuancheng Ren**"]
publication_types: ["2"]
abstract: "There are two major approaches for sequence labeling. One is the probabilistic gradient-based methods such as conditional random fields (CRF) and neural networks (e.g., RNN), which have high accuracy but drawbacks: slow training, and no support of search-based optimization (which is important in many cases). The other is the search-based learning methods such as structured perceptron and margin infused relaxed algorithm (MIRA), which have fast training but also drawbacks: low accuracy, no probabilistic information, and non-convergence in real-world tasks. We propose a novel and “easy” solution, a search-based probabilistic online learning method, to address most of those issues. The method is “easy”, because the optimization algorithm at the training stage is as simple as the decoding algorithm at the test stage. This method searches the output candidates, derives probabilities, and conducts efficient online learning. We show that this method with fast training and theoretical guarantee of convergence, which is easy to implement, can support search-based optimization and obtain top accuracy. Experiments on well-known tasks show that our method has better accuracy than CRF and BiLSTM."
featured: false
publication: "*Information Sciences*"
publication_short: "**Inf. Sci.** 478"
url_pdf: "https://doi.org/10.1016/j.ins.2018.11.025"
url_code: "https://github.com/lancopku/SAPO"
doi: "10.1016/j.ins.2018.11.025"
---

