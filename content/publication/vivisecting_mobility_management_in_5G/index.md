---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: " Vivisecting Mobility Management in 5G Cellular Networks"
authors: 
- Ahmad Hassan
- Arvind Narayanan
- Anlan Zhang
- Wei Ye
- Ruiyang Zhu
- Shuowei Jin
- Jason Carpenter
- Z. Morley Mao
- Zhi-Li Zhang
- Feng Qian
date: 2022-05-29T21:56:53-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-05-29T21:56:53-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "SIGCOMM 2022"
publication_short: "SIGCOMM 2022"

abstract: "With 5G's support for diverse radio bands and different deployment modes, e.g. standalone (SA) vs. non-standalone (NSA), mobility management - especially the handover process - becomes far more complex. Measurement studies have shown that frequent handovers cause wild fluctuations in 5G throughput, and worst, service outages. Through a cross-country (6,200km+) driving trip, we conduct in-depth measurements to study the current 5G mobility management practices adopted by three major US carriers. Using this rich dataset, we carry out a systematic analysis to uncover the handover mechanisms employed by 5G carriers, and compare them along several dimensions such as (4G vs. 5G) radio technologies, radio (low-, mid- & high-)bands, and deployment (SA vs NSA) modes. We further quantify the impact of mobility on application performance, power consumption, and signaling overheads. We identify key challenges facing today’s NSA 5G deployments which result in unnecessary handovers and reduced coverage. Finally, we design a holistic handover prediction system Prognos and demonstrate its ability to improve QoE for two 5G applications 16K panoramic VoD and real-time volumetric video streaming. We have released the datasets and tools of our study at https://github.com/SIGCOMM22-5GMobility/artifact."

# Summary. An optional shortened abstract.
summary: ""

tags: ["5G", "mobility management"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code: https://github.com/SIGCOMM22-5GMobility/artifact
url_dataset: https://github.com/SIGCOMM22-5GMobility/artifact
url_poster:
url_project:
url_slides:
url_source:
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
