---
title: "Achieving differential privacy for k-nearest neighbors based outlier detection by data partitioning"
authors:
- Jens Rauch
- Iyiola E. Olatunji
- Megha Khosla
author_notes:
date: "2021-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ["paper-conference"] #conference
# publication_types: ["article-journal"] #journal
publication_types: ["article"] # preprint


# Publication name and optional abbreviated publication name.
publication: "*ArXiv*"
publication_short: ""

abstract: When applying outlier detection in settings where data is sensitive, mechanisms which guarantee the privacy of the underlying data are needed. The k-nearest neighbors (k-NN) algorithm is a simple and one of the most effective methods for outlier detection. So far, there have been no attempts made to develop a differentially private (E-DP) approach for k-NN based outlier detection. Existing approaches often relax the notion of E-DP and employ other methods than k-NN. We propose a method for k-NN based outlier detection by separating the procedure into a fitting step on reference inlier data and then apply the outlier classifier to new data. We achieve E-DP for both the fitting algorithm and the outlier classifier with respect to the reference data by partitioning the dataset into a uniform grid, which yields low global sensitivity. Our approach yields nearly optimal performance on real-world data with varying dimensions when compared to the non-private versions of k-NN.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Defense

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2104.07938.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: "" #example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
