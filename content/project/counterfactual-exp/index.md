---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Counterfactual Explanations"
summary: ""
authors: []
tags: []
categories: []
date: 2021-07-12T16:33:11+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
The idea of _counterfactual_ (CF) explanations is to reveal the rationale behind the outputs provided by machine learning (ML) predictive models in response to individual inputs in the form: "_If_ **A** _had been different,_ **B** _would not have occurred_". CF explanations are based on CF examples: slightly modified versions of an input sample (yet "close" to it) that result in an alternative output response from the predictive model. 
The goal of this project is to design innovative methods for generating such CF examples _efficiently_. A promising research direction is that of framing this problem into a _reinforcement learning_ (RL) framework.
