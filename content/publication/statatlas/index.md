---
title: "Statistical Atlas of C. elegans Neurons"
authors:
- Erdem Varol
- admin
- Ruoxi Sun
- Gonzalo Mena
- Eviatar Yemini
- Oliver Hobert
- Liam Paninski
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
publication: "Statistical Atlas of C. elegans Neurons"
publication_short: "StatAtlas"

abstract: Constructing a statistical atlas of neuron positions in the nematode Caenorhabditis elegans enables a wide range of applications that require neural identity. These applications include annotating gene expression, extracting calcium activity, and evaluating nervous-system mutations. Large complete sets of neural annotations are necessary to determine canonical neuron positions and their associated confidence regions. Recently, a transgene of C. elegans (“NeuroPAL”) has been introduced to assign correct identities to all neurons in the worm via a deterministic, fluorescent colormap. This strain has enabled efficient and accurate annotation of worm neurons. Using a dataset of 10 worms, we propose a statistical model that captures the latent means and covariances of neuron locations, with efficient optimization strategies to infer model parameters. We demonstrate the utility of this model in two critical applications. First, we use our trained atlas to automatically annotate neuron identities in C. elegans at the state-of-the-art rate. Second, we use our atlas to compute correlations between neuron positions, thereby determining covariance in neuron placement. The code to replicate the statistical atlas is distributed publicly at https://github.com/amin-nejat/StatAtlas.


# Summary. An optional shortened abstract.
summary: ""

tags:
- NeuroPAL
- Atlas
- C. elegans
featured: false

url_pdf: 'https://ora.ox.ac.uk/objects/uuid:0838d9ea-e9ff-4d4d-b52e-8dcbd3efcb9f/download_file?safe_filename=Varol_et_al_Statistical_atlas.pdf&type_of_work=Conference+item'
url_code: 'https://github.com/amin-nejat/StatAtlas'


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
