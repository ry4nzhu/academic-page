---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Bugbasev2"
summary: "Bugbase (version 2) is a collection of reproduceable bugs in popular software stsytems."
authors: []
tags: []
categories: []
date: 2021-04-30T22:42:50-04:00

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/efeslab/bugbasev2"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Failure Sketch of the Bug"
  focal_point: "Center"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/efeslab/bugbasev2"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Bugbasev2 is a collection of reproduceable bugs in popular software stsytems (e.g. TensorFlow, MySQL, etc) and their failture sketches. Those reproducible bugs help for evaluating bug detection and root cause diagnosis and is an extension of data for the [bugbase](https://github.com/dslab-epfl/bugbase) project. All the bugs are self-contained inside a docker container and ready to be invoked independently. Currently, the total number of reproducible bugs exceeds 100.

Related paper: [Failure Sketching: A Technique for Automated Root Cause Diagnosis of In-Production Failures (SOSP'15)](https://dslab.epfl.ch/pubs/gist.pdf)
