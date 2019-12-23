---
title: "meProp: Sparsified Back Propagation for Accelerated Deep Learning with Reduced Overfitting"
date: 2017-08-06
publishDate: 2019-12-23T08:04:30.047125Z
authors: ["Xu Sun", "**Xuancheng Ren**", "Shuming Ma", "Houfeng Wang"]
publication_types: ["1"]
abstract: "We propose a simple yet effective technique for neural network learning. The forward propagation is computed as usual. In back propagation, only a small subset of the full gradient is computed to update the model parameters. The gradient vectors are sparsified in such a way that only the top-k elements (in terms of magnitude) are kept. As a result, only k rows or columns (depending on the layout) of the weight matrix are modified, leading to a linear reduction (k divided by the vector dimension) in the computational cost. Surprisingly, experimental results demonstrate that we can update only 1–4% of the weights at each back propagation pass. This does not result in a larger number of training iterations. More interestingly, the accuracy of the resulting models is actually improved rather than degraded, and a detailed analysis is given."
featured: true
publication: "*Proceedings of the 34th International Conference on Machine Learning, **ICML 2017***"
publication_short: "**ICML 2017**"
url_pdf: "http://proceedings.mlr.press/v70/sun17c.html"
url_arxiv: "http://arxiv.org/abs/1706.06197"
url_code: "https://github.com/lancopku/meProp"

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  caption: "An illustration of meProp."
  focal_point: "Smart"
  preview_only: false
---

