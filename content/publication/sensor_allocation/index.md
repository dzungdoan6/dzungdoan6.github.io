---
title: 'Sensor Allocation and Online-Learning-based Path Planning for Maritime Situational Awareness Enhancement: A Multi-Agent Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bach Long Nguyen
  - admin
  - Tat-Jun Chin
  - Christophe Guettier
  - Surabhi Gupta
  - Estelle Parra
  - Ian Reid
  - Markus Wagner
  
# Author notes (optional)
author_notes:

date: '2024-02-22T00:00:00Z'
doi: 'https://doi.org/10.1109/TITS.2024.3363716'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Intelligent Transportation Systems 2024*
publication_short: In *T-ITS*

abstract: Countries with access to large bodies of water often aim to protect their maritime transport by employing maritime surveillance systems. However, the number of available sensors (e.g., cameras) is typically small compared to the to-be-monitored targets, and their Field of View (FOV) and range are often limited. This makes improving the situational awareness of maritime transports challenging. To this end, we propose a method that not only distributes multiple sensors but also plans paths for them to observe multiple targets, while minimizing the time needed to achieve situational awareness. In particular, we provide a formulation of this sensor allocation and path planning problem which considers the partial awareness of the targets’ state, as well as the unawareness of the targets’ trajectories. To solve the problem we present two algorithms<span>:</span> 1) a greedy algorithm for assigning sensors to targets, and 2) a distributed multi-agent path planning algorithm based on regret-matching learning. Because a quick convergence is a requirement for algorithms developed for high mobility environments, we employ a forgetting factor to quickly converge to correlated equilibrium solutions. Experimental results show that our combined approach achieves situational awareness more quickly than related work.

# Summary. An optional shortened abstract.
summary: 
    We develop a planning algorithm that employs multiple sensors to observe multiple targets, minimising the time needed for maritime situational awareness.
    <br>
    <span style="font-size:1.1em">_IEEE Transactions on Intelligent Transportation Systems 2024_</span>. 

tags: 
- Path Planning
- Optimisation

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2307.02790.pdf'
url_code: 'https://github.com/Long-UoA/Sensor-Allocation-and-Online-Learning-based-Path-Planning-Approach'
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
