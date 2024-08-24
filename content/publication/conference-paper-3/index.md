---
title: 'Knowledge distillation with Segment Anything (SAM)
model for Planetary Geological Mapping'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Michael Granitzer

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-09-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning, Data Science and Optimization 2023*
publication_short: In *LOD 2023*

abstract: "Planetary science research involves analysing vast amounts of
remote sensing data, which are often costly and time-consuming to an-
notate and process. One of the essential tasks in this field is geological
mapping, which requires identifying and outlining regions of interest in
planetary images, including geological features and landforms. However,
manually labelling these images is a complex and challenging task that
requires significant domain expertise and effort. To expedite this en-
deavour, we propose the use of knowledge distillation using the recently
introduced cutting-edge Segment Anything (SAM) model. We demon-
strate the effectiveness of this prompt-based foundation model for rapid
annotation and quick adaptability to a prime use case of mapping plan-
etary skylights. Our work reveals that with a small set of annotations
obtained with the right prompts from the model and subsequently train-
ing a specialised domain decoder, we can achieve satisfactory semantic
segmentation on this task. Key results indicate that the use of knowledge
distillation can significantly reduce the effort required by domain experts
for manual annotation and improve the efficiency of image segmentation
tasks. This approach has the potential to accelerate extra-terrestrial dis-
covery by automatically detecting and segmenting Martian landforms."
## Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Semantic Segmentation
  - Knowledge distillation
  - Segment Anything Model

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2305.07586'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/_index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/_index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

