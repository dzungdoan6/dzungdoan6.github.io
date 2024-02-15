---
title: 'Scalable Place Recognition Under Appearance Change for Autonomous Driving'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yasir Latif
  - Tat-Jun Chin
  - Yu Liu
  - Thanh-Toan Do
  - Ian Reid
  
# Author notes (optional)
author_notes:

date: '2019-11-02T00:00:00Z'
doi: 'https://doi.org/10.1109/ICCV.2019.00941'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-11-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF International Conference on Computer Vision (ICCV 2019)*
publication_short: In *ICCV*

abstract: A major challenge in place recognition for autonomous driving is to be robust against appearance changes due to short-term (e.g., weather, lighting) and long-term (seasons, vegetation growth, etc.) environmental variations. A promising solution is to continuously accumulate images to maintain an adequate sample of the conditions and incorporate new changes into the place recognition decision. However, this demands a place recognition technique that is scalable on an ever growing dataset. To this end, we propose a novel place recognition technique that can be efficiently retrained and compressed, such that the recognition of new queries can exploit all available data (including recent changes) without suffering from visible growth in computational cost. Underpinning our method is a novel temporal image matching technique based on Hidden Markov Models. Our experiments show that, compared to state-of-the-art techniques, our method has much greater potential for large-scale place recognition for autonomous driving.

# Summary. An optional shortened abstract.
summary: 
    Highlight the need for continuous data collection in achieving a robust place recognition system. This drives our proposal for a scalable solution based on the Hidden Markov Model.

tags: 
- Localisation
- Hidden Markov Model

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content_ICCV_2019/papers/Doan_Scalable_Place_Recognition_Under_Appearance_Change_for_Autonomous_Driving_ICCV_2019_paper.pdf'
url_code: 'https://github.com/dzungdoan6/SPR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'uploads/spr_iccv2019.pdf'
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
