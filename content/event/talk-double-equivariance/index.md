---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Double Equivariance for Inductive Link Prediction for Both New Nodes and New Relation Types"
event: NeurIPS 2023 New Frontiers in Graph Learning (GLFrontiers)
event_url: https://neurips.cc/virtual/2023/workshop/66500
location: New Orleans, LA, USA
address:
  street:
  city:
  region:
  postcode:
  country:
summary: NeurIPS 2023 GLFrontiers Oral Presentation
abstract: "The task of inductive link prediction in discrete attributed multigraphs (e.g., knowledge graphs, multilayer networks, heterogeneous networks, etc.) generally focuses on test predictions with solely new nodes but not both new nodes and new relation types. In this work, we formally define the task of predicting (completely) new nodes and new relation types in test as a doubly inductive link prediction task and introduce a theoretical framework for the solution. We start by defining the concept of double permutation-equivariant representations that are equivariant to permutations of both node identities and edge relation types. We then propose a general blueprint to design neural architectures that impose a structural representation of relations that can inductively generalize from training nodes and relations to arbitrarily new test nodes and relations without the need for adaptation, side information, or retraining. We also introduce the concept of distributionally double equivariant positional embeddings designed to perform the same task. Finally, we empirically demonstrate the capability of the two proposed models on a set of novel real-world benchmarks, showcasing relative performance gains of up to 41.40% on predicting new relations types compared to baselines."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-12-15T10:45:00-08:00
date_end: 2023-12-15T10:50:00-08:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2023-12-15T10:50:00-08:00

authors: 
  - admin
tags: [Knowledge Graphs, Inductive Link Prediction, Graph Neural Networks, Double Equivariance]

# Is this a featured event? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: true   # Already have a Youtube embed with the same preview picture.

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides: https://drive.google.com/file/d/1vjvIE7m5HW6EIVSPUnwqTujA7jp0y03D/view?usp=sharing

# url_code:
# url_pdf:
url_video: https://nips.cc/virtual/2023/workshop/66500

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["double-equivariance"]
---

{{< youtube evXLHTFTgxQ>}}
