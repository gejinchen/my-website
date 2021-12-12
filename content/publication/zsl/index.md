---
abstract: The Activity Recognition Chain generally precludes the challenging
  scenario of recognizing new activities that were unseen during training,
  despite this scenario being a practical and common one as users perform
  diverse activities at test time. A few prior works have adopted zero-shot
  learning methods for IMU-based activity recognition, which work by relating
  seen and unseen classes through an auxiliary semantic space. However, these
  methods usually rely heavily on a hand-crafted attribute space which is costly
  to define, or a learnt semantic space based on word embedding, which lacks
  motion-related information crucial for distinguishing IMU features. Instead,
  we propose a strategy to exploit videos of human activities to construct an
  informative semantic space. With our approach, knowledge from state-of-the-art
  video action recognition models is encoded into video embeddings to relate
  seen and unseen activity classes. Experiments on three public datasets find
  that our approach outperforms other learnt semantic spaces, with an additional
  desirable feature of scalability, as recognition performance is seen to scale
  with the amount of data used. More generally, our results indicate that
  exploiting information from the video domain for IMU-based tasks is a
  promising direction, with tangible returns in a zero-shot learning scenario.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Catherine Tong
  - admin
  - Nicholas D. Lane
author_notes:
  - Equal contribution
  - Equal contribution
publication: In *Proceedings of the ACM on Interactive, Mobile, Wearable and
  Ubiquitous Technologies*
summary: Introduced a novel video embedding space for zero-shot HAR.
url_dataset: ""
url_project: ""
publication_short: In *IMWUT/UbiComp*
url_source: ""
url_video: ""
title: Zero-Shot Learning for IMU-Based Activity Recognition Using Video Embeddings
doi: ""
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2021-12-15T00:00:42.162Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
