---
title: 'Binary Hashing with Semidefinite Relaxation and Augmented Lagrangian'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Thanh-Toan Do
  - admin
  - Duc-Thanh Nguyen
  - Ngai-Man Cheung

# Author notes (optional)
author_notes:

date: '2016-09-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2016-09-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision*
publication_short: In *ECCV*

abstract: This paper proposes two approaches for inferencing binary codes in two-step (supervised, unsupervised) hashing. We first introduce an unified formulation for both supervised and unsupervised hashing. Then, we cast the learning of one bit as a Binary Quadratic Problem (BQP). We propose two approaches to solve BQP. In the first approach, we relax BQP as a semidefinite programming problem which its global optimum can be achieved. We theoretically prove that the objective value of the binary solution achieved by this approach is well bounded. In the second approach, we propose an augmented Lagrangian based approach to solve BQP directly without relaxing the binary constraint. Experimental results on three benchmark datasets show that our proposed methods compare favorably with the state of the art.

# Summary. An optional shortened abstract.
summary: 
    Unify two-step supervised and unsupervised image hashing into the Binary Quadratic Problem, then propose 2 solvers Semidefinite relaxation and Augmented Lagrangian
    <br> 
    _ECCV 2016_. **(Spotlight)**

tags: 
- Image hashing
- Optimisation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1607.05396.pdf'
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
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
