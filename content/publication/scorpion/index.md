---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SCORPION: Robust Spatial-Temporal Collaborative Perception Model on Lossy Wireless Network"
authors: 
- Ruiyang Zhu
- Minkyoung Cho
- Shuqing Zeng
- Fan Bai
- Z. Morley Mao
date: 2025-05-29T21:56:53-04:00
doi: "10.1109/IROS60139.2025.11247050"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-29T21:56:53-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2025"
publication_short: "IROS 2025 (**Oral**)"

abstract: "Collaborative Perception enables multiple agents, such as autonomous vehicles and infrastructure, to share sensor data via vehicular networks so that each agent gains an extended sensing range and better perception quality. Despite its promising benefits, realizing the full potential of such systems faces significant challenges due to inherent imperfections in underlying system layers, consisting of network layer imperfections and hardware-level noises. Such imperfections and noises include packet loss in vehicular networks, localization errors from GPS measurements, and synchronization errors caused by clock deviation and network latency. To address these challenges, we propose a novel end-to-end collaborative perception framework, SCORPION, that harnesses the AI co-design of the application layer and system layer to tackle the aforementioned imperfections. SCORPION consists of three main components: lost bird’s eye view feature reconstruction (L-BEV-R) recovers lost spatial features during lossy V2X communication, while deformable spatial cross attention (DSCA) and temporal alignment (TA) compensate for localization and synchronization errors in feature fusion. Experimental results on both synthetic and real-world collaborative 3D object detection datasets demonstrate that SCORPION advances the state-of-the-art collaborative perception methods by 5.9 - 13.2 absolute AP on both standard and noisy scenarios."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Autonomous Vehicle", "Cooperative Perception"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Website
  url: ./scorpion/index.html
  # icon_pack: fab
  # icon: twitter

url_pdf:
url_code: 
url_dataset: 
url_poster: files/SCORPION-IROS25.pdf
url_project: ""
url_slides: files/SCORPION-IROS25-slides.pdf
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
