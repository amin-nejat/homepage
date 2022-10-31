---
title: "Functional Causal Flow"
authors:
- admin
- Francesco Fumarola
- Saleh Esteki
- Taro Toyoizumi
- Roozbeh Kiani
- Luca Mazzucato
date: "2020-11-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Predicting perturbation effects from resting state activity using functional causal flow"
publication_short: "FCF"

abstract: A crucial challenge in targeted manipulation of neural activity is to identify perturbation sites whose stimulation exerts significant effects downstream (high efficacy), a procedure currently achieved by labor-intensive trial-and-error. Targeted perturbations will be greatly facilitated by understanding causal interactions within neural ensembles and predicting the efficacy of perturbation sites before intervention. Here, we address this issue by developing a computational framework to predict how single-site micorstimulation alters the ensemble spiking activity in an alert monkey’s prefrontal cortex. Our framework uses delay embedding techniques to infer the ensemble’s functional causal flow (FCF) based on the functional interactions inferred at rest. We validate FCF using ground truth data from models of cortical circuits, showing that FCF is robust to noise and can be inferred from brief recordings of even a small fraction of neurons in the circuit. A detailed comparison of FCF with several alternative methods, including Granger causality and transfer entropy, highlighted the advantages of FCF in predicting perturbation effects on empirical data. Our results provide the foundation for using targeted circuit manipulations to develop targeted interventions suitable for brain-machine interfaces and ameliorating cognitive dysfunctions in the human brain.


# Summary. An optional shortened abstract.
summary: "In this project, we develop a computational framework to predict how single-site micorstimulation alters the ensemble spiking activity in an alert monkey’s prefrontal cortex."

tags:
- dNMF
featured: true

url_pdf: 'https://www.biorxiv.org/content/10.1101/2020.11.23.394916v3.full.pdf'
url_code: 'https://github.com/amin-nejat/CCM'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Luca Mazzucato & Amin Nejatbakhsh'
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
