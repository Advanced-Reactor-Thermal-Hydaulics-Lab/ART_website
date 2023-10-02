---
title: Identification of Plug Bubbles by Segmentation of Images using a Residual Neural Network
subtitle: ''
summary: Development of a method of bubble identification using a neural network
tags:
- Previous
- Image Analysis
- Two-phase Flow
- Neural Network
- Machine Learning

date: "2020-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart
  preview_only: "true"

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

authors: ["marquarj", "kongr"]
---

Plug and slug flow regimes are known for their bullet shapes. Identifying the shape the of the plug bubble is crucial to understanding the pressure drop and heat transfer capacity of the the fluid. The conventional solution to analyze plug bubbles is to use image analysis techniques. These techniques are useful, but can be computationally expensive, and the diversity of methods leads to diversity of errors.

Using previously acquired data from videos of plug bubbles passing through a mirror box in order to capture the top and and the side of the bubble at once. A residual convolutional neural network was trained to try and mimic the plug/slug bubble identification techniques. Once trained, this neural method was much less computationally expensive than the image analysis techniques, and even reduces some of the errors present in the original techniques. A comparison of the neural network identification to raw video is shown in Figure 1.
