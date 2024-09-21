---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Age of Information in CSMA-based Networks with Bursty Update Traffic"
authors: 
  - Andrea Baiocchi
  - admin
  - Alexey Vinel
date: 2022-04-18
doi: "10.1109/ACCESS.2022.3168321"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-04-28T00:00:00+01:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: "IEEE Access"

abstract: "Exchanging status information between closely located mobile agents is an underlying process in numerous future Cyber Physical Systems (CPS). Real-time updates including positions of neighboring nodes is performed when, for example, autonomous vehicles execute a cooperative maneuver, industrial robots collaborate with each other on a task, or Unmanned Aerial Vehicles (UAVs) execute a mission in a swarm. For the design of networked automatic control strategies in these scenarios, it is essential to understand the performance of such Machine-to-Machine (M2M) communications from the information freshness perspective. To this end, we introduce a mathematical framework which allows characterizing the Age of Information (AoI) in networks governed by the Carrier-Sense Multiple Access (CSMA) protocol. Differently from existing work, we take into account the fact that update packets sent by mobile nodes are not necessarily periodic, since packet triggering is often coupled with agents’ mobility. Our approach is based on the assumption that diverse mobility-triggered message generation patterns can be modeled by a wide class of update traffic arrival processes. We apply Discrete Markovian Arrival Process (DMAP), which is a versatile arrival model able to fit arrival patterns that are modulated by a finite state machine, including bursty traffic. We develop an accurate and efficient analytical model of nodes exchanging one-hop broadcast update messages with bursty arrivals to evaluate the moments as well as entire probability distribution of several performance metrics, including AoI. An asymptotic analysis for large networks suggests a simple way to control the update message rate to minimize the AoI. We show that the optimal update rate that minimizes the mean AoI coincides with the optimum of the wireless channel utilization. Numerical examples point out that the asymptotic theory provides accurate predictions also for small values of the number of nodes."

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
