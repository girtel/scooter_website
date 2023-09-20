---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Impact of SCHC Compression and Fragmentation in LPWAN: A Case Study with LoRaWAN'
subtitle: ''
summary: ''
authors:
- Jesus Sanchez-Gomez
- Jorge Gallego-Madrid
- Ramon Sanchez-Iborra
- Jose Santa
- Antonio F. Skarmeta
tags: []
categories: []
date: '2020-01-01'
lastmod: 2023-09-18T12:04:43+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-09-18T10:04:43.147955Z'
publication_types:
- '2'
abstract: The dawn of the Internet of Things (IoT) paradigm has brought about a series
  of novel services never imagined until recently. However, certain deployments such
  as those employing Low-Power Wide-Area Network (LPWAN)-based technologies may present
  severe network restrictions in terms of throughput and supported packet length.
  This situation prompts the isolation of LPWAN systems on islands with limited interoperability
  with the Internet. For that reason, the IETF’s LPWAN working group has proposed
  a Static Context Header Compression (SCHC) scheme that permits compression and fragmentation
  of and IPv6/UDP/CoAP packets with the aim of making them suitable for transmission
  over the restricted links of LPWANs. Given the impact that such a solution can have
  in many IoT scenarios, this paper addresses its real evaluation in terms not only
  of latency and delivery ratio improvements, as a consequence of different compression
  and fragmentation levels, but also of the overhead in end node resources and useful
  payload sent per fragment. This has been carried out with the implementation of
  middleware and using a real testbed implementation of a LoRaWAN-to-IPv6 architecture
  together with a publish/subscribe broker for CoAP. The attained results show the
  advantages of SCHC, and sustain discussion regarding the impact of different SCHC
  and LoRaWAN configurations on the performance. It is highlighted that necessary
  end node resources are low as compared to the benefit of delivering long IPv6 packets
  over the LPWAN links. In turn, fragmentation can impose a lack of efficiency in
  terms of data and energy and, hence, a cross-layer solution is needed in order to
  obtain the best throughput of the network.
doi: 10.3390/s20010280
publication: '*Sensors*, Vol. 20, No. 1, DOI: 10.3390/s20010280'
links:
- name: URL
  url: https://www.mdpi.com/1424-8220/20/1/280
---
