---
title: "Double Equivariance for Inductive Link Prediction for Both New Nodes and New Relation Types"
authors:
- Jianfei Gao
- Yangze Zhou
- admin
- Bruno Ribeiro
date: "2023-10-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-03T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to ICLR 2024 (under review)"
publication_short: ""

abstract: The task of inductive link prediction in discrete attributed multigraphs (e.g., knowledge graphs, multilayer networks, heterogeneous networks, etc.) generally focuses on test predictions with solely new nodes but not both new nodes and new relation types. In this work, we formally define the task of predicting (completely) new nodes and new relation types in test as a doubly inductive link prediction task and introduce a theoretical framework for the solution. We start by defining the concept of double permutation-equivariant representations that are equivariant to permutations of both node identities and edge relation types. We then propose a general blueprint to design neural architectures that impose a structural representation of relations that can inductively generalize from training nodes and relations to arbitrarily new test nodes and relations without the need for adaptation, side information, or retraining. We also introduce the concept of distributionally double equivariant positional embeddings designed to perform the same task. Finally, we empirically demonstrate the capability of the two proposed models on a set of novel real-world benchmarks, showcasing average relative performance gains of 39.65% on predicting new relations types compared to baselines.


tags:
- Knowledge Graphs
- Inductive Link Prediction
- Graph Neural Networks
- Permutation Equivariance
- Double Equivariance
featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2302.01313
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
