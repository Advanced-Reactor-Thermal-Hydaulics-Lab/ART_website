---
title: Objective Flow Regime Identification via Ultrasound
summary: Analysis using ultrasonic signal and Symbolic Dynamic Filtering (SDF) to determine the flow structure.
tags:
- Previous
- Experiments
- Flow Regime Identification

date: "2019-08-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart
  preview_only: true

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

authors: ["skim"]
---

In two-phase flows systems, knowledge of the flow structure is important in determining the pressure drop, heat transfer capability and general behavior of the flow. However, in practical pipes systems, the flow structure cannot be visually observed. The current work investigates the use of an ultrasonic signal coupled with Symbolic Dynamic Filtering (SDF) to gain understanding of the flow structure. The processing algorithm compares the characteristics of a “base-state” to an input condition to determine the measure of difference.

To test the approach, measurements in an air-water system are taken with the ultrasonic probe and the output of the algorithm correlated to the area-averaged void fraction of the flow condition. As shown in Figure 1, the degree of change in the flow condition, from the base-state, undergoes an inflection at the location where the structure is visually observed to change from bubbly to cap-bubbly flow. Ideally, this sensor could be employed is a system to detect a change in flow structure and take corrective action if necessary.

{{< figure src="featured.jpg" title="Output of SDF versus area-averaged void fraction measurements of conductivity probe." numbered="true" lightbox="true" >}}

{{< figure src="Figure2.jpg" title="Rows from top to bottom: (1) high-speed camera image of the flow process; (2) ultrasonic signal; (3) pattern (i.e., state probability) vector." numbered="true" lightbox="true" >}}
