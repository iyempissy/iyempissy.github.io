---
title: "Private graph extraction via feature explanations"
authors:
- Iyiola E. Olatunji
- Mandeep Rathee
- Thorben Funke
- Megha Khosla
author_notes:
date: "2023-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"] #conference
# publication_types: ["article-journal"] #journal
# publication_types: ["article"] # preprint


# Publication name and optional abbreviated publication name.
publication: "*Proceedings on Privacy Enhancing Technologies (PETS)*"
publication_short: ""

abstract: 'Privacy and interpretability are two important ingredients for achieving trustworthy machine learning. We study the interplay of these
two aspects in graph machine learning through graph reconstruction attacks. The goal of the adversary here is to reconstruct the
graph structure of the training data given access to model explanations. Based on the different kinds of auxiliary information available to the adversary, we propose several graph reconstruction
attacks. We show that additional knowledge of post-hoc feature explanations substantially increases the success rate of these attacks.
Further, we investigate in detail the differences between attack
performance with respect to three different classes of explanation methods for graph neural networks: gradient-based, perturbationbased, and surrogate model-based methods. While gradient-based
explanations reveal the most in terms of the graph structure, we
find that these explanations do not always score high in utility. For
the other two classes of explanations, privacy leakage increases
with an increase in explanation utility. Finally, we propose a defense based on a randomized response mechanism for releasing
the explanations, which substantially reduces the attack success
rate. Our code is available at https://github.com/iyempissy/graphstealing-attacks-with-explanation.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Attack and Defense

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2206.14724.pdf'
url_code: 'https://github.com/iyempissy/graph-stealing-attacks-with-explanation'
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
