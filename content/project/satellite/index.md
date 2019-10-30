---
title: Building Detection
summary: Finding buildings in satellite imagery.
tags:
- Computer Vision
date: "2014-06-10"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Raw, ground truth, and CRF prediction.
  focal_point: Smart

links:
url_pdf: "project/satellite/poster.pdf"

---

In this project we used a densely connected graphical model to detect building
rooftops in satellite imagery. The problem was formulated as a pixel-level image
segmentation task. Labeled building data was pulled from OpenStreetMap and
registered to publicly available satellite imagery using standard GIS
techniques.  

We applied a fully connected conditional random field (CRF) 
defined on the complete set of pixels of an image as proposed by [Krahenbuhl and
Koltun](https://arxiv.org/abs/1210.5644), with unary potentials derived from
Shotton et al.’s
[TextonBoost](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/ijcv07a.pdf).
Inference in this model is made tractable by using mean-field approximation and
Gaussian kernels for the pairwise potentials, allowing for an efficient
message-passing algorithm.
