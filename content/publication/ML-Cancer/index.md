---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Machine learning models to predict the progression from early to late stages of papillary renal cell carcinoma"
authors: [Noor Pratap Singh, Raju S Bapi, P K Vinod]
date: 2018-09-01
doi: "0.1016/j.compbiomed.2018.06.030"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-25T11:48:59-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computers in Biology and Medicine"
publication_short: "Comput Biol Med"

abstract: "Papillary Renal Cell Carcinoma (PRCC) is a heterogeneous disease with variations in disease progression and clinical outcomes. The advent of next generation sequencing techniques (NGS) has generated data from patients that can be analysed to develop a predictive model. In this study, we have adopted a machine learning approach to identify biomarkers and build classifiers to discriminate between early and late stages of PRCC from gene expression profiles. A machine learning pipeline incorporating different feature selection algorithms and classification models is developed to analyse RNA sequencing dataset (RNASeq). Further, to get a reliable feature set, we extracted features from different partitions of the training dataset and aggregated them into feature sets for classification. We evaluated the performance of different algorithms on the basis of 10-fold cross validation and independent test dataset. 10-fold cross validation was also performed on a microarray dataset of PRCC. A random forest based feature selection (varSelRF) yielded minimum number of features (104) and a best performance with area under Precision Recall curve (PR-AUC) of 0.804, MCC (Matthews Correlation Coefficient) of 0.711 and accuracy of 88% with Shrunken Centroid classifier on a test dataset. We identified 80 genes that are consistently altered between stages by different feature selection algorithms. The extracted features are related to cellular components - centromere, kinetochore and spindle, and biological process mitotic cell cycle. These observations reveal potential mechanisms for an increase in chromosome instability in the late stage of PRCC. Our study demonstrates that the gene expression profiles can be used to classify stages of PRCC."

# Summary. An optional shortened abstract.
summary: ""

tags: [Cell cycle; Chromosome instability; Feature selection; Machine learning; Papillary renal cell carcinoma; Tumour stage prediction.]
categories: [Cell cycle; Chromosome instability; Feature selection; Machine learning; Papillary renal cell carcinoma; Tumour stage prediction.]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0010482518301781
url_code: https://github.com/NPSDC/BISP
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
