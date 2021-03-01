---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Deep and Efficient: A Deep Siamese Self-Attention Fully Efficient Convolutional Network for Change Detection in VHR Images"
authors: [Hongruixuan Chen, Chen Wu, Bo Do]
date: 2020-12-29T17:06:16+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-01T17:06:16+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transaction on Neural Networks and Learning Systems"
publication_short: "IEEE TNNLS"

abstract: "Change detection in multi-temporal very-high-resolution (VHR) images plays a significant role in facilitating the understanding of the relationships and interactions between human activities and the natural environment. Recently, fully convolutional networks (FCNs) have attracted widespread attention in the change detection field. In pursuit of better change detection performance, it has become a tendency to design deeper and more complicated FCNs, which inevitably brings about huge numbers of parameters and an unbearable computational burden. With the goal of designing a quite deep architecture to obtain more precise change detection results while simultaneously decreasing parameter numbers to improve efficiency, in this work, we present a very deep and efficient change detection network, entitled EffCDNet. In EffCDNet, to reduce the numerous parameters associated with deep architecture, an efficient convolution consisting of depth-wise convolution and group convolution with a channel shuffle mechanism is introduced to replace standard convolutional layers. In terms of the specific network architecture, EffCDNet does not use mainstream UNet-like architecture, but rather adopts another type of architecture with a very deep encoder and a lightweight decoder. In the very deep encoder, two very deep siamese streams stacked by efficient convolution first extract two highly representative and informative feature maps from input image-pairs. By performing a subtraction operation on two deep feature maps, a difference feature map containing rich change information is produced. Subsequently, an efficient atrous spatial pyramid pooling (EASPP) module is designed to capture multi-scale change information. In the lightweight decoder, a recurrent criss-cross self-attention (RCCA) module is applied to efficiently utilize non-local similar feature representations to enhance discriminability for each pixel, thus effectively separating the changed and unchanged regions. Moreover, to tackle the optimization problem in confused pixels, two novel loss functions based on information entropy are presented. On two challenging open change detection datasets, our approach outperforms other state-of-the-art FCN-based methods in terms of both visual interpretation and accuracy assessment, with only benchmark-level parameter numbers and quite low computational overhead, thereby demonstrating its effectiveness, superiority, and potential."

# Summary. An optional shortened abstract.
summary: ""

tags: [Change detection, very-high-resolution image, deep siamese fully convolutional network, efficient convolution, self-attention mechanism, information entropy]
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
