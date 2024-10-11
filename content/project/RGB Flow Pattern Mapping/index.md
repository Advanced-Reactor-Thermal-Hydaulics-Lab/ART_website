---
title: RGB Flow Pattern Mapping and Classification
summary: A novel alternative to flow regime identification
tags:
- Active
- Two-phase flow
- Experiments
- Flow Regime Transition
- RGB

date: "2024-10-11T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ''
  focal_point: Smart
  preview_only: true

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

authors: ["kang284", "ryan103"] 
---

Two-phase flow regimes are categorizations of flow patterns based on the geometric characteristics of the interface between phases. Flow regimes are widely implemented in thermal-hydraulics and reactor safety simulation tools. It is therefore crucial to properly classify flow conditions into their respective regimes to design and operate multiphase flow systems. The traditional approach to flow regime classification entails recording two-phase flows in transparent pipes with high-speed video cameras and making subjective judgements about the flow based on visualization. After taking videos for multiple flow conditions, flow regime transition boundaries are drawn onto a map.

Not only is this methodology inherently subjective, it misrepresents flow pattern development as an instantaneous transition and introduces numerical instabilities as correlations on either side of a transition fail to converge to a single solution along the boundary. This is often artificially treated by smoothing the solutions. Additionally, pipe inclination introduces additional complexity that makes visual classification of flow regimes challenging.

ART has developed a novel approach to flow pattern identification and classification which is applicable to any pipe inclination, and which presents flow pattern transitions as continuous gradients based on experimental impedance meter signals obtained with the separate effects test facility.

