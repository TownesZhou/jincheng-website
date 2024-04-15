---
title: "Zero-shot Logical Query Reasoning on any Knowledge Graph"
authors:
- Mikhail Galkin
- admin
- Bruno Ribeiro
- Jian Tang
- Zhaocheng Zhu
date: "2024-04-10T00:00:00Z"
doi: ""

# Author notes (optional)

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: ""

abstract: Complex logical query answering (CLQA) in knowledge graphs (KGs) goes beyond simple KG completion and aims at answering compositional queries comprised of multiple projections and logical operations. Existing CLQA methods that learn parameters bound to certain entity or relation vocabularies can only be applied to the graph they are trained on which requires substantial training time before being deployed on a new graph. Here we present UltraQuery, an inductive reasoning model that can zero-shot answer logical queries on any KG. The core idea of UltraQuery is to derive both projections and logical operations as vocabulary-independent functions which generalize to new entities and relations in any KG. With the projection operation initialized from a pre-trained inductive KG reasoning model, UltraQuery can solve CLQA on any KG even if it is only finetuned on a single dataset. Experimenting on 23 datasets, UltraQuery in the zero-shot inference mode shows competitive or better query answering performance than best available baselines and sets a new state of the art on 14 of them. 


tags:
- Knowledge Graphs
- Logical Query Ansering
- Graph Neural Networks
- Double Equivariance
featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2404.07198
url_code: https://github.com/DeepGraphLearning/ULTRA
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: https://neurips.cc/virtual/2023/82330
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- logical-query-answering

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
