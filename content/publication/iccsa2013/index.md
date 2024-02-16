---
title: 'Combining Descriptors Extracted from Feature Maps of Deconvolutional Networks and SIFT Descriptors in Scene Image Classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ngoc-Trung Tran
  - Dinh-Phong Vo
  - Bac Le
  - Atsuo Yoshitaka 

# Author notes (optional)
author_notes:

date: '2013-09-08T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-642-39640-3_24'

# Schedule page publish date (NOT publication's date).
publishDate: '2013-09-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computational Science and Its Applications (ICCSA 2013)*
publication_short: In *ICCSA*

abstract: This paper presents a new method to combine descriptors extracted from feature maps of Deconvolutional Networks and SIFT descriptors by converting them into histograms of local patterns, so the concatenation operation can be applied and ensure to increase the classification rate. We use K-means clustering algorithm to construct codebooks and compute Spatial Histograms to represent the distribution of local patterns in an image. Consequently, we can concatenate these histograms to make a new one that represents more local patterns than the originals. In the classification step, SVM associated with Histogram Intersection Kernel is utilized. In the experiments on Scene-15 Dataset containing 15 categories, the classification rates of our method are around 84% which outperforms Reconfigurable Bag-of-Words (RBoW), Sparse Covariance Patterns (SCP), Spatial Pyramid Matching (SPM), Spatial Pyramid Matching using Sparse Coding (ScSPM) and Visual Word Reweighting (VWR).

# Summary. An optional shortened abstract.
summary:  
    <span style="font-size:1.1em">In _ICCSA 2013_</span>

tags: 

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
