---
title: "Deep Active Learning for Detection of Mercury's Bow Shock and Magnetopause Crossings"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Nikolas Kirschstein
  - Michael Granitzer
  - Alexander Lavrukhin
  - Ute Amerstorfer

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-08-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *European Confereence on Machine Learning and Principles and Practice of Knowledge Discovery in Databases 2022*
publication_short: In *ECML PKDD 2022*

abstract: "Accurate and timely detection of bow shock and magne-
topause crossings is essential for understanding the dynamics of a planet’s
magnetosphere. However, for Mercury, due to the variable nature of
its magnetosphere, this remains a challenging task. Existing approaches
based on geometric equations only provide average boundary shapes, and
can be hard to generalise to environments with variable conditions. On
the other hand, data-driven methods require large amounts of annotated
data to account for variations, which can scale up the costs quickly. We
propose to solve this problem with machine learning. To this end, we
introduce a suitable dataset, prepared by processing raw measurements
from NASA’s MESSENGER 4 mission and design a five-class supervised
learning problem. We perform an architectural search to find a suitable
model, and report our best model, a Convolutional Recurrent Neural
Network (CRNN), achieves a macro F1 score of 0.82 with accuracies
of approximately 80 % and 88 % on the bow shock and magnetopause
crossings, respectively. Further, we introduce an approach based on ac-
tive learning that includes only the most informative orbits from the
MESSENGER dataset measured by Shannon entropy. We observe that
by employing this technique, the model is able to obtain near maximal
information gain by training on just two Mercury years worth of data,
which is about 10 % of the entire dataset. This has the potential to sig-
nificantly reduce the need for manual labeling. This work sets the ground
for future machine learning endeavors in this direction and may be highly
relevant to future missions such as BepiColombo, which is expected to
enter orbit around Mercury in December 2025."
## Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Active Learning
  - Magnetosphere
  - Artificial Neural Networks

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

