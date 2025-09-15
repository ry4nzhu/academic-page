---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust Real-time Multi-vehicle Collaboration on Asynchronous Sensors"
authors: 
- Qingzhao Zhang*
- Xumiao Zhang*
- Ruiyang Zhu*
- Fan Bai
- Mohammad Naserian
- Z. Morley Mao
date: 2023-06-14T21:56:53-04:00
doi: "https://doi.org/10.1145/3570361.3613271"

# Schedule page publish date (NOT publication's date).
publishDate: 203-06-14T21:56:53-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "MobiCom 2023"
publication_short: "MobiCom 2023"

abstract: "Cooperative perception significantly enhances the perception performance of connected autonomous vehicles. Instead of purely relying on local sensors with limited range, it enables multiple vehicles and roadside infrastructures to share sensor data to perceive the environment collaboratively. Through our study, we realize that the performance of cooperative perception systems is limited in real-world deployment due to (1) out-of-sync sensor data during data fusion and (2) inaccurate localization of occluded areas. To address these challenges, we develop RAO, an innovative, effective, and lightweight cooperative perception system that merges asynchronous sensor data from different vehicles through our novel designs of motion-compensated occupancy flow prediction and on-demand data sharing, improving both the accuracy and coverage of the perception system. Our extensive evaluation, including real-world and emulation-based experiments, demonstrates that RAO outperforms state-of-the-art solutions by more than 34% in perception coverage and by up to 14% in perception accuracy, especially when asynchronous sensor data is present. RAO consistently performs well across a wide variety of map topologies and driving scenarios. RAO incurs negligible additional latency (8.5ms) and low data transmission overhead (10.9 KB per frame), making cooperative perception feasible."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Autonomous Vehicle", "Cooperative Perception"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/doi/pdf/10.1145/3570361.3613271
url_code: 
url_dataset: 
url_poster:
url_project:
url_slides: https://sigmobile.org/mobicom/2023/media/presentations/ZhaoRAO.pptx
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
