---
title: Pool++
summary: Pool augmented with computer vision, LIDAR, and lasers.
tags:
- Computer Vision
- Geometry
date: "2015-09-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Pool in black and white.
  focal_point: Smart

links:
url_slides: "pool.pdf"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Best In Show and People's Choice at San Francisco Science Hack Day 2015.

This was a father (hardware) and son (software) project done over 2 days.  We
instrumented a pool table with a LIDAR and an overhead camera — determining the
precise location of the balls and the cue using computer vision and time of
flight data.  These coordinates were fed into a physics engine which would
predict the outcome of the shot, which were in turn drawn onto the table using a
high-powered laser. 
