---
title: "Conditional Generative Adversarial Networks for Speed Control in Trajectory
Simulation"
authors:
- admin
- Vishal Sowrirajan
- Jörg Schlötterer
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-03-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-21T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning, Data Science and Optimization 2021*
publication_short: In *LOD 2021*

abstract: "Motion behaviour is driven by several factors - goals,
presence and actions of neighbouring agents, social rela-
tions, physical and social norms, the environment with its
variable characteristics, and further. Most factors are not
directly observable and must be modelled from context. Tra-
jectory prediction, is thus a hard problem, and has seen in-
creasing attention from researchers in the recent years. Pre-
diction of motion, in application, must be realistic, diverse
and controllable. In spite of increasing focus on multimodal
trajectory generation, most methods still lack means for ex-
plicitly controlling different modes of the data generation.
Further, most endeavours invest heavily in designing spe-
cial mechanisms to learn the interactions in latent space.
We present Conditional Speed GAN (CSG), that allows con-
trolled generation of diverse and socially acceptable trajec-
tories, based on user controlled speed. During prediction,
CSG forecasts future speed from latent space and conditions
its generation based on it. CSG is comparable to state-of-
the-art GAN methods in terms of the benchmark distance
metrics, while being simple and useful for simulation and
data augmentation for different contexts such as fast or slow
paced environments. Additionally, we compare the effect of
different aggregation mechanisms and show that a naive ap-
proach of concatenation works comparable to its attention
and pooling alternatives."
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2103.11471
url_code: 'https://github.com/julka01/CSG'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/_index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/_index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
