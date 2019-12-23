---
title: "A Hierarchical Reinforced Sequence Operation Method for Unsupervised Text Style Transfer"
date: 2019-08-02
publishDate: 2019-12-23T08:04:29.921124Z
authors: ["Chen Wu*", "**Xuancheng Ren***", "Fuli Luo", "Xu Sun"]
publication_types: ["1"]
abstract: "Unsupervised text style transfer aims to alter text styles while preserving the content, without aligned data for supervision. Existing seq2seq methods face three challenges: 1) the transfer is weakly interpretable, 2) generated outputs struggle in content preservation, and 3) the trade-off between content and style is intractable. To address these challenges, we propose a hierarchical reinforced sequence operation method, named Point-Then-Operate (PTO), which consists of a high-level agent that proposes operation positions and a low-level agent that alters the sentence. We provide comprehensive training objectives to control the fluency, style, and content of the outputs and a mask-based inference algorithm that allows for multi-step revision based on the single-step trained agents. Experimental results on two text style transfer datasets show that our method significantly outperforms recent methods and effectively addresses the aforementioned challenges."
featured: true
publication: "*Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, **ACL 2019***, Volume 1: Long Papers"
publication_short: "**ACL 2019**"
url_pdf: "https://www.aclweb.org/anthology/P19-1482/"
url_code: "https://github.com/lancopku/Point-Then-Operate"
url_arxiv: "https://arxiv.org/abs/1906.01833"
doi: "10.18653/v1/P19-1482"

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  caption: "Our proposed Point-Then-Operate (PTO) applied to a real test sample. A high-level agent (red squares) iteratively proposes operation positions, and a low-level agent (arrows) alters the sentence based on the high-level proposals. Compared with seq2seq methods, PTO is more interpretable and better preserves style-independent contents."
  focal_point: "Smart"
  preview_only: false
---

