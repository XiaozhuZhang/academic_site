---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "复杂网络的系统风险评估"
summary: " "
authors: [ ]
tags: ["纯解析"]
categories: []
date: 2020-11-26

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "动态脆弱性指数DVI（右）vs. 节点最高响应（左）"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

在一个交流电网中，一个风电厂的波动性电力输出可能会在不同节点引起不同幅度的共振性频率波动 ([Zhang et al., *Sci. Adv.* 2019]({{< ref "/publication/zhang2019fluctuation/index.md" >}}))。由于风电输出时间序列的随机性，这些频率波动的时间序列同样是随机而难以预测的。然而，如果这些波动超过了安全阈值，将会导致电网中其他机组的损坏，从而影响整个电网系统的稳定。我们能否用一个指数来估计这一系统性风险，即哪些节点动态脆弱性更大，会表现出最大的共振性频率偏差呢？

我们提出了复杂网络的“动态脆弱性指数(DVI)”，用来评估一个复杂网络中不同节点对具有特定频谱的随机扰动的最大响应值排序 ([Zhang et al., *Chaos* 2020]({{< ref "/publication/zhang2020vulnerability/index.md" >}}))。



