---
title: Detection of minimum repeatable tile in fabric textures using CNN activations.
summary: MSc Thesis. This work focuses on a modern approach that uses a CNN to extract the activation maps of texture images and detect the minimum repeatable pattern of fabric images.
tags:
  - Deep Learning
  - Computer Vision
date: '2022-06-20T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: 'https://drive.google.com/file/d/1XP-YnNesI8wbOFywh4RQgwCHugOc2J4Y/view'
url_slides: 'https://drive.google.com/file/d/1rL1nQna23VXWpAriaj2jAmH1fogA0rri/view'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

#### Summary

The fashion industry is undergoing digitalization to address its inefficiency, high textile
waste, and environmental damage. Digital tools such as 3D modeling software, virtual
reality, and artificial intelligence enable designers and manufacturers to create and
visualize designs rapidly and precisely, reducing time and expenses. Texture rendering
and digitizing fabrics are increasingly significant in the fashion industry, allowing for
highly realistic simulations and renderings that can be used for various applications such
as virtual clothing try-on and textile product visualization.

However, an open problem in computer vision is detecting the minimum repeatable
tile (MRT) of a fabric, which refers to the smallest unit of a textile pattern that can
be seamlessly repeated to create a larger pattern. This is essential for creating accurate
digital representations of textile patterns, allowing the pattern to be scaled up or down
without distorting its overall appearance. Texture mapping is crucial in fabric rendering
and requires tileable and memory-optimized textures for efficient real-time rendering.
Identifying the minimum repeatable tile is critical to creating realistic and high-quality
texture maps for various applications, including video games and digital art.

Various traditional and modern approaches exist for detecting pattern repetition. This
work focuses on a modern approach that uses a CNN to extract the activation maps of
texture images. The aim of our work is to research and develop auto-tiling, i.e. an
automatic process for the detection of the minimum repeatable pattern. This involves
a three-stage process (auto-alignment, detection of the minimum repeatable tile and
stitching), and an online demo has been created and deployed for users to test it. This
work has been done with the company SEDDI, as it is intended to integrate this product
into SEDDI Textura.