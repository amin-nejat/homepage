---
title: "Probabilistic Joint Segmentation and Labeling of C. elegans Neurons"
authors:
- admin
- Erdem Varol
- Eviatar Yemini
- Oliver Hobert
- Liam Paninski
date: "2020-09-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Probabilistic Joint Segmentation and Labeling of C. elegans Neurons"
publication_short: "SinkhornEM"

abstract: Automatic identification and segmentation of the neurons of C. elegans enables evaluating nervous system mutations, positional variability, and allows us to conduct high-throughput population studies employing many animals. A recently introduced transgene of C. elegans, named “NeuroPAL” has enabled the efficient annotation of neurons and the construction of a statistical atlas of their positions. Previous atlas-based segmentation approaches have modeled images of cells as a mixture model. The expectation-maximization (EM) algorithm and its variants are used to find the (local) maximum likelihood parameters for this class of models. We present a variation of the EM algorithm called Sinkhorn-EM (sEM) that uses regularized optimal transport Sinkhorn iterations to enforce constraints on the marginals of the joint distribution of observed variables and latent assignments in order to incorporate our prior information about cell sizes into the cluster-data assignment proportions. We apply our method to the problem of segmenting and labeling neurons in fluorescent microscopy images of C. elegans specimens. We show empirically that sEM outperforms vanilla EM and a recently proposed 3-step (filter, detect, identify) labeling approach. Open source code implementing this method is available at https://github.com/amin-nejat/SinkhornEM.


# Summary. An optional shortened abstract.
summary: ""

tags:
- dNMF
featured: false

url_pdf: 'https://link.springer.com/content/pdf/10.1007%2F978-3-030-59722-1.pdf'
url_code: 'https://github.com/amin-nejat/SinkhornEM'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Amin Nejatbakhsh & Erdem Varol'
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
