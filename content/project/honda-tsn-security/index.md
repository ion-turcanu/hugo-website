---
title: TSN Security
summary: Evaluating Practical Attacks against TSN in a TSN-enabled Testbed
tags:
  - TSN
  - Automotive Ethernet
  - Testbed
  - Prototype
  - Finished
date: '2020-01-01T00:00:00Z'

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

Ethernet is easily the most popular Local Area Network (LAN) technology today.
It has been first introduced commercially in 1980, supporting a maximum data rate of 3 Mbit/s.
Since then it continuously evolved, arriving to support today data rates of up to 400 Gbit/s.
Due to the rapid development of new automotive applications and services demanding more and more bandwidth, Ethernet has become an attractive candidate technology to extend the capabilities of the next generation automotive networks.

An important part of making Ethernet a promising option for automotive networks is the work done in the IEEE Time-Sensitive Networking (TSN) working group. 
While Ethernet typically just offers a best effort service, TSN allows deterministic services over Ethernet, which includes guaranteed packet transport with bounded latency, low packet delay variation (jitter), and low packet loss.
However, security aspects, which are also an integral part of making Ethernet succeed as automotive technology, have been neglected so far.
While IEEE specified promising security technologies such as 802.1X (access control) and 802.1AE (MACsec, media access control security), there is no standard combining security technologies with TSN.

The purpose of this project is motivating the need for further research in the field of combining TSN with security technologies by demonstrating several powerful yet easy-to-perform attacks against an unsecured TSN test bed.
This is further motivated by the IEEE also considering this an important point, which is shown by the fact that a new working group with the goal of specifying a secure TSN profile for automotive networks emerged

<i class="fa-solid fa-calendar-days"></i> **Project duration:** 01.01.2020 - 31.03.2020

<i class="fa-solid fa-money-bill"></i> **Funding:** Honda R&D Europe (Germany)