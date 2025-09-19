---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Rethinking Persistent Scheduling in 5G New Radio Vehicle-to-Everything Sidelink Communications"
authors:
  - Alexey Rolich
  - Mert Yildiz
  - admin
  - Alexey Vinel
  - Andrea Baiocchi

date: 2025-09-18
doi: "10.1109/ACCESS.2025.3611486"

# Schedule page publish date (NOT publication's date).
publishDate: 2025-09-18T00:00:00+01:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: "IEEE Access"

abstract: "5G New Radio (NR) Vehicle-to-Everything (V2X) Mode 2 relies on Semi-Persistent Scheduling (SPS) to manage sidelink resources, with persistence playing a key role in affecting communication integrity and Age of Information (AoI) for connected and autonomous vehicles. However, its impact remains underexplored, and whether to include SPS as is in future standards remains an open issue, calling for a deeper understanding of its effects. In this paper, we introduce a simpler method for implementing the persistence concept in 5G NR-V2X Mode 2, providing a broader range of persistence degrees than standard SPS. Through ns-3 simulations, we show that higher persistence improves communication stability, but it degrades the AoI by slowing sub-channel switching. Conversely, weaker persistence strikes a better balance between collision occurrence rate and collision duration, minimizing AoI. Crucially, our results reveal that Dynamic Scheduling (DS) can outperform SPS even for strictly periodic traffic flows, challenging the longstanding assumption that SPS is optimal in such scenarios. In fact, it turns out that persistent collisions boost message delivery burstiness, creating large gaps in the flow of delivered update messages. Our findings offer clearer guidance on designing simpler, more effective sidelink multiple access strategies to improve communication timeliness."

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
