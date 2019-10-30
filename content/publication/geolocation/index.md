---
title: "User-driven geolocation of untagged desert imagery using digital elevation models"
authors:
- Eric Tzeng
- Andrew Zhai
- Matthew Clements
- admin
- Avideh Zakhor
date: "2013-06-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2013-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Computer Vision and Pattern Recognition 2013 Workshop on Visual Analysis and Geo-Localization of Large-Scale Imagery
publication_short: In CVPR 2013 Workshops

abstract: "We propose a system for user-aided visual localization
of desert imagery without the use of any metadata such as
GPS readings, camera focal length, or field-of-view. The
system makes use only of publicly available digital elevation models (DEMs) to rapidly and accurately locate photographs in non-urban environments such as deserts. Our
system generates synthetic skyline views from a DEM and
extracts stable concavity-based features from these skylines
to form a database. To localize queries, a user manually
traces the skyline on an input photograph. The skyline is
automatically refined based on this estimate, and the same
concavity-based features are extracted. We then apply a
variety of geometrically constrained matching techniques
to efficiently and accurately match the query skyline to a
database skyline, thereby localizing the query image. We
evaluate our system using a test set of 44 ground-truthed
images over a 10,000km<sup>2</sup> region of interest in a desert and
show that in many cases, queries can be localized with precision as fine as 100m<sup>2</sup>."

summary: A user-assisted geolocation system than can use natural skylines to often pinpoint a photo's location to within 100m<sup>2</sup>.

tags:
- CVPR
featured: false

links:
url_pdf: 'https://www.cv-foundation.org/openaccess/content_cvpr_workshops_2013/W07/papers/Tzeng_User-Driven_Geolocation_of_2013_CVPR_paper.pdf'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Query skyline (top) and matched synthetic database skyline (bottom)'
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
