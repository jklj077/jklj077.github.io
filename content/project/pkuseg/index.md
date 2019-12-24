---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "PKUSeg"
summary: ""
authors: ["Ruixuan Luo", "Jingjing Xu", "**Xuancheng Ren**", "Yi Zhang", "Bingzhen Wei", "Xu Sun"]
tags: []
categories: []
date: 2019-06-27T22:42:33+08:00

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

url_code: "https://github.com/lancopku/pkuseg-python"
url_pdf: "https://arxiv.org/abs/1906.11455"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

PKUSeg-python is a multi-domain Chinese word segmentation toolkit in Python. There is also a C# version of this toolkit, in which I am not involved.

## Highlights

The toolkit has the following features:

- Supporting multi-domain Chinese word segmentation. PKUSeg-python supports multi-domain segmentation, including domains like news, web, medicine, and tourism. Users are free to choose different pre-trained models according to the domain features of the text to be segmented. If not sure the domain of the text, users are recommended to use the default model trained on mixed-domain data.

- Higher word segmentation results. Compared with existing word segmentation toolkits, pkuseg-python can achieve higher F1 scores on the same dataset.

- Supporting model training. PKUSeg-python  also supports users to train a new segmentation model with their own data.

- Supporting POS tagging. We also provide users POS tagging interfaces for further lexical analysis. 

## Work

I have mainly worked on improving the efficiency and the maintainability of the toolkit:
- Identify the bottleneck of speed
- Rework the core compuation parts with Cython, bringing ~9x speedup
- Refactor the codes and address backward compatibility
