---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Towards 6G Sidelink: Distributed Scheduling and Routing for Reliable Multi-Hop Connectivity"
authors: 
  - Saleh Nikooroo
  - Juan Estrada-Jimenez
  - Aurel Machalek
  - Jérôme Härri
  - Thomas Engel
  - admin
date: 2026-02-15
doi: "10.23919/WONS68803.2026.11501839"

# Schedule page publish date (NOT publication's date).
publishDate: 2026-02-15T00:00:00+01:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "21st Wireless On-demand Network systems and Services Conference (WONS 2026)"
publication_short: "WONS 2026"

abstract: "Reliable multi-hop communication in 5G New Radio (NR) Vehicle-to-Everything (V2X) communications remains challenging, especially in dynamic, infrastructure-less scenarios. We present a joint framework for distributed scheduling and multi-hop relaying over the Sidelink interface, tailored to dynamic formations such as virtually coupled trains. Motivated by the railway requirement to operate strictly at Layer 2 (i.e., without the ETSI ITS stack), our design integrates sensing based on inter-UE coordination with a proactive routing protocol inspired by B.A.T.M.A.N. that fits the Sidelink MAC model. Unlike approaches that treat routing and resource selection independently, our cross-layer strategy couples the two via a hybrid next-hop metric – a weighted combination of Signal-to-Interference-plus-Noise Ratio (SINR) and available resource blocks – so that paths can avoid weak links and relays with limited resources. Simulations in a virtual train coupling scenario show high delivery ratios, reduced hidden-node collisions, and robust performance across densities, indicating the suitability of the proposed Layer 2 framework for V2X-enabled train automation and future cooperative mobility systems."

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
projects: [candi]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
