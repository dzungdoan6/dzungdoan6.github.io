---
title: 'A Hybrid Quantum-Classical Algorithm for Robust Fitting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Michele Sasdelli
  - David Suter
  - Tat-Jun Chin
  
# Author notes (optional)
author_notes:

date: '2022-06-24T00:00:00Z'
doi: 'https://doi.org/10.1109/CVPR52688.2022.00051'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2022)*
publication_short: In *CVPR*

abstract: Fitting geometric models onto outlier contaminated data is provably intractable. Many computer vision systems rely on random sampling heuristics to solve robust fitting, which do not provide optimality guarantees and error bounds. It is therefore critical to develop novel approaches that can bridge the gap between exact solutions that are costly, and fast heuristics that offer no quality assurances. In this paper, we propose a hybrid quantum-classical algorithm for robust fitting. Our core contribution is a novel robust fitting formulation that solves a sequence of integer programs and terminates with a global solution or an error bound. The combinatorial subproblems are amenable to a quantum annealer, which helps to tighten the bound efficiently. While our usage of quantum computing does not surmount the fundamental intractability of robust fitting, by providing error bounds our algorithm is a practical improvement over randomised heuristics. Moreover, our work represents a concrete application of quantum computing in computer vision. We present results obtained using an actual quantum computer (D-Wave Advantage) and via simulation.

# Summary. An optional shortened abstract.
summary: 
    A hybrid quantum-classical solution with an error bound for consensus maximisation
    <br>
    <span style="font-size:1.1em">In _CVPR 2022_</span>.

tags: 
- Robust fitting
- Quantum computing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2201.10110.pdf'
url_code: 'https://github.com/dzungdoan6/HQC-robust-fitting'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'uploads/quantum_classical_robust_fitting_slides.pdf'
url_source: ''
url_video: ''
links:
    - name: Presentation
      url: https://youtu.be/jLwYbL7jOk8?si=pWRcbnnzAPUaWLJ4

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
