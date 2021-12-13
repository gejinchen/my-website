---
title: Example Project
summary: Use deep learning to improve the power efficiency of camera traps.
tags:
- Deep Learning
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links: []
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

Camera trapping, in which cameras with motion sensors are set up to automatically capture images or videos of wild animals, has become one of the most important and efficient ways for scientists to understand the distribution or behaviour of wildlife. However, the constraints in power and storage, as well as the requirement of manual data processing still significantly limit the flexibility and applicability of camera trapping. To cope with these issues, we propose an intelligent camera trapping system we call AICaTS. Our system employs model compression techniques to integrate Convolutional Neural Networks (CNNs) with low power camera trap devices. Thereafter, image classification is performed on the edge to evaluate the contents of the captured images and then make valuable decisions like whether to start video recording, what kind of recording quality should be used, etc. Even with the strict resource restrictions, our compressed models still achieve competitive accuracies, which proves the feasibility of machine learning on common camera-trapping hardware. Finally, we also built a simple camera trap to demonstrate our ideas. 