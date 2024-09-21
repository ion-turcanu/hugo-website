---
title: Building an In-Car Ethernet Testbed System
summary:
tags:
  - TSN
  - Automotive Ethernet
  - Testbed
  - Prototype
  - Finished
date: '2018-05-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

#links:
#  - name: 
#    url: 
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---

Nowadays, cars are becoming increasingly dependent on embedded computers, sensors, cameras, Light Imaging, Detection, And Ranging (LIDAR), etc. to enable safe and comfortable journeys for drivers and passengers.
Moreover, self-driving cars will hit our roads in the coming years, which will require an increasing number of advanced sensors and high resolution camera systems.

To integrate these features into cars and to ensure the delivery of bandwidth-hungry and delay-sensitive traffic, it is a necessity to have reliable, deterministic and bandwidth-guarantee communication protocols.
Current communication technologies adopted by car manufacturers include Controller Area Network (CAN), Local Interconnect Network (LIN), Media Oriented Serial Transport (MOST), and FlexRay.
The main limitation of these technologies is that, at the time of their conception, they were not tailored with the sharp rise of high-bandwidth applications.

To support the above mentioned requirements, in-car networks have to undergo significant changes.
The inherent features of Ethernet, such as increased bandwidth, low cost and flexibility, makes it a potential candidate to substitute or complement existing in-car communication technologies.
Recently, several Ethernet-based protocols have been proposed, such as Audio Video Bridging (AVB)/Time-Sensitive Networking (TSN) and Time-Triggered Ethernet (TTEthernet).
It was demonstrated by several simulation studies that AVB/TSN is able to support high volumes of data while fulfilling critical timing constraints.
The aim of this project is to build an in-car testbed for testing automotive Ethernet-based solutions and for carrying out realistic traffic load experiments that reflect upcoming in-car communications.
To this end, selected open-source Automotive Ethernet protocols will be deployed, while different Ethernet-based topologies will be investigated and evaluated.

<i class="fa-solid fa-calendar-days"></i> **Project duration:** 01.05.2018 - 30.04.2019

<i class="fa-solid fa-money-bill"></i> **Funding:** Honda R&D Europe (Germany)