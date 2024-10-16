---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Tree-based differential testing using inferential uncertainty for RNA-Seq"
authors: [Noor Pratap Singh, Michael I Love, Rob Patro]
date: 2023-12-25
doi: "https://doi.org/10.1101/2023.12.25.573288"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-25T11:48:59-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: "bioRxiv"

abstract: "Identifying differentially expressed transcripts poses a crucial yet challenging problem in transcriptomics. Substantial uncertainty is associated with the abundance estimates of certain transcripts which, if ignored, can lead to the exaggeration of false positives and, if included, may lead to reduced power. For a given set of RNA-Seq samples, TreeTerminus arranges transcripts in a hierarchical tree structure that encodes different layers of resolution for interpretation of the abundance of transcriptional groups, with uncertainty generally decreasing as one ascends the tree from the leaves. We introduce trenDi, which utilizes the tree structure from TreeTerminus for differential testing. The candidate nodes are determined in a data-driven manner to maximize the signal that can be extracted from the data while controlling for the uncertainty associated with estimating the transcript abundances. The identified candidate nodes can include transcripts and inner nodes, with no two nodes having an ancestor/descendant relationship. We evaluated our method on both simulated and experimental datasets, comparing its performance with other tree-based differential methods as well as with uncertainty-aware differential transcript/gene expression methods. Our method detects inner nodes that show a strong signal for differential expression, which would have been overlooked when analyzing the transcripts alone."

# Summary. An optional shortened abstract.
summary: ""

tags: [RNA-Seq; Inferential uncertainty; differential testing; Tree based differential testing.]
categories: [.]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.biorxiv.org/content/10.1101/2024.07.30.605821v1.abstract
url_code: https://github.com/NPSDC/mehenDi
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
