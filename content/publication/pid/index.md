---
title: "Estimating the unique information of continuous variables"
authors:
- Ari Pakman
- admin
- Dar Gilboa
- Abdullah Makkeh
- Luca Mazzucato
- Michael Wibral
- Elad Schneidman
date: "2019-08-19T00:00:00Z"
doi: ""


# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Estimating the unique information of continuous variables"
publication_short: "PID"

abstract: The integration and transfer of information from multiple sources to multiple targets is a core motive of neural systems. The emerging field of partial information decomposition (PID) provides a novel information-theoretic lens into these mechanisms by identifying synergistic, redundant, and unique contributions to the mutual information between one and several variables. While many works have studied aspects of PID for Gaussian and discrete distributions, the case of general continuous distributions is still uncharted territory. In this work we present a method for estimating the unique information in continuous distributions, for the case of one versus two variables. Our method solves the associated optimization problem over the space of distributions with fixed bivariate marginals by combining copula decompositions and techniques developed to optimize variational autoencoders. We obtain excellent agreement with known analytic results for Gaussians, and illustrate the power of our new approach in several brain-inspired neural models. Our method is capable of recovering the effective connectivity of a chaotic network of rate neurons, and uncovers a complex trade-off between redundancy, synergy and unique information in recurrent networks trained to solve a generalized XOR task.

# Summary. An optional shortened abstract.
summary: ""

tags:
- PID
featured: false

url_pdf: https://proceedings.neurips.cc/paper/2021/file/a9a1d5317a33ae8cef33961c34144f84-Paper.pdf
# url_code: https://github.com/amin-nejat/CELL_ID


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Ev Yemini'
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
