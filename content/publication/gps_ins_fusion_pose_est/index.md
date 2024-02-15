---
title: 'Outlier-Robust Manifold Pre-Integration for INS/GPS Fusion'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shin-Fang Ch’ng
  - Alireza Khosravian
  - admin
  - Tat-Jun Chin

# Author notes (optional)
author_notes:

date: '2019-09-08T00:00:00Z'
doi: 'https://doi.org/10.1109/IROS40897.2019.8967643'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-09-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2019)*
publication_short: In *IROS*

abstract: We tackle the INS/GPS sensor fusion problem for pose estimation, particularly in the common setting where the INS components (IMU and magnetometer) function at much higher frequencies than GPS, and where the magnetometer and GPS are prone to giving erroneous measurements (outliers) due to magnetic disturbances and glitches. Our main contribution is a novel non-linear optimization framework that (1) fuses pre-integrated IMU and magnetometer measurements with GPS, in a manner that respects the manifold structure of the state space; and (2) supports the usage of robust norms and efficient large scale optimization to effectively mitigate the effects of outliers. Through extensive experiments, we demonstrate the superior accuracy and robustness of our approach over filtering methods (which are customarily applied in the target setting) with minimal impact to computational efficiency. Our work further illustrates the strength of optimization approaches in state estimation problems and paves the way for their adoption in the control and navigation communities.

# Summary. An optional shortened abstract.
summary: 
    We propose an efficient outlier-robust algorithm to tackle INS and GPS sensor fusion problem for pose estimation.
    <br> 
    <span style="font-size:1.1em">In _IROS 2019_</span>

tags: 
- Localisation
- Sensor Fusion
- Optimisation

# Display this page in the Featured widget?
featured: true

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
