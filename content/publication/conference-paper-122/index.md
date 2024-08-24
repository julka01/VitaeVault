---
title: "Deep convolutional recurrent neural network for rare acoustic event detection"
authors:
- admin
- Shahin Amiriparian
- Nicolas Cummins
- Björn Schuller
date: "2018-04-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-04-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-04-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Jahrestagung für Akustik 2018*
publication_short: In *DAGA 2018*

abstract: "Rare acoustic event detection, as evidenced by the recent IEEE AASP Challenge on Detection and Classification of Acoustic Scenes and Events (DCASE 2017), is a growing field of acoustic classification research. Rare audio events often possess unique spectral and temporal structures which can aid their identification. In this regard, we investigate the advantages of a hybrid combination of convolutional neural network and a recurrent neural network to classify rare occurring sound events in audio streams. Our developed system uses log-Mel spectrograms fed into convolutional layers to first extract high-level, shift-invariant spectral features. Recurrent layers are then used to learn the long-term temporal context from obtained high-level features. Finally, using a feed forward neural network with sigmoid activations, a sequence of probability estimations is used to predict the onset and presence of the rare sounds. We develop and test our system on the Detection of Rare Sound Events task of the DCASE 2017 challenge. Key results presented indicate that our proposed approach outperforms the challenge baseline, improving the overall detection error rate from 0.63 to 0.29 on the evaluation dataset."
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
