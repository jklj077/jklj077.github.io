---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-View Feature Representation for Dialogue Generation with Bidirectional Distillation"
authors: ["Shaoxiong Feng", "admin", "Kan Li", "Xu Sun"]
date: 2021-02-02
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-02T12:57:33+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The Thirty-Fifth AAAI Conference on Artificial Intelligence, **AAAI 2021** (to appear)*"
publication_short: "**AAAI 2021** (to appear)"

abstract: "Neural dialogue models suffer from low-quality responses when interacted in practice, demonstrating difficulty in generalization over training data. Recently, knowledge distillation has been used to successfully regularize the student by transferring knowledge from the teacher. However, the teacher and the student are trained on the same dataset and tend to learn similar feature representations, whereas the most general knowledge should be found through differences. The finding of general knowledge is further hindered by the unidirectional distillation, as the student should obey the teacher and may discard some knowledge that is truly general but refuted by the teacher. To this end, we propose a novel training framework, where the learning of general knowledge is more in line with the idea of reaching consensus, i.e., finding common knowledge that is beneficial to different yet all datasets through diversified learning partners. Concretely, the training task is divided into a group of subtasks with the same number of students. Each student assigned to one subtask is not only optimized on the allocated subtask but also imitates multi-view feature representation aggregated from other students (i.e., student peers), which induces students to capture common knowledge among different subtasks and alleviates the over-fitting of students on the allocated subtasks. To further enhance generalization, we extend the unidirectional distillation to the bidirectional distillation that encourages the student and its student peers to co-evolve by exchanging complementary knowledge with each other. Empirical results and analysis demonstrate that our training framework effectively improves the model generalization without sacrificing training efficiency."

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
