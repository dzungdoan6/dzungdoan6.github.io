---
title: 'Slack-Free Spiking Neural Network Formulation for Hypergraph Minimum Vertex Cover'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tam Ngoc-Bang Nguyen
  - admin
  - Zhipeng Cai
  - Tat-Jun Chin
  
# Author notes (optional)
author_notes:

date: '2024-01-01T00:00:00Z'
# doi: 'https://doi.org/10.1016/j.cviu.2023.103885'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems*
publication_short: In *NeurIPS*

abstract: Neuromorphic computers open up the potential of energy-efficient computation using spiking neural networks (SNN), which consist of neurons that exchange spike-based information asynchronously. In particular, SNNs have shown promise in solving combinatorial optimization. Underpinning the SNN methods is the concept of energy minimization of an Ising model, which is closely related to quadratic unconstrained binary optimization (QUBO). Thus, the starting point for many SNN methods is reformulating the target problem as QUBO, then executing an SNN-based QUBO solver. For many combinatorial problems, the reformulation entails introducing penalty terms, potentially with slack variables, that implement feasibility constraints in the QUBO objective. For more complex problems such as hypergraph minimum vertex cover (HMVC), numerous slack variables are introduced which drastically increase the search domain and reduce the effectiveness of the SNN solver. In this paper, we propose a novel SNN formulation for HMVC. Rather than using penalty terms with slack variables, our SNN architecture introduces additional spiking neurons with a constraint checking and correction mechanism that encourages convergence to feasible solutions. In effect, our method obviates the need for reformulating HMVC as QUBO. Experiments on neuromorphic hardware show that our method consistently yielded high quality solutions for HMVC on real and synthetic instances where the SNN-based QUBO solver often failed, while consuming measurably less energy than global solvers on CPU.

# Summary. An optional shortened abstract.
summary: 
    We propose a novel SNN formulation for hypergraph minimum vertex cover, which achieves high-quality solutions with reduced energy consumption efficiently.
    <br>
    <span style="font-size:1.1em">In _NeurIPS 2024_</span>. 

tags: 
- Spiking Neural Network
- Optimization
- Neuromorphic Computing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=4A5IQEjG8c'
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
