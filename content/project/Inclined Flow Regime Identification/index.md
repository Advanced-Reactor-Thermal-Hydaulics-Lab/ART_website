---
title: Objective Flow Regime Identification for Inclined Two-Phase Flows
summary: Experiments and machine learning applications for flow regime identification
tags:
- Active
- Two-phase flow
- Experiments
- Flow Regime Transition
- Machine Learning

date: "2022-05-27T00:00:00Z"

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

Two-phase flow regimes are categorizations of flow patterns based on the geometric characteristics of the interface between phases. Flow regimes are widely implemented in thermal-hydraulics and reactor safety simulation tools. It is therefore crucial to properly classify flow conditions into their respective regimes to design and operate multiphase flow systems. The traditional approach to flow regime classification entails recording two-phase flows in transparent pipes with high-speed video cameras and making subjective judgements about the flow based on visualization. This subjectivity is susceptible to error and disagreement between researchers. Additionally, pipe inclination introduces additional complexity that makes visual classification of flow regimes challenging. Recent work with machine learning has endeavored to reduce the subjectivity involved in flow regime identification and classification efforts.

ART has developed a modular structure of k-means algorithms designed to objectively organize horizontal, inclined, and vertical flow conditions into flow regimes using an experimental database obtained with the separate effects test facility.

{{< figure src="Figure.jpg" title="Flow chart of the hierarchical structure (B: Bubbly, P: Plug, ST: Stratified, S: Slug, CT: Churn-Turbulent, SW: Stratified-Wavy, A: Annular)" numbered="true" lightbox="true" >}}

Images of flow conditions at different angles are shown in Figure 2, highlighting the changes to the interfacial structure that can occur with respect to angle. 

{{< figure src="Figure2.jpg" title="Hierarchical algorithm two-phase flow regime map results: (a) 90° upward, (b) 80° upward, (c) 60° upward, (d) 30° upward, (e) 0° compared to visualization" numbered="true" lightbox="true" >}}
