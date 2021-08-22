---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Deep Siamese Multi-scale Convolutional Network for Change Detection in Multi-temporal VHR Images"
authors: [Hongruixuan Chen, Chen Wu, Bo Du, Liangpei Zhang]
date: 2019-08-25T16:11:28+08:00
doi: "10.1109/Multi-Temp.2019.8866947"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-04T16:11:28+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2019 10th International Workshop on the Analysis of Multitemporal Remote Sensing Images"
publication_short: "MultiTemp"

abstract: "In this letter, we propose a powerful multi-scale feature convolution unit for change detection. The proposed unit is able to extract multi-scale features in the same layer. Based on the proposed unit, two novel deep Siamese convolution networks, deep Siamese multi-scale convolutional network (DSMS-CN) and deep Siamese multi-scale fully-convolutional network (DSMS-FCN), are designed for unsupervised and supervised change detection in multi-temporal very high resolution (VHR) images. For unsupervised change detection, we implement automatic pre-detection to obtain training patch samples, and the DSMS-CN fits the statistical distribution of changed and unchanged ground from patch samples for change detection through multi-scale feature extraction module and deep Siamese architecture. For supervised change detection, an end-to-end deep network DSMS-FCN is trained in any size of multitemporal VHR images, and directly output the binary change map. The experimental results with a GF data set and an open change detection data set confirm that the two proposed architectures perform better than the state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: ""

tags: [change detection, deep learning, very-high-resolution (VHR) images]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/abstract/document/8866947/
url_code: https://github.com/I-Hope-Peace/DSMSCN
url_dataset: https://github.com/I-Hope-Peace/ChangeDetectionRepository/tree/master/Dataset/SZTAKI_AirChange_Benchmark
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
