---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GraphMap: Scalable Crowd-Sourced Global Vectorized HD Map Construction via Sparse Visual Graph Fusion"
authors:
- admin
- Minkyoung Cho
- Shuqing Zeng
- Fan Bai
- Z. Morley Mao
date: 2026-07-17T00:00:00-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2026-07-17T00:00:00-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2026"
publication_short: "IROS 2026"

abstract: "High-definition (HD) maps are vital for autonomous driving, offering fine-grained geometric and semantic information beyond onboard perceptions. While recent vision-based methods enable online local HD map detection, constructing accurate global vectorized maps at scale remains a fundamental challenge: (1) individual vehicles have limited sensing range, and (2) the mainstream ego-centric dense fusion approaches for collaborative perception suffer from poor scalability, high computation costs, and sensitivity to spatial-temporal misalignment. In this paper, we present GraphMap, a novel crowd-sourced vehicle-cloud framework for global vectorized HD map construction via sparse graph fusion. Unlike prior collaborative perception methods that rely on dense, fixed-size bird’s-eye-view (BEV) features, our approach is not constrained by ego-centric views or fixed perception ranges. GraphMap encodes local vectorized maps as sparse geometric graphs and incrementally fuses them through a sparse-to-sparse graph fusion algorithm. To reduce network bandwidth and computation overhead, GraphMap incorporates a selective map sensing mechanism that prioritizes data uploads from more informative agents with higher sensing value. Experiments across multiple real-world and simulated driving scenes with up to 60 agents demonstrate that GraphMap constructs accurate global maps under sparse, spatially misaligned observations, outperforming state-of-the-art baselines by 37.2 mAP while reducing communication costs by more than 30%."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Autonomous Vehicle", "Cooperative Perception", "HD Map"]
categories: []
featured: false

url_pdf: publication/graphmap/graphmap.pdf
url_code:
url_dataset:
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

projects: []
slides: ""
---
