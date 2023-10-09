---
title: "An OOD Multi-Task Perspective for Link Prediction with New Relation Types and Nodes"
authors:
- admin
- Beatrice Bevilacqua
- Bruno Ribeiro
date: "2023-07-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to NeurIPS 2023 GLFrontiers workshop (under review)"
publication_short: ""

abstract: The task of inductive link prediction in (discrete) attributed multigraphs infers missing attributed links (relations) between nodes in new test multigraphs. Traditional relational learning methods face the challenge of limited generalization to OOD test multigraphs containing both novel nodes and novel relation types not seen in training. Recently, under the only assumption that all relation types share the same structural predictive patterns (single task), Gao et al. (2023) proposed an OOD link prediction method using the theoretical concept of double exchangeability (for nodes & relation types), in contrast to the (single) exchangeability (only for nodes) used to design Graph Neural Networks (GNNs). In this work we further extend the double exchangeability concept to multi-task double exchangeability, where we define link prediction in attributed multigraphs that can have distinct and potentially conflicting predictive patterns for different sets of relation types (multiple tasks). Our empirical results on real-world datasets demonstrate that our approach can effectively generalize to entirely new relation types in test, without access to additional information, yielding significant performance improvements over existing methods.


tags:
- Knowledge Graphs
- Inductive Link Prediction
- Out-of-Distribution
- Multi-Task Learning
- Graph Neural Networks
- Double Equivariance
featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2307.06046
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
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
- internal-project

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
