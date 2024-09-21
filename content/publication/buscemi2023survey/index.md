---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Survey on Controller Area Network Reverse Engineering"
authors:
  - Alessio Buscemi
  - admin
  - German Castignani
  - Andriy Panchenko
  - Thomas Engel
  - Kang G. Shin
date: 2023-04-05
doi: "10.1109/COMST.2023.3264928"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-04-12T00:00:00+01:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Communications Surveys & Tutorials"
publication_short: "IEEE Communications Surveys & Tutorials"

abstract: "Controller Area Network (CAN) is a masterless serial bus designed and widely used for the exchange of mission and time-critical information within commercial vehicles. Invehicle communication is based on messages sent and received by Electronic Control Units (ECUs) connected to this serial bus network. Although unencrypted, CAN messages are not easy to interpret. In fact, Original Equipment Manufacturers (OEMs) attempt to achieve security through obscurity by encoding the data in their proprietary format, which is kept secret from the general public. As a result, the only way to obtain clear data is to reverse engineer CAN messages. Driven by the need for in-vehicle message interpretation, which is highly valuable in the automotive industry, researchers and companies have been working to make this process automated, fast, and standardized. In this paper, we provide a comprehensive review of the state of the art and summarize the major advances in CAN bus reverse engineering. We are the first to provide a taxonomy of CAN tokenization and translation techniques. Based on the reviewed literature, we highlight an important issue: the lack of a public and standardized dataset for the quantitative evaluation of translation algorithms. In response, we define a complete set of requirements for standardizing the data collection process. We also investigate the risks associated with the automation of CAN reverse engineering, in particular with respect to the security network and the safety and privacy of drivers and passengers. Finally, we discuss future research directions in CAN reverse engineering."

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
