---
title: "DriftGAN: Using historical data for Unsupervised Recurring Drift Detection"
authors:
- Christofer Fellicious
- admin
- Lorenz Wendlinger
- Michael Granitzer


author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-04-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *The 39th ACM/SIGAPP Symposium On Applied Computing,2024*
publication_short: In *ACM SAC 2024*

abstract: "In real-world applications, input data distributions are rarely
static over a period of time, a phenomenon known as concept drift. Such
concept drifts degrade the model’s prediction performance, and there-
fore we require methods to overcome these issues. The initial step is to
identify concept drifts and have a training method in place to recover
the model’s performance. Most concept drift detection methods work on
detecting concept drifts and signalling the requirement to retrain the
model. However, in real-world cases, there could be concept drifts that
recur over a period of time. In this paper, we present an unsupervised
method based on Generative Adversarial Networks(GAN) to detect con-
cept drifts and identify whether a specific concept drift occurred in the
past. Our method reduces the time and data the model requires to get
up to speed for recurring drifts. Our key results indicate that our pro-
posed model can outperform the current state-of-the-art models in most
datasets. We also test our method on a real-world use case from astro-
physics, where we detect the bow shock and magnetopause crossings with
better results than the existing methods in the domain."
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://opus.bibliothek.uni-augsburg.de/opus4/frontdoor/deliver/index/docId/44180/file/1772.pdf
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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
slides: example
---
