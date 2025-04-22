---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "TreeTerminus - Creating transcript trees using inferential replicate counts"
authors: ["Noor Pratap Singh", "Michael I Love", "Rob Patro" ]
date: 2023-06-16
doi: "https://doi.org/10.1016/j.isci.2023.106961"

# Schedule page publish date (NOT publication's date).
# publishDate: 2021-08-25T11:48:59-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "iScience"
# publication_short: "Comput Biol Med"

abstract: "The accuracy and robustness of many types of analyses performed using RNA-seq data are directly impacted by the quality of the transcript and gene abundance estimates inferred from this data. However, a certain degree of uncertainty is always associated with the transcript abundance estimates. This uncertainty may make many downstream analyses, such as differential testing, difficult for certain transcripts. Conversely, gene-level analysis, though less ambiguous, is often too coarse-grained. To circumvent this problem, methods have proposed grouping transcripts together into distinct inferential units that should be used as a base unit for analysis. However, these methods don9t take downstream analysis into account. We introduce TreeTerminus, a data-driven approach for grouping transcripts into a tree structure where leaves represent individual transcripts and internal nodes represent an aggregation of a transcript set. TreeTerminus constructs trees such that, on average, the inferential uncertainty decreases as we ascend the tree topology. The tree provides the flexibility to analyze data at nodes that are at different levels of resolution in the tree and can be tuned depending on the analysis of interest. To obtain fixed groups for the downstream analysis, we provide a dynamic programming (DP) approach that can be used to find a cut through the tree that optimizes one of several different objectives. We evaluated TreeTerminus on two simulated and two experimental datasets, and observed an improved performance compared to transcripts (leaves) and other methods under several different metrics.."

# Summary. An optional shortened abstract.
summary: ""

tags: [Inferential Uncertainty, Dynamic Programming, RNA-Seq, Transcript-tree.]
categories: [Inferential Uncertainty, Dynamic Programming, RNA-Seq, Transcript-tree.]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.cell.com/iscience/fulltext/S2589-0042(23)01038-6
url_code: https://github.com/COMBINE-lab/TreeTerminus
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
