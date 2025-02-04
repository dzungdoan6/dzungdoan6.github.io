---
title: 'Visual localization under appearance change: filtering approaches'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yasir Latif
  - Tat-Jun Chin
  - Yu Liu
  - Shin-Fang Ch'ng 
  - Thanh-Toan Do
  - Ian Reid
  
# Author notes (optional)
author_notes:

date: '2020-09-17T00:00:00Z'
doi: 'https://doi.org/10.1007/s00521-020-05339-y'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-09-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Neural Computing and Applications 2020* (Special Issue on Best of DICTA 2019)
publication_short: In *NCAA*

abstract: A major focus of current research on place recognition is visual localization for autonomous driving. In this scenario, as cameras will be operating continuously, it is realistic to expect videos as an input to visual localization algorithms, as opposed to the single-image querying approach used in other visual localization works. In this paper, we show that exploiting temporal continuity in the testing sequence significantly improves visual localization—qualitatively and quantitatively. Although intuitive, this idea has not been fully explored in recent works. To this end, we propose two filtering approaches to exploit the temporal smoothness of image sequences<span>:</span> (i) filtering on discrete domain with hidden Markov model, and (ii) filtering on continuous domain with Monte Carlo-based visual localization. Our approaches rely on local features with an encoding technique to represent an image as a single vector. The experimental results on synthetic and real datasets show that our proposed methods achieve better results than state of the art (i.e., deep learning-based pose regression approaches) for the task on visual localization under significant appearance change. Our synthetic dataset and source code are made publicly available [here](https://sites.google.com/view/g2d-software/home) and [here](https://github.com/dadung/Visual-Localization-Filtering).

# Summary. An optional shortened abstract.
summary: 
    Propose 2 filtering approaches for visual localization<span>:</span> Monte Carlo Visual Localization, and Hidden Markov Model.
    <br>
    <span style="font-size:1.1em">_Neural Computing and Applications 2020_ (Special Issue on Best of DICTA 2019)</span>.

tags: 
- Localisation
- Bayes Filters

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1811.08063.pdf'
url_code: 'https://github.com/dzungdoan6/Visual-Localization-Filtering'
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
