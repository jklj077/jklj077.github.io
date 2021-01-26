---
title: "Prophet Attention: Predicting Attention with Future Attention for Improved Image Captioning"
date: 2020-12-07
publishDate: 2020-09-26T08:04:29.940124Z
authors: ["Fenglin Liu", "admin", "Xian Wu", "Shen Ge", "Wei Fan", "Yuexian Zou", "Xu Sun"]
publication_types: ["1"]
abstract: "Recently, attention based models have been used extensively in image captioning and are expected to ground correct image regions with proper generated words. However, for each time step in the decoding process, the attention based models usually use the hidden state of current input to attend to the image regions. Under this setting, these attention models have a “deviated focus” problem, that they calculate the attention weights based on previous words instead of the one to be generated, impairing the performance of both grounding and captioning. In this paper, we propose the Prophet Attention, similar to the form of self-supervision. In the training stage, this module utilizes the future information to calculate the “ideal” attention weights towards image regions. These calculated weights are further used to regularize the “deviated” attention. In this manner, image regions are grounded with the correct words. Prophet Attention does not introduce additional model parameters or inference computations, making it easily incorporated into any existing systems. The experiments on the Flickr30k Entities and MSCOCO datasets show that the proposed Prophet Attention consistently outperforms baselines in both automatic metrics and human evaluations. It is worth noticing that we set new state-of-the-arts on the two benchmark datasets and achieve the 1st place on the leaderboard of the online MSCOCO benchmark."
featured: false
publication: "*Advances in Neural Information Processing Systems 33, **NeurIPS 2020** (to appear)*"
publication_short: "**NeurIPS 2020** (to appear)"
---

