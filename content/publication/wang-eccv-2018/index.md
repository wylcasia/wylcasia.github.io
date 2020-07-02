---
title: "End-to-End View Synthesis for Light Field Imaging with Pseudo 4DCNN"
date: 2018-01-01
publishDate: 2020-02-16T11:44:49.306438Z
authors: ["admin", "Fei Liu", "Zilei Wang", "Guangqi Hou", "Zhenan Sun", "Tieniu Tan"]
publication_types: ["1"]
abstract: "Limited angular resolution has become the main bottleneck of microlens-based plenoptic cameras towards practical vision applications. Existing view synthesis methods mainly break the task into two steps, i.e. depth estimating and view warping, which are usually inefficient and produce artifacts over depth ambiguities. In this paper, an end-to-end deep learning framework is proposed to solve these problems by exploring Pseudo 4DCNN. Specifically, 2D strided convolutions operated on stacked EPIs and detail-restoration 3D CNNs connected with angular conversion are assembled to build the Pseudo 4DCNN. The key advantage is to efficiently synthesize dense 4D light fields from a sparse set of input views. The learning framework is well formulated as an entirely trainable problem, and all the weights can be recursively updated with standard backpropagation. The proposed framework is compared with state-of-the-art approaches on both genuine and synthetic light field databases, which achieves significant improvements of both image quality (+2 dB higher) and computational efficiency (over 10X faster). Furthermore, the proposed framework shows good performances in real-world applications such as biometrics and depth estimation."
featured: true
publication: "*European Conference On Computer Vision (ECCV2018)*"
tags: ["Computational Photography", "Deep Learning", "Light Field Reconstruction", "End-to-end View Synthesis", "Pseudo 4DCNN"]
url_pdf: wang-eccv-2018.pdf
url_code: https://github.com/wylcasia/Pseudo4DCNN
image:
  placement: 1
  caption: "Pseudo 4DCNN"
  focal_point: "Center"
  preview_only: false
projects: ["light-field-image-enhancement-and-application"]
---

