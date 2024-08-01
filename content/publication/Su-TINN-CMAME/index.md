---
title: "A thermodynamics-informed neural network for elastoplastic constitutive modeling of granular materials"
authors:
- mingming su
- admin
author_notes:
- "First author"
- "Corresponding author"
date: "2024-07-25T00:00:00Z"
doi: "10.1016/j.cma.2024.117246"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Methods in Applied Mechanics and Engineering*"
publication_short: "CMAME"

abstract: Data-driven methods have emerged as a promising framework for material constitutive modeling. However, traditional data-driven models are hindered by limitations arising from as a scarcity of datasets and the absence of explicit physical principles. These limitations lead to inadequate generalization capabilities and predictions that may contradict established physical laws. To overcome these challenges, this study introduces a thermodynamics-informed neural network (TINN) for elastoplastic constitutive modeling of granular materials. Following the thermodynamics-based elastoplastic theory, the TINN model incorporates elastic free energy, stored plastic work, and dissipation. It achieves this by integrating a path dependent recurrent neural network (RNN) and three sub-fully connected neural networks to capture the mechanical response and energy evolution in sheared granular materials. The total loss function of TINN combines data-driven and physics-informed components. The effectiveness and generalization capabilities of TINN are evaluated by testing it on diverse datasets, including both simulated and experimental data. The simulated virtual data are derived either from an available elastoplastic model or via discrete element method (DEM) simulations employing stress probing techniques. The results highlight the superior generalization ability and robustness of the TINN model, surpassing purely data-driven models in performance and reliability. 

# Summary. An optional shortened abstract.
summary: .

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.researchgate.net/publication/382334862_A_thermodynamics-informed_neural_network_for_elastoplastic_constitutive_modeling_of_granular_materials
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
