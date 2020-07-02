---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A New Journal Paper Published in TCI2020"
subtitle: "High-fidelity View Synthesis for Light Field Imaging with Extended Pseudo 4DCNN"
summary: ""
authors: ["admin","Fei Liu","Kunbo Zhang","Zilei Wang","Zhenan Sun","Tieniu Tan"]
tags: ["Light Field Imaging", "Light Field Reconstruction", "View Synthesis"]
categories: []
date: 2020-07-02T11:42:00+08:00
lastmod: 2020-07-02T11:42:00+08:00
featured: true
draft: false
share: true  # Show social sharing links?
commentable: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["light-field-image-enhancement-and-application"]
---


Multi-view properties of light field (LF) imaging enable exciting applications such as auto-refocusing, depth estimation and 3D reconstruction. However, limited angular resolution has become the main bottleneck of microlens-based plenoptic cameras towards more practical vision applications. Existing view synthesis methods mainly break the task into two steps, i.e. depth estimating and view warping, which are usually inefficient and produce artifacts over depth ambiguities. We have proposed an end-to-end deep learning framework named Pseudo 4DCNN to solve these problems in a conference paper. Rethinking on the overall paradigm, we further extend pseudo 4DCNN and propose a novel loss function which is applicable for all tasks of light field reconstruction i.e. EPI Structure Preserving (ESP) loss function. This loss function is proposed to attenuate the blurry edges and artifacts caused by averaging effect of L2 norm based loss function. Furthermore, the extended Pseudo 4DCNN is compared with recent state-of-the-art (SOTA) approaches on more publicly available light field databases, as well as self-captured light field biometrics and microscopy datasets. Experimental results demonstrate that the proposed framework can achieve better performances than vanilla Pseudo 4DCNN and other SOTA methods, especially in the terms of visual quality under occlusions. The source codes and self-collected datasets for reproducibility are available online.