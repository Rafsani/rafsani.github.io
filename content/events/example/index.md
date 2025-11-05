---
title: Presented DinoAtten3D in ICCV 2025 @ Honolulu, Hawaii

event: ICCV 2025
event_url: https://example.org

location: Honolulu Convention center
address:
  street: Honolulu
  city: Stanford
  region: Hawaii
  postcode: '94305'
  country: United States

summary: Presented my research work on Anomaly Detection using DinoV2 for Brain MRI
abstract: 'In this study, we propose an attention-based global aggregation framework tailored specifically for 3D medical image anomaly classification. Leveraging the self-supervised DINOv2 model as a pretrained feature extractor, our method processes individual 2D axial slices of brain MRIs, assigning adaptive slice-level importance weights through a soft attention mechanism. To further address data scarcity, we employ a composite loss function combining supervised contrastive learning with class-variance regularization, enhancing inter-class separability and intra-class consistency. We validate our framework on the ADNI dataset and an institutional multi-class headache cohort, demonstrating strong anomaly classification performance despite limited data availability and significant class imbalance. Our results highlight the efficacy of utilizing pretrained 2D foundation models combined with attention-based slice aggregation for robust volumetric anomaly detection in medical imaging.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-10-01T13:00:00Z'
date_end: '2025-10-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-10-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
  - type: code
    url: https://github.com
  - type: slides
    url: https://slideshare.net
  - type: video
    url: https://youtube.com

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

