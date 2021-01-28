---
abstract: We propose a practical algorithm for low rank matrix completion for
  matrices with binary entries which obtains explicit binary factors and show it
  performs well at the recommender task on real world datasets. The algorithm,
  which we call TBMC (Tiling for Binary Matrix Completion), gives interpretable
  output in the form of binary factors which represent a decomposition of the
  matrix into tiles. Our approach extends a popular algorithm from the data
  mining community, PROXIMUS, to missing data, applying the same recursive
  partitioning approach. The algorithm relies upon rank-one approximations of
  incomplete binary matrices, and we propose a linear programming (LP) approach
  for solving this subproblem. We also prove a 2-approximation result for the LP
  approach which holds for any subsampling pattern, and show that TBMC exactly
  solves the rank-k prediction task for a underlying block-diagonal tiling
  structure with geometrically decreasing tile sizes, providing the ratio
  between successive tiles is less than . Numerical experiments show that TBMC
  outperforms existing methods on real datasets.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Mel Beckerleg Andrew Thompson
author_notes:
  - Equal contribution
  - Equal contribution
publication: " Linear Algebra and its Applications"
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
  tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
  condimentum.
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: A Divide and Conquer Algorithm for Binary Matrix Completion
doi: ""
featured: true
tags: []
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
