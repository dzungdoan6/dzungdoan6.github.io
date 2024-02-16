---
title: 'Learning to Predict Repeatability of Interest Points'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Daniyar Turmukhambetov
  - Yasir Latif
  - Tat-Jun Chin
  - Soohyun Bae
  
# Author notes (optional)
author_notes:

date: '2021-01-01T00:00:00Z'
doi: 'https://doi.org/10.1109/ICRA48506.2021.9561383'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation (ICRA 2021)*
publication_short: In *ICRA*

abstract: Many robotics applications require interest points that are highly repeatable under varying viewpoints and lighting conditions. However, this requirement is very challenging as the environment changes continuously and indefinitely, leading to appearance changes of interest points with respect to time. This paper proposes to predict the repeatability of an interest point as a function of time, which can tell us the lifespan of the interest point considering daily or seasonal variation. The repeatability predictor (RP) is formulated as a regressor trained on repeated interest points from multiple viewpoints over a long period of time. Through comprehensive experiments, we demonstrate that our RP can estimate when a new interest point is repeated, and also highlight an insightful analysis about this problem. For further comparison, we apply our RP to the map summarization under visual localization framework, which builds a compact representation of the full context map given the query time. The experimental result shows a careful selection of potentially repeatable interest points predicted by our RP can significantly mitigate the degeneration of localization accuracy from map summarization.

# Summary. An optional shortened abstract.
summary: 
    Repeatability of an interest point is not constant but a function of time
    <br>
    <span style="font-size:1.1em">In _ICRA 2021_</span>

tags: 
- Localisation
- Deep learning

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2105.03578.pdf'
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
