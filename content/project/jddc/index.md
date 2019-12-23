---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "JDDC 2018"
summary: ""
authors: ["Ruixuan Luo", "Xuancheng Ren", "Junyang Lin", "Jingjing Xu", "Xu Sun"]
tags: []
categories: []
date: 2018-10-31T22:42:45+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

JDDC stands for JD Dialog Challenge, which is a task-oriented multi-turn dialogue challenge in the e-commerce setup. We participated in the 2018 edition of this challenge.

## Highlights

We design a novel system based on mixed response proposal. 
1. A classification module based on fully-connected neural network using bag-of-words is first used to dispatch the coming questions, either for answer retrieving or for answer generation. 
2. For answer retrieving, common questions are directly mapped to the corresponding answer pool and an answer is randomly selected. The answer pool is generated based on the clusterd questions in terms of semantic similarity.
3. For answer generation, other questions are given to a history-based sequence-to-sequence neural network, and a never-before-seen answer is generated based on beam search.

The proposed system works fine for practical purpose:
- It achieves a good balance between speed and accuarcy. Surprisingly, we did not use the related product knowledge but answered most of the questions very well.
- We won the first place in the automatic evaluation and were second to the based in the human evaluation. In addition, we were given the _Architecture Innovation Award_ and the _Excellent Instructor Award_ was given to Prof. Xu Sun.

## Work

I joined the team in the second phase of the competition and was responsible for refining, exploring, and verifying the new system design. Besides, I worked the design/technical documents and presentation slides and particated in the final defense, with Junyang Lin and Ruixuan Luo.