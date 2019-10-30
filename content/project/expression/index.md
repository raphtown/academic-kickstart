---
title: Expression Recognition
summary: Classification of facial expressions.
tags:
- Computer Vision
date: "2012-12-15"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Gabor filters applied to a sample BSAF image.
  focal_point: Smart

links:
url_pdf: "project/expression/facialExpressionRecognition.pdf"

---

Classified which of 6 expressions (Joy, Sorrow, Disgust, Anger, Surprise, Fear)
were being displayed in grayscale images of subjects’ faces.  

We trained one-vs-many linear SVMs on Gabor filters applied to the input images.
We used existing standard datasets (i.e., Cohn-Kanade and JAFFE) as well as a
self-collected 47-subject dataset: the Berkeley Students and Friends (BSAF).
