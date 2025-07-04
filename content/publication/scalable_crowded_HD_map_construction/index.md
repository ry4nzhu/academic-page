---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Scalable Crowd-Sourced Global HD Map Construction via Collaborative Map Perception and Sparse Graph Fusion"
authors: 
- Ruiyang Zhu*
- Minkyoung Cho*
- Shuqing Zeng
- Fan Bai
- Xiang Gao
- Z. Morley Mao
date: 2025-05-27T21:56:53-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-27T21:56:53-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 4th Workshop on Transformers for Vision (T4V) at CVPR 2025"
publication_short: "CVPRW 2025"

abstract: "High-definition (HD) maps are vital for autonomous driving, providing fine-grained geometric and semantic information beyond the scope of onboard perception. However, automatically constructing accurate vectorized maps at scale using learning-based methods remains challenging, as individual vehicles observe only partial, localized environments. This motivates the need for collaborative HD map construction, where multiple vehicles contribute local observations to build a unified global map. While collaborative perception has been extensively studied through dense BEV fusion, existing methods are fundamentally ego-centric and operate within a fixed perception range, making them ill-suited for large-scale, open-world mapping. In this paper, we propose a graph-based sparse fusion framework for collaborative vectorized HD map construction. Vehicles build local HD maps collaboratively and encode them as sparse geometric graphs, which are fused by a sparse-to-sparse fusion algorithm that incrementally aligns and merges graphs across space and time. This design leverages multi-agent fine-grained features and enables scalable, memory-efficient fusion without relying on dense tensors. Experimental results show that our method constructs accurate global maps under sparse and asynchronous observations, outperforming baselines by over 10.3 mAP."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Autonomous Vehicle", "HD-Map"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://drive.google.com/file/d/1t422YHsrgB5f7Mz8uPgQbmgrrByOnTKx/view
url_code: 
url_dataset: 
url_poster: https://drive.google.com/file/d/1TCaIgbg16s_jSUmAs7HnAg-QDXmiXEcS/view?usp=sharing
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
