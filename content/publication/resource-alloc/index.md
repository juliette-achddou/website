---
title: 'Regret Analysis of the Stochastic Direct Search Method for Blind Resource Allocation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Juliette Achddou
  - Olivier Cappé
  - Aurélien Garivier
# Author notes (optional)


date: "2024-01-01T00:00:00Z"
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: To appear in  *TMLR 2024*


abstract: Motivated by programmatic advertising optimization, we consider the task of sequentially allocating budget across a set of resources. At every time step, a feasible allocation is chosen and only a corresponding random return is observed. The goal is to maximize the cumulative expected sum of returns. This is a realistic model for budget allocation across subdivisions of marketing campaigns, when the objective is to maximize the number of conversions. We study direct search (aka pattern search) methods for linearly constrained and derivative-free optimization in the presence of noise. Those algorithms are easy to implement and particularly suited to constrained optimization. They have not yet been analyzed from the perspective of cumulative regret. We provide a regret upper-bound of the order of T 2/3 in the general case. Our mathematical analysis also establishes, as a by-product, time-independent regret bounds in the deterministic, unconstrained case. We also propose an improved version of the method relying on sequential tests to accelerate the identification of descent directions. 
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- bandits
- black-box optimization

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2210.05222.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false
projects: []

slides: ""
---


