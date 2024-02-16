---
title: 'On-Device Scalable Image-Based Localization via Prioritized Cascade Search and Fast One-Many RANSAC'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ngoc-Trung Tran
  - Dang-Khoa Le Tan
  - admin
  - Thanh-Toan Do
  - Tuan-Anh Bui
  - Mengxuan Tan
  - Ngai-Man Cheung
  
# Author notes (optional)
author_notes:

date: '2018-11-18T00:00:00Z'
doi: 'https://doi.org/10.1109/TIP.2018.2881829'

# Schedule page publish date (NOT publication's date).
publishDate: '2018-11-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing 2018*
publication_short: In *TIP*

abstract: We present the design of an entire on-device system for large-scale urban localization using images. The proposed design integrates compact image retrieval and 2D–3D correspondence search to estimate the location in extensive city regions. Our design is GPS agnostic and does not require network connection. In order to overcome the resource constraints of mobile devices, we propose a system design that leverages the scalability advantage of image retrieval and accuracy of 3D model-based localization. Furthermore, we propose a new hashing-based cascade search for fast computation of 2D–3D correspondences. In addition, we propose a new one-many RANSAC for accurate pose estimation. The new one-many RANSAC addresses the challenge of repetitive building structures (e.g. windows and balconies) in urban localization. Extensive experiments demonstrate that our 2D–3D correspondence search achieves the state-of-the-art localization accuracy on multiple benchmark datasets. Furthermore, our experiments on a large Google street view image dataset show the potential of large-scale localization entirely on a typical mobile device.

# Summary. An optional shortened abstract.
summary: 
    Develop an on-device system for large-scale visual localisation
    <br>
    <span style="font-size:1.1em">_IEEE Transactions on Image Processing 2018_</span>.

tags: 
- Localisation
- Edge AI

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1802.03510.pdf'
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
  preview_only: true

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
