---
title: 'Compact Hash Code Learning With Binary Deep Neural Network'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Thanh-Toan Do
  - Tuan Hoang
  - Dang-Khoa Le Tan
  - admin
  - Ngai-Man Cheung
  
# Author notes (optional)
author_notes:

date: '2019-08-15T00:00:00Z'
doi: 'https://doi.org/10.1109/TMM.2019.2935680'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-08-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Multimedia 2019*
publication_short: In *TMM*

abstract: Learning compact binary codes for image retrieval problem using deep neural networks has recently attracted increasing attention. However, training deep hashing networks is challenging due to the binary constraints on the hash codes. In this paper, we propose deep network models and learning algorithms for learning binary hash codes given image representations under both unsupervised and supervised manners. The novelty of our network design is that we constrain one hidden layer to directly output the binary codes. This design has overcome a challenging problem in some previous works<span>:</span> optimizing non-smooth objective functions because of binarization. In addition, we propose to incorporate independence and balance properties in the direct and strict forms into the learning schemes. We also include a similarity preserving property in our objective functions. The resulting optimizations involving these binary, independence, and balance constraints are difficult to solve. To tackle this difficulty, we propose to learn the networks with alternating optimization and careful relaxation. Furthermore, by leveraging the powerful capacity of convolutional neural networks, we propose an end-to-end architecture that jointly learns to extract visual features and produce binary hash codes. Experimental results for the benchmark datasets show that the proposed methods compare favorably or outperform the state of the art.

# Summary. An optional shortened abstract.
summary: 
    Extension of ECCV16 paper<span>:</span> end-to-end training binary deep neural network and CNN.
    <br>
    <span style="font-size:1.1em">_IEEE Transactions on Multimedia 2019_</span>.

tags: 
- Image Retrieval
- Hashing
- Deep Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1712.02956.pdf'
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
