---
title: 'SPRINT: Subgraph Place Recognition for INtelligent Transportation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yasir Latif
  - admin
  - Tat-Jun Chin
  - Ian Reid 
  
# Author notes (optional)
author_notes:

date: '2020-08-31T00:00:00Z'
doi: 'https://doi.org/10.1109/ICRA40945.2020.9196522'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-31T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation (ICRA 2020)*
publication_short: In *ICRA*

abstract: Visual place recognition is an important problem in mobile robotics which aims to localize a robot using image information alone. Recent methods have shown promising results for place recognition under varying environmental conditions by exploiting the sequential nature of the image acquisition process. We show that by using k nearest neighbours based image retrieval as the backend, and exploiting the structure of the image acquisition process which introduces temporal relations between images in the database, the location of possible matches can be restricted to a subset of all the images seen so far. In effect, the original problem space can thus be restricted to a significantly smaller subspace, reducing the inference time significantly. This is particularly important for scalable place recognition over databases containing millions of images. We present large scale experiments using publicly sourced data that show the computational performance of the proposed method under varying environmental conditions.

# Summary. An optional shortened abstract.
summary: 
    Explore the sparsity of topological map to improve the inference time for place recognition
    <br>
    <span style="font-size:1.1em">In _ICRA 2020_</span>

tags: 
- Localisation
- Hidden Markov Model

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
