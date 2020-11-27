---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "复杂网络中的扰动传播"
summary: " "
authors: [ ]
tags: ["半解析"]
categories: [ ]
date: 2020-11-26T22:39:36+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "与网络结构无关的扰动传播主曲线"
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

向平静的池塘丢一颗石子，会激起层层涟漪在水面荡漾开来。想象一下，对于一个处于稳态的复杂网络，如果我们“拨动”其中的一个节点，那么产生的扰动会如何在复杂的网络结构中传播呢？一个处在网络另一端的节点，会在多长时间之后“感受”到这个扰动呢？

我们通过分析扩散耦合的网络瞬态线性响应，并结合网络响应的数值模拟，得到了与网络具体结构无关的扰动传播的主曲线。运用这条曲线，我们就能精确预测任意未知网络的扰动传播过程 ([Zhang et al., *Phys. Rev. Lett.* 2020]({{< ref "/publication/zhang2020topological/index.md" >}}))。