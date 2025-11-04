---
title: 'DinoAtten3D: Slice-Level Attention Aggregation of DinoV2 for 3D Brain MRI Anomaly Classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jay Shah
  - Catherine D. Chong
  - Todd J. Schwedt
  - Teresa Wu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-07-10T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '22025-07-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: Anomaly detection and classification in medical imaging are critical for early diagnosis but remain challenging due to limited annotated data, class imbalance, and the high cost of expert labeling. Emerging vision foundation models such as DINOv2, pretrained on extensive, unlabeled datasets, offer generalized representations that can potentially alleviate these limitations. In this study, we propose an attention-based global aggregation framework tailored specifically for 3D medical image anomaly classification. Leveraging the self-supervised DINOv2 model as a pretrained feature extractor, our method processes individual 2D axial slices of brain MRIs, assigning adaptive slice-level importance weights through a soft attention mechanism. To further address data scarcity, we employ a composite loss function combining supervised contrastive learning with class-variance regularization, enhancing inter-class separability and intra-class consistency. We validate our framework on the ADNI dataset and an institutional multi-class headache cohort, demonstrating strong anomaly classification performance despite limited data availability and significant class imbalance. Our results highlight the efficacy of utilizing pretrained 2D foundation models combined with attention-based slice aggregation for robust volumetric anomaly detection in medical imaging

# Summary. An optional shortened abstract.
summary: |

tags:
  - Computer Vision

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://openaccess.thecvf.com/content/ICCV2025W/ADFM/papers/Rafsani_DinoAtten3D_Slice-Level_Attention_Aggregation_of_DinoV2_for_3D_Brain_MRI_ICCVW_2025_paper.pdf"
  - type: code
    url: https://github.com/Rafsani/DinoAtten3D.git

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
