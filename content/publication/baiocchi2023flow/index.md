---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "On Flow Control and Optimized Back-Off in Non-Saturated CSMA"
authors: 
  - Andrea Baiocchi
  - admin
date: 2023-01-31
doi: "10.1109/TNET.2023.3239410"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-01-31T00:00:00+01:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Networking"
publication_short: "IEEE/ACM Transactions on Networking"

abstract: "Medium Access Control (MAC) main functions encompass contention for channel access, packet scheduling, error control, and data integrity. Channel contention is a collective function involving all stations in the network, while data integrity pertains to data flows of each individual station. We propose a design where contention related functions are separated from other data management functions. The hinge connecting contention and other data management functions is a flow control algorithm, aiming at guaranteeing stability of contention queues and load on the MAC channel. With reference to Carrier-Sense Multiple Access (CSMA), we define an analytical model of contention queues under non saturated traffic. An asymptotic analysis of the model for large number of stations yields a closed form of the optimal flow control rate. The insight gained from the model is used to design an adaptive flow control algorithm that guarantees throughput optimality for all values of the number of stations."

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
