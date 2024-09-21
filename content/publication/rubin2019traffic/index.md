---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Traffic management and networking for autonomous vehicular highway systems"
authors:
  - Izhak Rubin
  - Andrea Baiocchi
  - Yulia Sunyoto
  - admin
date: 2019-02-01
doi: "10.1016/j.adhoc.2018.08.018"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-07T16:42:14+01:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Elsevier Ad Hoc Networks"
publication_short: "Elsevier Ad Hoc Networks"

abstract: "We develop traffic management and data networking mechanisms and study their integrated design for an autonomous transportation system. The traffic management model involves a multi-lane multi-segment highway. Ramp managers regulate admission of vehicles into the highway and their routing to designated lanes. Vehicles moving across each lane are organized into platoons. A Platoon Leader (PL) is elected in each platoon and is used to manage its members and their communications with the infrastructure and with vehicles in other platoons. We develop new methods that are employed to determine the structural formations of platoons and their mobility processes in each lane, aiming to maximize the realized flow rate under vehicular end-to-end delay constraints. We set a limit on the vehicular on-ramp queueing delay and on the (per unit distance) transit time incurred along the highway. We make use of the platoon formations to develop new Vehicle-to-Vehicle (V2V) wireless networking cross-layer schemes that are used to disseminate messages among vehicles traveling within a specified neighborhood. For this purpose, we develop algorithms that configure a hierarchical networking architecture for the autonomous system. Certain platoon leaders are dynamically assigned to act as Backbone Nodes (BNs). The latter are interconnected by communications links to form a Backbone Network (Bnet). Each BN serves as an access point for its Access Network (Anet), which consists of its mobile clients. We study the delay-throughput performance behavior of the network system and determine the optimal setting of its parameters, assuming both TDMA and IEEE 802.11p oriented wireless channel sharing (MAC) schemes. Integrating these traffic management and data networking mechanisms, we demonstrate the performance tradeoffs available to the system designer and manager when aiming to synthesize an autonomous transportation system operation that achieves targeted vehicular flow rates and transit delays while also setting the data communications network system to meet targeted message throughput and delay objectives."

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
