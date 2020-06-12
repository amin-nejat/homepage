---
title: "Temporal Wasserstein Non-Negative Matrix Factorization"
authors:
- Erdem Varol
- admin
- Conor McGrory
date: "2019-12-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-12-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Temporal Wasserstein non-negative matrix factorization for non-rigid motion segmentation and spatiotemporal deconvolution"
publication_short: "TWNMF"

abstract: Motion segmentation for natural images commonly relies on dense optic flow to yield point trajectories which can be grouped into clusters through various means including spectral clustering or minimum cost multicuts. However, in biological imaging scenarios, such as fluorescence microscopy or calcium imaging, where the signal to noise ratio is compromised and intensity fluctuations occur, optical flow may be difficult to approximate. To this end, we propose an alternative paradigm for motion segmentation based on optimal transport which models the video frames as time-varying mass represented as histograms. Thus, we cast motion segmentation as a temporal non-linear matrix factorization problem with Wasserstein metric loss. The dictionary elements of this factorization yield segmentation of motion into coherent objects while the loading coefficients allow for time-varying intensity signal of the moving objects to be captured. We demonstrate the use of the proposed paradigm on a simulated multielectrode drift scenario, as well as calcium indicating fluorescence microscopy videos of the nematode Caenorhabditis elegans (C. elegans). The latter application has the added utility of extracting neural activity of the animal in freely conducted behavior.

# Summary. An optional shortened abstract.
summary: ""

tags:
- TWNMF
featured: false

url_pdf: https://arxiv.org/pdf/1912.03463.pdf
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
