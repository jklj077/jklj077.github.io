---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Be Careful about Poisoned Word Embeddings: Exploring the Vulnerability of the Embedding Layers in NLP Models"
authors: ["Wenkai Yang", "Lei Li", "Zhiyuan Zhang", "admin", "Xu Sun", "Qun Liu"]
date: 2021-06-06
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-01T12:53:44+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics, **NAACL 2021** (to appear)*"
publication_short: "**NAACL 2021** (to appear)"

abstract: "Recent studies have revealed a security threat to natural language processing (NLP) models, called the Backdoor Attack. Victim models can maintain competitive performance on clean samples while behaving abnormally on samples with a specific trigger word inserted. Previous backdoor attacking methods usually assume that attackers have a certain degree of data knowledge, either the dataset which users would use or proxy datasets for a similar task, for implementing the data poisoning procedure. However, in this paper, we find that it is possible to hack the model in a data-free way by modifying one single word embedding vector, with almost no accuracy sacrificed on clean samples. Experimental results on sentiment analysis and sentence-pair classification tasks show that our method is more efficient and stealthier. We hope this work can raise the awareness of such a critical security risk hidden in the embedding layers of NLP models."

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
url_arxiv: "https://arxiv.org/abs/2103.15543"
url_code: "https://github.com/lancopku/Embedding-Poisoning"
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
