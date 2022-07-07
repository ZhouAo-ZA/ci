---
title: 'optimizing Memory Efficiency of Graph Neural Networks on Edge Computing Platforms'
authors:
  - Ao Zhou
  - Jianlei Yang
date: '2021-03-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-03-20 T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *RTAS 2021*
publication_short: In *RTAS 2021*

abstract: Graph neural networks (GNN) have achieved stateof-the-art performance on various industrial tasks. However, the poor efficiency of GNN inference and frequent Out-OfMemory (OOM) problem limit the successful application of GNN on edge computing platforms. To tackle these problems, a feature decomposition approach is proposed for memory efficiency optimization of GNN inference. The proposed approach could achieve outstanding optimization on various GNN models, covering a wide range of datasets, which speeds up the inference by up to 3×. Furthermore, the proposed feature decomposition could significantly reduce the peak memory usage (up to 5× in memory efficiency improvement) and mitigate OOM problems during GNN inference.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true


url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9470441
url_code: 'https://github.com/BUAA-CI-Lab/GNN-Feature-Decomposition'
url_dataset: '#'
url_poster: '#'
url_project: 'https://github.com/pyg-team/pytorch_geometric/blob/master/torch_geometric/nn/conv/message_passing.py'
url_slides: ''
url_source: '#'
url_video: 'https://www.youtube.com/watch?v=O7Am0-EwYkI&t=88s'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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
slides:
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

 [Contribution to PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/torch_geometric/nn/conv/message_passing.py).
