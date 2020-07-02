---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "High-fidelity View Synthesis for Light Field Imaging with Extended Pseudo 4DCNN"
authors: ["admin","Fei Liu","Kunbo Zhang","Zilei Wang","Zhenan Sun","Tieniu Tan"]
date: 2020-07-02T21:36:56+08:00

doi: "10.1109/TCI.2020.2986092"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T21:36:56+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Computational Imaging*"
# publication_short: "TCI"

abstract: "Multi-view properties of light field (LF) imaging enable exciting applications such as auto-refocusing, depth estimation and 3D reconstruction. However, limited angular resolution has become the main bottleneck of microlens-based plenoptic cameras towards more practical vision applications. Existing view synthesis methods mainly break the task into two steps, i.e. depth estimating and view warping, which are usually inefficient and produce artifacts over depth ambiguities. We have proposed an end-to-end deep learning framework named Pseudo 4DCNN to solve these problems in a conference paper. Rethinking on the overall paradigm, we further extend pseudo 4DCNN and propose a novel loss function which is applicable for all tasks of light field reconstruction i.e. EPI Structure Preserving (ESP) loss function. This loss function is proposed to attenuate the blurry edges and artifacts caused by averaging effect of L2 norm based loss function. Furthermore, the extended Pseudo 4DCNN is compared with recent state-of-the-art (SOTA) approaches on more publicly available light field databases, as well as self-captured light field biometrics and microscopy datasets. Experimental results demonstrate that the proposed framework can achieve better performances than vanilla Pseudo 4DCNN and other SOTA methods, especially in the terms of visual quality under occlusions. The source codes and self-collected datasets for reproducibility are available online."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Light Field Imaging", "Light Field Reconstruction", "View Synthesis"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/document/9061053
url_code: https://github.com/wylcasia/ExtendedP4DCNN
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
  caption: "Extended Pseudo 4DCNN"
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
