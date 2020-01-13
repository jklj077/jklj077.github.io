---
title: "Training Simplification and Model Simplification for Deep Learning: A Minimal Effort Back Propagation Method"
date: 2018-11-27
publishDate: 2019-12-23T08:04:30.047125Z
authors: ["Xu Sun*", "**Xuancheng Ren***", "Shuming Ma", "Bingzhen Wei", "Wei Li", "Jingjing Xu", "Houfeng Wang", "Yi Zhang"]
publication_types: ["2"]
abstract: "We propose a simple yet effective technique to simplify the training and the resulting model of neural networks. In back propagation, only a small subset of the full gradient is computed to update the model parameters. The gradient vectors are sparsified in such a way that only the top-k elements (in terms of magnitude) are kept. As a result, only k rows or columns (depending on the layout) of the weight matrix are modified, leading to a linear reduction in the computational cost. Based on the sparsified gradients, we further simplify the model by eliminating the rows or columns that are seldom updated, which will reduce the computational cost both in the training and decoding, and potentially accelerate decoding in real-world applications. Surprisingly, experimental results demonstrate that most of time we only need to update fewer than 5% of the weights at each back propagation pass. More interestingly, the accuracy of the resulting models is actually improved rather than degraded, and a detailed analysis is given. The model simplification results show that we could adaptively simplify the model which could often be reduced by around 9x, without any loss on accuracy or even with improved accuracy."
featured: true
publication: "*IEEE Transactions on Knowledge and Data Engineering (**TKDE**)*"
publication_short: "**TKDE** 32(2)"
url_pdf: "https://doi.org/10.1109/TKDE.2018.2883613"
url_arxiv: "https://arxiv.org/abs/1711.06528"
url_code: "https://github.com/lancopku/meSimp"
doi: "10.1109/TKDE.2018.2883613"

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  caption: "An illustration of model simplification."
  focal_point: "Smart"
  preview_only: false
---

