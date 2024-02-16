---
title: 'Domain Adaptation for Satellite-Borne Hyperspectral Cloud Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Andrew Du
  - admin
  - Yee Wei Law
  - Tat-Jun Chin

# Author notes (optional)
author_notes:

date: '2023-09-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The advent of satellite-borne machine learning hardware accelerators has enabled the on-board processing of payload data using machine learning techniques such as convolutional neural networks (CNN). A notable example is using a CNN to detect the presence of clouds in hyperspectral data captured on Earth observation (EO) missions, whereby only clear sky data is downlinked to conserve bandwidth. However, prior to deployment, new missions that employ new sensors will not have enough representative datasets to train a CNN model, while a model trained solely on data from previous missions will underperform when deployed to process the data on the new missions. This underperformance stems from the domain gap, i.e., differences in the underlying distributions of the data generated by the different sensors in previous and future missions. In this paper, we address the domain gap problem in the context of on-board hyperspectral cloud detection. Our main contributions lie in formulating new domain adaptation tasks that are motivated by a concrete EO mission, developing a novel algorithm for bandwidth-efficient supervised domain adaptation, and demonstrating test-time adaptation algorithms on space deployable neural network accelerators. Our contributions enable minimal data transmission to be invoked (e.g., only 1% of the weights in ResNet50) to achieve domain adaptation, thereby allowing more sophisticated CNN models to be deployed and updated on satellites without being hampered by domain gap and bandwidth limitations.

# Summary. An optional shortened abstract.
summary: 
    Develop a novel algorithm for bandwidth-efficient supervised domain adaptation, and demonstrate test-time adaptation on space deployable neural network accelerators.

tags: 
- Domain Adaptation
- Earth Observation

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2309.02150.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 
  focal_point: ''
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
slides: []
---