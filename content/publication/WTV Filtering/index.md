---
title: "Wasserstein Total Variation Filtering"
authors:
- Erdem Varol
- admin
date: "2019-10-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: In this paper, we expand upon the theory of trend filtering by introducing the use of the Wasserstein metric as a means to control the amount of spatiotemporal variation in filtered time series data. While trend filtering utilizes regularization to produce signal estimates that are piecewise linear, in the case of l1 regularization, or temporally smooth, in the case of l2 regularization, it ignores the topology of the spatial distribution of signal. By incorporating the information about the underlying metric space of the pixel layout, the Wasserstein metric is an attractive choice as a regularizer to undercover spatiotemporal trends in time series data. We introduce a globally optimal algorithm for efficiently estimating the filtered signal under a Wasserstein finite differences operator. The efficacy of the proposed algorithm in preserving spatiotemporal trends in time series video is demonstrated in both simulated and fluorescent microscopy videos of the nematode \textit{caenorhabditis elegans} and compared against standard trend filtering algorithms.

# Summary. An optional shortened abstract.
summary: ""

tags:
- NeuroPAL
featured: false

url_pdf: https://arxiv.org/pdf/1910.10822.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

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
