---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Dual-Tasks Siamese Transformer Framework for Building Damage Assessment"
authors: [Hongruixuan Chen, Edoardo Nemni, Sofia Vallecorsa, Xi Li, Chen Wu, Lars Bromley]
date: 2022-01-29T16:33:13+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-29T16:33:13+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Accurate and fine-grained information about the extent of damage to buildings is essential for humanitarian relief and disaster response. However, as the most commonly used architecture in remote sensing interpretation tasks, Convolutional Neural Networks (CNNs) have limited ability to model the non-local relationship between pixels. Recently, Transformer architecture first proposed for modeling long-range dependency in natural language processing has shown promising results in computer vision tasks. Considering the frontier advances of Transformer architecture in the computer vision field, in this paper, we present the first attempt at designing a Transformer-based damage assessment architecture (DamFormer). In DamFormer, a siamese Transformer encoder is first constructed to extract non-local and representative deep features from input multitemporal image-pairs. Then, a multitemporal fusion module is designed to fuse information for downstream tasks. Finally, a lightweight dual-tasks decoder aggregates multi-level features for final prediction. To the best of our knowledge, it is the first time that such a deep Transformer-based network is proposed for multitemporal remote sensing interpretation tasks. The experimental results on the large-scale damage assessment dataset xBD demonstrate the potential of the Transformer-based architecture."

# Summary. An optional shortened abstract.
summary: ""

tags: [damage assessment, deep learning, Vision Transformer]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2201.10953
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
