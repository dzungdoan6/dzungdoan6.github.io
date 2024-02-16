---
title: 'HM4: Hidden Markov Model With Memory Management for Visual Place Recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yasir Latif
  - Tat-Jun Chin
  - Ian Reid
  
# Author notes (optional)
author_notes:

date: '2021-01-11T00:00:00Z'
doi: 'https://doi.org/10.1109/LRA.2020.3036615'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics and Automation Letters* <span style="color:red">**(Best Paper Award)**</span>.
publication_short: In *RA-L*

abstract: Visual place recognition needs to be robust against appearance variability due to natural and man-made causes. Training data collection should thus be an ongoing process to allow continuous appearance changes to be recorded. However, this creates an unboundedly-growing database that poses time and memory scalability challenges for place recognition methods. To tackle the scalability issue for visual place recognition in autonomous driving, we develop a Hidden Markov Model approach with a two-tiered memory management. Our algorithm, dubbed HM 4 , exploits temporal look-ahead to transfer promising candidate images between passive storage and active memory when needed. The inference process takes into account both promising images and a coarse representations of the full database. We show that this allows constant time and space inference for a fixed coverage area. The coarse representations can also be updated incrementally to absorb new data. To further reduce the memory requirements, we derive a compact image representation inspired by Locality Sensitive Hashing (LSH). Through experiments on real world data, we demonstrate the excellent scalability and accuracy of the approach under appearance changes and provide comparisons against state-of-the-art techniques.

# Summary. An optional shortened abstract.
summary: 
    Achieve a lightweight & scalable solution for place recognition
    <br>
    <span style="font-size:1.1em">_IEEE Robotics and Automation Letters_</span>. <span style="color:red;font-size:1.1em">**(Best Paper Award)**</span>.

tags: 
- Localisation
- Hidden Markov Model

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2011.00450.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://sites.google.com/view/scalable-place-recognition/home'
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
