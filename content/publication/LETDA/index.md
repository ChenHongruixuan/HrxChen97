---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Cross-domain Semantic Segmentation via Low-level Edge Information Transfer"
authors: [Hongruixuan Chen, Chen Wu, Yonghao Xu, Bo Do]
date: 2021-03-04T14:44:11+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-04T14:44:11+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Aims at ACM Multimedia"
publication_short: "ACMMM"

abstract: "Cross-domain semantic segmentation has received widespread attention over the past years, which aims to make models trained on synthetic data (source domain) adapt to real images (target domain). Previous feature-level adversarial learning methods only consider adapting models on the high-level semantic features. However, the large domain gap between source and target domains in the high-level semantic features makes accurate adaptation difficult. In this paper, we present the first attempt at explicitly using low-level edge information, which has a small domain shift between source and target domains, to guide the semantic segmentation over the target domain. To this end, a dual-stream domain adaptation architecture is proposed, which uses an independent edge stream to process edge information, thereby generating high quality semantic boundaries over the target domain. Then, an edge consistency loss is presented to align target semantic predictions with produced boundaries. Moreover, we further propose two entropy reweighting methods for semantic adversarial learning and self-supervised training, respectively, which can further enhance the adaptation performance of our architecture. Comprehensive experiments on two benchmark datasets demonstrate the superiority of our architecture compared with state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: ""

tags: [deep learning, semantic segmentation, domain adaptation]
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
