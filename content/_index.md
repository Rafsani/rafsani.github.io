---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        #education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
        date_format: 'January 2006'
        # Education or Experience section first?
        is_education_first: true
  - block: markdown
    content:
      title: '📚 Research'
      subtitle: ''
      text: |-
        Fazle Rafsani’s research centers on advancing foundation and generative models for medical image analysis, with a focus on improving automated diagnosis and interpretability in healthcare. As a Ph.D. student and research associate at the ASU-Mayo Center for Innovative Imaging (AMCII), his work integrates computer vision, deep learning, and multimodal learning to analyze complex medical imaging data such as MRI and CT scans.

        His contributions include developing DinoAtten3D, a slice-level attention aggregation framework that enhances 3D brain MRI anomaly classification, and AnoFPDM, a diffusion-based anomaly detection method that removes the need for pixel-level supervision. Through NIH- and DoD-funded projects, he applies foundation models like BioMedCLIP and MedSAM to tasks such as headache subtype prediction and thyroid nodule segmentation, emphasizing model interpretability through Grad-CAM-based biomarker visualization.

        Rafsani’s research bridges cutting-edge vision transformers, contrastive learning, and diffusion models to create scalable, data-efficient solutions for neurological disorder diagnosis.   His work has appeared in top venues including ICCV, WACV, and Nature Scientific Reports, reflecting both scientific innovation and translational impact toward clinically explainable AI systems in medical imaging.

    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: markdown
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
    #   page_type: blog
    #   # Choose how many pages you would like to display (0 = all pages)
    #   count: 5
    #   # Filter on criteria
    #   filters:
    #     author: ''
    #     category: ''
    #     tag: ''
    #     exclude_featured: false
    #     exclude_future: false
    #     exclude_past: false
    #     publication_type: ''
    #   # Choose how many pages you would like to offset by
    #   offset: 0
    #   # Page order: descending (desc) or ascending (asc) date.
    #   order: desc
    # # design:
    # #   # Choose a layout view
    # #   view: card
    # #   # Reduce spacing
    # #   spacing:
    # #     padding: [0, 0, 0, 0]

    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
