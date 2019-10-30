---
title: "End-to-End Learning on 3D Protein Structure for Interface Prediction"
authors:
- admin
- Rishi Bedi
- Patricia A. Suriana
- Ron O. Dror
date: "2019-10-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Neural Information Processing Systems 2019
publication_short: In NeurIPS 2019

abstract: "Despite an explosion in the number of experimentally determined, atomically detailed structures of biomolecules, many critical tasks in structural biology remain data-limited.  Whether performance in such tasks can be improved by using large repositories of tangentially related structural data remains an open question.  To address this question, we focused on a central problem in biology: predicting how proteins interact with one another---that is, which surfaces of one protein bind to those of another protein.  We built a training dataset, the Database of Interacting Protein Structures (DIPS), that contains biases but is two orders of magnitude larger than those used previously.  We found that these biases significantly degrade the performance of existing methods on gold-standard data.  Hypothesizing that assumptions baked into the hand-crafted features on which these methods depend were the source of the problem, we developed the first end-to-end learning model for protein interface prediction, the Siamese Atomic Surfacelet Network (SASNet).  Using only spatial coordinates and identities of atoms, SASNet outperforms state-of-the-art methods trained on gold-standard structural data, even when trained on only 3% of our new dataset."

summary: We present a 100x-sized protein interface prediction dataset and achieve state-of-the-art results through using 3DCNNs.

tags:
- NeurIPS
featured: true

links:
url_pdf: 'https://arxiv.org/abs/1807.01297'
url_code: 'https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/H93ZKK'
url_dataset:  'https://github.com/drorlab/DIPS'
url_poster: 'https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/H93ZKK/GVQOD2&version=5.0'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'The SASNet model for interface prediction.'
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
