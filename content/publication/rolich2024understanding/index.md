---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Understanding the impact of persistence and propagation on the Age of Information of broadcast traffic in 5G NR-V2X sidelink communications"
authors:
  - Alexey Rolich
  - admin
  - Alexey Vinel
  - Andrea Baiocchi
date: 2024-05-13
doi: "10.1016/j.comnet.2024.110503"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-05-25T00:00:00+01:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Elsevier Computer Networks"
publication_short: "Elsevier Computer Networks"

abstract: "The current Cellular V2X (C-V2X) standard for direct communication between vehicles is based on the so called Semi-Persistent Scheduling (SPS) algorithm. It is based on the multiple access structure of 5G New Radio (NR) and exploits sensing and persistence to realize a randomized multiple access. We consider the application of SPS to support periodic broadcast traffic where no acknowledgments are provided. Persistence is a key feature, which consists of a node using the same resource for its transmissions for multiple frames. The specific resource used is randomly selected from among those that are perceived to be idle, and reselected anew after a randomized number of frames. We define a model to gain insight into the interplay between persistence and key performance metrics for the type of traffic considered, namely probability of successful delivery and Age of Information (AoI). A core version of the model is validated against simulations and used to show that there exists an optimal level that minimizes AoI. The model is then extended to account for a distance-dependent propagation model, allowing further insight into the effects of the interplay between sender–receiver distance and persistence. Finally, an even more detailed model is investigated, using ns-3-based simulations. This further analysis confirms the qualitative behaviors revealed by the analytical model and provides more insight into the complex interactions of system parameters and channel characteristics. The obtained results help to identify the limits of SPS, opening the way to system-principled parameter optimization and design of more powerful variants of the multiple access scheme."

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
