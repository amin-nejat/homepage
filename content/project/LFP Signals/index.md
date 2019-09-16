---
title: Analyzing LFP Signals to Cluster V1 Neurons
summary: ""

tags:
- Robotics
date: "2000-00-00T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Grating stimulus in multiple orientations were shown to the monkey while recording from its V1 layers. We implemented a system to cluster V1 neurons based on their orientation selectivity and features obtained from signals such as peaks and fourier transform. I used svd to reduce the dimension of the feature space and gaussian mixture model for the clustering system. Project for Neuroscience course done with M. Hasanshahi. Implemented in Matlab using its machine learning toolbox.