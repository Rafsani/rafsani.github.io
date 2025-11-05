---
title: "AUCp: Pseudo-AUC for Inference Model Selection with Unlabeled Validation Data in Abnormality Detection"
authors:
- Md Mahfuzur Rahman Siddiquee
- admin
- Jay Shah
- Catherine D. Chong
- Todd J. Schwedt
- Teresa Wu
- Baoxin Li
 
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2025-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to IEEE Transactions of Medical Images"
publication_short: "IEEE TMI"

abstract:   Abnormality detection is a crucial yet challenging task in medical image analysis. Distinguishing abnormalities from normal data by learning to reconstruct normal-only data alleviates the reliance on labeled datasets. However, many studies, even if unsupervised, rely on a labeled validation set to select the best model for inference from multiple training iterations. For many diseases labeled data are unavailable and substantially time consuming to obtain. To address this,  AUCp - a novel metric that supports abnormality detection for unsupervised and self-supervised methods is proposed. Instead of evaluating the realism of reconstructed images to select the best of model for inference, it focuses on actual detection performance and without requiring an annotated test set. Assuming the pseudo ground truth of all unannotated samples in the test set as abnormal/positive and using traditional AUCcalculation,  AUCp scores are derived. Given a large and representative training set of normal samples, we show mathematical and empirical evidence that model selection using AUCp scores improves disease detection in terms of unsupervised and self-supervised methods over conventional metrics. Using two unsupervised methods for neurologic disease detection and self-supervised methods on diverse datasets, our results demonstrate that the AUCp score effectively identifies the optimal model for inference, significantly enhancing abnormality and disease detection.
# Summary. An optional shortened abstract.
summary: |

tags:
- anomaly detection
featured: false

hugoblox:
  ids:
    arxiv: 1512.04133v1

links:
  - type: pdf
    url: https://www.nature.com/articles/s41598-025-18507-81


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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

