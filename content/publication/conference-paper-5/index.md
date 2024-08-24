---
title: "Recognition of Echolalic Autistic Child Vocalisations Utilising
Convolutional Recurrent Neural Networks"
authors:
- admin
- Shahin Amiriparian
- Alice Baird
- Alyssa Alcorn
- Björn Schuller

author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2018-09-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-21T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Interspeech 2018*
publication_short: In *Interspeech 2018*

abstract: "Autism spectrum conditions (ASC) are a set of neuro-
developmental conditions partly characterised by difficulties
with communication. Individuals with ASC can show a variety
of atypical speech behaviours, including echolalia or the ‘echo-
ing’ of another’s speech. We herein introduce a new dataset of
15 Serbian ASC children in a human-robot interaction scenario,
annotated for the presence of echolalia amongst other ASC vocal
behaviours. From this, we propose a four-class classification
problem and investigate the suitability of applying a 2D convolu-
tional neural network augmented with a recurrent neural network
with bidirectional long short-term memory cells to solve the
proposed task of echolalia recognition. In this approach, log
Mel-spectrograms are first generated from the audio recordings
and then fed as input into the convolutional layers to extract
high-level spectral features. The subsequent recurrent layers
are applied to learn the long-term temporal context from the
obtained features. Finally, we use a feed forward neural network
with softmax activation to classify the dataset. To evaluate the
performance of our deep learning approach, we use leave-one-
subject-out cross-validation. Key results presented indicate the
suitability of our approach by achieving a classification accuracy
of 83.5 % unweighted average recall."
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
