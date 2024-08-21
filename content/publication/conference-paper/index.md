---
title: 'LLMs in the Loop: Leveraging Large Language Model Annotations for Active Learning in Low-Resource Languages'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nataliia Kholodna
  - admin 
  - Mohammad Khodadadi
  - Michael Granitzer

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-04-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *European Confereence on Machine Learning and Principles and Practice of Knowledge Discovery in Databases 2024*
publication_short: In *ECML PKDD 2024*

abstract: "Low-resource languages face significant barriers in AI devel-
opment due to limited linguistic resources and expertise for data labeling,
rendering them rare and costly. The scarcity of data and the absence of
preexisting tools exacerbate these challenges, especially since these lan-
guages may not be adequately represented in various NLP datasets. To
address this gap, we propose leveraging the potential of LLMs in the
active learning loop for data annotation. Initially, we conduct evalua-
tions to assess inter-annotator agreement and consistency, facilitating
the selection of a suitable LLM annotator. The chosen annotator is then
integrated into a training loop for a classifier using an active learning
paradigm, minimizing the amount of queried data required. Empirical
evaluations, notably employing GPT-4-Turbo, demonstrate near-state-
of-the-art performance with significantly reduced data requirements, as
indicated by estimated potential cost savings of at least 42.45 times com-
pared to human annotation. Our proposed solution shows promising po-
tential to substantially reduce both the monetary and computational
costs associated with automation in low-resource settings. By bridging
the gap between low-resource languages and AI, this approach fosters
broader inclusion and shows the potential to enable automation across
diverse linguistic landscapes."
## Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Large Language Models
  - Low-resource Language Modelling

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2404.02261'
url_code: 'https://github.com/mkandai/llms-in-the-loop'
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

