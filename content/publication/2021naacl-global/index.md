---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Global Past-Future Early Exit Method for Accelerating Inference of Pre-trained Language Models"
authors: ["Kaiyuan Liao", "Yi Zhang", "admin", "Qi Su", "Xu Sun", "Bin He"]
author_notes: ["Equal contribution", "Equal contribution"]
date: 2021-06-06
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-01T12:57:44+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics, **NAACL 2021** (to appear)*"
publication_short: "**NAACL 2021** (to appear)"

abstract: "Early exit mechanism aims to accelerate inference speed for large-scale pre-trained language models. The essential idea is exiting early without passing through all the inference layers at the inference stage. To make accurate predictions for downstream tasks, the hierarchical linguistic information embedded in all layers should be jointly considered. However, much of the research up to now has been limited to use local representations of the exit layer. Such treatment inevitably loses information of the unused passed layers as well as the high-level features embedded in future layers, leading to sub-optimal performance. To address this issue, we propose a novel Past-Future method to make comprehensive predictions from a global perspective. We first take into consideration all the hierarchical linguistic information embedded in the past layers and then take a further step to engage the future states which are originally inaccessible for predictions. Extensive experiments demonstrate that our method outperforms previous early exit methods by a large margin, yielding more effective and more robust results."

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

url_pdf: 
url_arxiv:
url_code: "https://github.com/lancopku/Early-Exit"
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
