---
title: 'Distributed Online Optimization with Stochastic Agent Availability'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Juliette Achddou
  - Nicolò Cesa-bianchi
  - Hao Qiu
# Author notes (optional)
tags:
- online learning
- federated

date: "2024-09-01T00:00:00Z"
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: preprint


abstract: Motivated by practical federated learning settings where clients may not be always available, we investigate a variant of distributed online optimization where agents are active with a known probability $p$ at each time step, and communication between neighboring agents can only take place if they are both active. We introduce a distributed variant of the FTRL algorithm and analyze its network regret, defined through the average of the instantaneous regret of the active agents. Our analysis shows that, for any connected communication graph $G$ over $N$ agents, the expected network regret of our FTRL variant after $T$ steps is at most of order $(\kappa/p^2)\min\big\{\sqrt{N},N^{1/4}/\sqrt{p}\big\}\sqrt{T}$, where $\kappa$ is the condition number of the Laplacian of $G$. We then show that similar regret bounds also hold with high probability. Moreover, we show that our notion of regret (average-case over the agents) is essentially equivalent to the standard notion of regret (worst-case over agents), implying that our bounds are not significantly improvable when $p=1$. Our theoretical results are supported by experiments on synthetic datasets.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2411.16477'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'
# url_slides: 'slides_ACML.pdf'
# url_poster: 'ACML_poster.pdf'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

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
slides: ""
---
