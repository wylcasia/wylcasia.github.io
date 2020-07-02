---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Novel Deep-learning Pipeline for Light Field Image Based Material Recognition"
authors: ["admin","Kunbo Zhang","Zhenan Sun"]
date: 2020-07-02T21:57:47+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T21:57:47+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*25th International Conference on Pattern Recognition (ICPR2020)*"
# publication_short: ""

abstract: "The primitive basis of image based material recognition builds upon the fact that discrepancies in the reflectances of distinct materials lead to imaging differences under multiple viewpoints. LF cameras possess coherent abilities to capture multiple sub-aperture views (SAIs) within one exposure, which can provide appropriate multi-view sources for material recognition. In this paper, a unified Factorize-Connect-Merge (FCM) deep-learning pipeline is proposed to solve problems of light field image based material recognition. 4D light-field data as input is initially decomposed into consecutive 3D light-field slices. Shallow CNN is leveraged to extract low-level visual features of each view inside these slices. As to establish correspondences between these SAIs, Bidirectional Long-Short Term Memory (Bi-LSTM) network is built upon these low-level features to model the imaging differences. After feature selection including concatenation and dimension reduction, effective and robust feature representations for material recognition can be extracted from 4D light-field data. Experimental results indicate that the proposed pipeline can obtain remarkable performances on both tasks of single-pixel material classification and whole-image material segmentation. In addition, the proposed pipeline can potentially benefit and inspire other researchers who may also take LF images as input and need to extract 4D light-field representations for computer vision tasks such as object classification, semantic segmentation and edge detection. "

# Summary. An optional shortened abstract.
summary: ""

tags: ["Light Field Imaging", "Material Recognition"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: wang-icpr-2020.pdf
# url_code: 
# url_dataset:
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Light Field Image Based Material Recognition"
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["light-field-image-enhancement-and-application"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
