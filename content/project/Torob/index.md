---
title: Torob Automatic Feature Extraction and Clustering System
summary: ""

tags:
- Robotics
date: "2000-00-00T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
- icon: 
  icon_pack: 
  name: Visit
  url: http://torob.com
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

Torob is an intelligent shopping search engine which searches for a specific product through Iranian E-Stores. In order to find the minimum price for a product among different stores, a system was needed to cluster html pages into groups, each of which was representive of one specific product. For this purpose, I translated the data into english, wrote a code to find similar words based on their semantic relations, extracted features from the data, and implemented a clustering system based on affinity propagation algorithm. Project for Torob Company. Implemented in Python using goslate library for translation, nltk library for finding similar words and sickit-learn library for clustering system.