---
title: Neuroscience Experimental Design and Data Collection System
summary: ""

tags:
- Robotics
date: "2000-00-00T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: "https://youtu.be/lu9dXQs2b6k"

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

In this project, I implemented an object oriented system with the aim of providing researchers the possibility to design visual or auditory neuroscience tasks for human or animal subjects and collect the data based on their behavior. In this system, each task is assumed to be a set of states. In each state a set of stimuli (image, video, sound, or geometrical shape) is represented to the subject of the task. A number of devices are involved in each task, some of them are used by the subject of the task so that the subject can interact with the task while other devices are used as controls to track the subject’s behavior. Using the first group of devices, the subject can move between states of the task. While the task is running, the data of the subject’s interaction with devices and state transitions are collected. Currently, we are using this system in our lab to teach specific tasks to the monkeys and collect their behavioral data.