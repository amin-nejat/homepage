---
title: "Deformable Non-negative Matrix Factorization"
authors:
- admin
- Erdem Varol
- Eviatar Yemini
- Vivek Venkatachalam
- Albert Lin
- Aravi Samuel
- Oliver Hobert
- Liam Paninski
date: "2020-06-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Extracting neural signals from mobile animals with deformable non-negative matrix factorization"
publication_short: "dNMF"

abstract: Extracting calcium traces from the neurons of mobile animals is a critical step in the study of the large-scale neuronal dynamics that govern behavior. Accurate activity extraction requires the correction of motion and movement-induced deformations as well as demixing of signals that may overlap spatially due to limitations in optical resolution. Traditionally, non-negative matrix factorization (NMF) methods have been successful in demixing and denoising cellular calcium activity in relatively motionless or pre-registered videos. However, standard NMF methods fail in mobile animals undergoing significant non-rigid motion; similarly, standard image registration methods based on template matching can fail when large changes in activity lead to mismatches with the image template. To address these issues simultaneously, we introduce a deformable non-negative matrix factorization (dNMF) framework that jointly optimizes registration with signal demixing. On simulated data and real C. elegans microscopy videos, dNMF outperforms traditional demixing methods that account for motion and demixing separately. Finally, following the extraction of neural traces from multiple imaging experiments, we develop a quantile regression time-series normalization technique to account for varying neural signal intensity baselines across different animals or different imaging setups.


# Summary. An optional shortened abstract.
summary: ""

tags:
- dNMF
featured: false

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Erdem Varol'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
