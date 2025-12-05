---
title: "Zero-shot Generalization of GNNs Over Distinct Attribute Domains"
authors:
- Yangyi Shen
- admin
- Beatrice Bevilacqua
- Joshua Robinson
- Charilaos Kanatsoulis
- Jure Leskovec
- Bruno Ribeiro
date: "2025-05-10T00:00:00Z"
doi: ""

# Author notes (optional)

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]

# Publication name and optional abbreviated publication name.
publication: "ICML 2025"
publication_short: ""

abstract: Inductive GNNs are able to generalize across graphs with the same set of node attributes. However, zero-shot generalization across attributed graphs with disparate node attribute domains remains a fundamental challenge in graph machine learning. Existing methods are unable to effectively make use of node attributes when transferring to unseen attribute domains, frequently performing no better than models that ignore attributes entirely. This limitation stems from the fact that models trained on one set of attributes (e.g., biographical data in social networks) fail to capture relational dependencies that extend to new attributes in unseen test graphs (e.g., TV and movies preferences). Here, we introduce STAGE, a method that learns representations of _statistical dependencies_ between attributes rather than the attribute values themselves, which can then be applied to completely unseen test-time attributes, generalizing by identifying analogous dependencies between features in test. STAGE leverages the theoretical link between maximal invariants and measures of statistical dependencies, enabling it to provably generalize to unseen feature domains for a family of domain shifts. Our empirical results show that when STAGE is pretrained on multiple graph datasets with unrelated feature spaces (distinct feature types and dimensions) and evaluated zero-shot on graphs with yet new feature types and dimensions, it achieves a relative improvement in Hits@1 between 40% to 103% for link prediction, and an 10% improvement in node classification against state-of-the-art baselines.


tags:
- OOD Generalization
- Graph Foundation Models
- Graph Neural Networks
featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://openreview.net/pdf?id=5btqauRdz0
# url_code: https://github.com/DeepGraphLearning/ULTRA
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
