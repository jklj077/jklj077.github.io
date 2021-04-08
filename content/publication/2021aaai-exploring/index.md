---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Exploring the Vulnerability of Deep Neural Networks: A Study of Parameter Corruption"
authors: ["Xu Sun", "Zhiyuan Zhang", "admin", "Ruixuan Luo", "Liangyou Li"]
author_notes: ["Equal contribution", "Equal contribution"]
date: 2021-02-02
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-02T12:57:00+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The Thirty-Fifth AAAI Conference on Artificial Intelligence, **AAAI 2021** (to appear)*"
publication_short: "**AAAI 2021** (to appear)"

abstract: "We argue that the vulnerability of model parameters is of crucial value to the study of model robustness and generalization but little research has been devoted to understanding this matter. In this work, we propose an indicator to measure the robustness of neural network parameters by exploiting their vulnerability via parameter corruption. The proposed indicator describes the maximum loss variation in the non-trivial worst-case scenario under parameter corruption. For practical purposes, we give a gradient-based estimation, which is far more effective than random corruption trials that can hardly induce the worst accuracy degradation. Equipped with theoretical support and empirical validation, we are able to systematically investigate the robustness of different model parameters and reveal vulnerability of deep neural networks that has been rarely paid attention to before. Moreover, we can enhance the models accordingly with the proposed adversarial corruption-resistant training, which not only improves the parameter robustness but also translates into accuracy elevation."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.aaai.org/AAAI21Papers/AAAI-2538.SunX.pdf"
url_arxiv: "https://arxiv.org/abs/2006.05620"
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
