---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "DSDANet: Deep Siamese Domain Adaptation Convolutional Neural Network for Cross-domain Change Detection"
authors: [Hongruixuan Chen, Chen Wu, Bo Du, Liangpei Zhang]
date: 2020-06-25T16:49:44+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-04T16:49:44+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Geoscience and Remote Sensing"
publication_short: "IEEE TGRS"

abstract: "Change detection (CD) is one of the most vital applications in remote sensing. Recently, deep learning has achieved promising performance in the CD task. However, the deep models are task-specific and CD data set bias often exists, hence it is inevitable that deep CD models would suffer degraded performance after transferring it from original CD data set to new ones, making manually label numerous samples in the new data set unavoidable, which costs a large amount of time and human labor. This motivates us to learn a transferable CD model in the data set with enough labeled data (source domain), which can well detect changes in another data set without labeled data (target domain). It is defined as the cross-domain change detection problem. In this paper, we propose a novel deep siamese domain adaptation convolutional neural network (DSDANet) architecture for cross-domain CD. In DSDANet, a siamese convolutional neural network first extracts spatial-spectral features from multitemporal images. Then, through multi-kernel maximum mean discrepancy (MK-MMD), the learned feature representation is embedded into a reproducing kernel Hilbert space (RKHS), in which the distribution of two domains can be explicitly matched. By optimizing the network parameters and kernel coefficients with the source labeled data and target unlabeled data, DSDANet can learn transferrable feature representation that can bridge the discrepancy between two domains. To the best of our knowledge, it is the first time that such a domain adaptation-based deep network is proposed for CD. The theoretical analysis and experimental results demonstrate the effectiveness and potential of the proposed method."

# Summary. An optional shortened abstract.
summary: ""

tags: [change detection, deep learning, transfer learning, domain adaptation, convolutional neural network (CNN), multi-kernel maximum mean discrepancy (MK-MMD), multispectral images]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2006.09225
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
