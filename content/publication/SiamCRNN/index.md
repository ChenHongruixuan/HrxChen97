---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Change Detectin in Multisource VHR Images via Deep Siamese Convolutional Multiple-Layers Recurrent Neural Network"
authors: [Hongruixuan Chen, Chen Wu, Bo Du, Liangpei Zhang, Le Wang]
date: 2020-04-01T15:42:50+08:00
doi: "10.1109/TGRS.2019.2956756"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-04T15:42:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Geoscience and Remote Sensing"
publication_short: "IEEE TGRS"

abstract: "With the rapid development of Earth observation technology, very-high-resolution (VHR) images from various satellite sensors are more available, which greatly enrich the data source of change detection (CD). Multisource multitemporal images can provide abundant information on observed landscapes with various physical and material views, and it is exigent to develop efficient techniques to utilize these multisource data for CD. In this article, we propose a novel and general deep siamese convolutional multiple-layers recurrent neural network (RNN) (SiamCRNN) for CD in multitemporal VHR images. Superior to most VHR image CD methods, SiamCRNN can be used for both homogeneous and heterogeneous images. Integrating the merits of both convolutional neural network (CNN) and RNN, SiamCRNN consists of three subnetworks: deep siamese convolutional neural network (DSCNN), multiple-layers RNN (MRNN), and fully connected (FC) layers. The DSCNN has a flexible structure for multisource image and is able to extract spatial-spectral features from homogeneous or heterogeneous VHR image patches. The MRNN stacked by long-short term memory (LSTM) units is responsible for mapping the spatial-spectral features extracted by DSCNN into a new latent feature space and mining the change information between them. In addition, FC, the last part of SiamCRNN, is adopted to predict change probability. The experimental results in two homogeneous data sets and one challenging heterogeneous VHR images data set demonstrate that the promising performances of the proposed network outperform several state-of-the-art approaches."

# Summary. An optional shortened abstract.
summary: ""

tags: [change detection, deep learning, very-high-resolution (VHR) images, multi-source images]
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
url_code: https://github.com/I-Hope-Peace/SiamCRNN
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
  focal_point: "Center"
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
