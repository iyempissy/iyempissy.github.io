---
title: "Membership inference attack on graph neural networks"
authors:
- Iyiola E. Olatunji
- Wolfgang Nejdl
- Megha Khosla
author_notes:
date: "2021-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"] #conference
# publication_types: ["article-journal"] #journal

# Publication name and optional abbreviated publication name.
publication: "*2021 Third IEEE International Conference on Trust, Privacy and Security in Intelligent Systems and Applications (TPS-ISA)*"
publication_short: ""

abstract: Graph Neural Networks (GNNs), which generalize traditional deep neural networks on graph data, have achieved state-of-the-art performance on several graph analytical tasks. We focus on how trained GNN models could leak information about the member nodes that they were trained on. We introduce two realistic settings for performing a membership inference (MI) attack on GNNs. While choosing the simplest possible attack model that utilizes the posteriors of the trained model (black-box access), we thoroughly analyze the properties of GNNs and the datasets which dictate the differences in their robustness towards MI attack. While in traditional machine learning models, overfitting is considered the main cause of such leakage, we show that in GNNs the additional structural information is the major contributing factor. We support our findings by extensive experiments on four representative GNN models. To prevent MI attacks on GNN, we propose two effective defenses that significantly decreases the attacker's inference by up to 60% without degradation to the target model's performance. Our code is available at https://github.com/iyempissy/rebMIGraph.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2101.06570.pdf'
url_code: 'https://github.com/iyempissy/rebMIGraph'
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
