---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Modular Network Digital Twin for Radio Coverage Prediction: From Theory to Practice"
authors: 
  - Ayat Zaki-Hindi
  - Jean-Sébastien Sottet
  - Sumit Kumar
  - admin
  - Sébastien Faye
date: 2025-12-08
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-09-19T00:00:00+01:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Global Communications Conference (GLOBECOM 2025)"
publication_short: "IEEE GLOBECOM 2025"

abstract: "Network Digital Twins (NDTs) offer a structured framework for modeling, predicting, and optimizing wireless networks. This paper presents a modular NDT implementation based on the GreyCat platform, integrating graph-based data models and external functional algorithms for indoor radio coverage prediction. For the first time, we implement an NDT system aligned with ITU-T Recommendation Y.3090, covering both basic and functional model instantiation from modular and interoperable abstract structures. We generated a practical dataset using a software-defined radio (SDR)-based OpenAirInterface5G setup, with a gNB and commercial UE deployed in a controlled environment. This real-world dataset was used to benchmark Gaussian Process Regression (GPR) and Convolutional Neural Network (CNN) models for predicting RSRP-based radio coverage. Our results show that CNN outperforms GPR in under-sampled conditions, and we demonstrate how the modular architecture supports flexible model integration and benchmarking. This work represents a significant step toward practical, data-driven NDT deployments for wireless systems."

# Summary. An optional shortened abstract.
summary: ""

tags: []
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

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [6g-twin]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
