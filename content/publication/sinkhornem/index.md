---
title: "Sinkhorn EM: an expectation-maximization algorithm based on entropic optimal transport"
authors:
- Gonzalo Mena
- admin
- Erdem Varol
- Jonathan Niles-Weed

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
publication: "Sinkhorn EM: an expectation-maximization algorithm based on entropic optimal transport"
publication_short: "SinkhornEM"

abstract: We study Sinkhorn EM (sEM), a variant of the expectation maximization (EM) algorithm for mixtures based on entropic optimal transport. sEM differs from the classic EM algorithm in the way responsibilities are computed during the expectation step: rather than assign data points to clusters independently, sEM uses optimal transport to compute responsibilities by incorporating prior information about mixing weights. Like EM, sEM has a natural interpretation as a coordinate ascent procedure, which iteratively constructs and optimizes a lower bound on the log-likelihood. However, we show theoretically and empirically that sEM has better behavior than EM: it possesses better global convergence guarantees and is less prone to getting stuck in bad local optima. We complement these findings with experiments on simulated data as well as in an inference task involving C. elegans neurons and show that sEM learns cell labels significantly better than other approaches.


# Summary. An optional shortened abstract.
summary: ""

tags:
- Expectation Maximization
- Optimal Transport
featured: false

url_pdf: 'https://arxiv.org/pdf/2006.16548'
url_code: 'https://github.com/amin-nejat/SinkhornEM'


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
