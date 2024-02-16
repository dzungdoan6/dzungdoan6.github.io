---
title: 'G2D: from GTA to Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Abdul Mohsi Jawaid
  - Thanh-Toan Do
  - Tat-Jun Chin

# Author notes (optional)
author_notes:

date: '2018-06-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-06-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: This document describes G2D, a software that enables capturing videos from Grand Theft Auto V (GTA V), a popular role playing game set in an expansive virtual city. The target users of our software are computer vision researchers who wish to collect hyper-realistic computer-generated imagery of a city from the street level, under controlled 6DOF camera poses and varying environmental conditions (weather, season, time of day, traffic density, etc.). G2D accesses/calls the native functions of the game; hence users can directly interact with G2D while playing the game. Specifically, G2D enables users to manipulate conditions of the virtual environment on the fly, while the gameplay camera is set to automatically retrace a predetermined 6DOF camera pose trajectory within the game coordinate system. Concurrently, automatic screen capture is executed while the virtual environment is being explored. G2D and its source code are publicly available [here](https://github.com/dzungdoan6/G2D). In addition, we demonstrate an application of G2D to generate a large-scale dataset with groundtruth camera poses for testing structure-from-motion (SfM) algorithms. The dataset and generated 3D point clouds are also made available [here](https://drive.google.com/drive/folders/1jSn_zlbqPERadjL_LI22QkjN_naiOIGT)

# Summary. An optional shortened abstract.
summary: 
    Present a software to collect simulated data from computer game GTA V. Users have fully control of camera poses and environmental conditions.

tags: 
- Dataset
- Localisation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1806.07381.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://sites.google.com/view/g2d-software/home'
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
