---
title: 'AnoFPDM: Anomaly Detection with Forward Process of Diffusion Models for Brain MRI'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yiming Che
  - admin
  - Jay Shah
  - Md Mahfuzur Rahman Siddiquee
  - Teresa Wu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-07-10T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the Winter Conference on Applications of Computer Vision 2025
publication_short: In WACV 2025

abstract: Weakly-supervised diffusion models (DMs) in anomaly segmentation, leveraging image-level labels, have attracted significant attention for their superior performance compared to unsupervised methods. It eliminates the need for pixel-level labels in training, offering a more cost-effective alternative to supervised methods. However, existing methods are not fully weakly-supervised because they heavily rely on costly pixel-level labels for hyperparameter tuning in inference. To tackle this challenge, we introduce Anomaly Segmentation with Forward Process of Diffusion Models (AnoFPDM), a fully weakly-supervised framework that operates without the need of pixel-level labels. Leveraging the unguided forward process as a reference for the guided forward process, we select hyperparameters such as the noise scale, the threshold for segmentation and the guidance strength. We aggregate anomaly maps from guided forward process, enhancing the signal strength of anomalous regions. Remarkably, our proposed method outperforms recent state-of-the-art weakly-supervised approaches, even without utilizing pixel-level labels.

# Summary. An optional shortened abstract.
summary: |

tags:
  - Computer Vision

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://arxiv.org/abs/2404.15683"
  - type: code
    url: "https://github.com/SoloChe/AnoFPDM.git"


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
