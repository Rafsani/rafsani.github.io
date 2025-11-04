---
title: "Leveraging multi-modal foundation model image encoders to enhance brain MRI-based headache classification"
authors:
- admin
-  Devam Sheth
- Yiming Che
- Jay Shah
- Md Mahfuzur Rahman Siddiquee
- Catherine D. Chong
- Simona Nikolova
- Katherine Ross
- Gina Dumkrieger
- Baoxin Li
- Teresa Wu
- Todd J. Schwedt 
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: Headaches are a nearly universal human experience traditionally diagnosed based solely on symptoms. Recent advances in imaging techniques and artificial intelligence (AI) have enabled the development of automated headache detection systems, which can enhance clinical diagnosis, especially when symptom-based evaluations are insufficient. Current AI models often require extensive data, limiting their clinical applicability where data availability is low. However, deep learning models, particularly pre-trained ones and fine-tuned with smaller, targeted datasets can potentially overcome this limitation. By leveraging BioMedCLIP, a pre-trained foundational model combining a vision transformer (ViT) image encoder with PubMedBERT text encoder, we fine-tuned the pre-trained ViT model for the specific purpose of classifying headaches and detecting biomarkers from brain MRI data. The dataset consisted of 721 individuals: 424 healthy controls (HC) from the IXI dataset and 297 local participants, including migraine sufferers (n = 96), individuals with acute post-traumatic headache (APTH, n = 48), persistent post-traumatic headache (PPTH, n = 49), and additional HC (n = 104). The model achieved high accuracy across multiple balanced test sets, including 89.96% accuracy for migraine versus HC, 88.13% for APTH versus HC, and 83.13% for PPTH versus HC, all validated through five-fold cross-validation for robustness. Brain regions identified by Gradient-weighted Class Activation Mapping analysis as responsible for migraine classification included the postcentral cortex, supramarginal gyrus, superior temporal cortex, and precuneus cortex; for APTH, rostral middle frontal and precentral cortices; and, for PPTH, cerebellar cortex and precentral cortex. To our knowledge, this is the first study to leverage a multimodal biomedical foundation model in the context of headache classification and biomarker detection using structural MRI, offering complementary insights into the causes and brain changes associated with headache disorders.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

hugoblox:
  ids:
    arxiv: 1512.04133v1

links:
  - type: pdf
    url: https://www.nature.com/articles/s41598-025-18507-81


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

