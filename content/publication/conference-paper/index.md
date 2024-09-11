---
title: 'Deep learning based reconstruction enables high-resolution electrical impedance tomography for lung function assessment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shihao Zeng
  - Wang Chun Kwok
  - Peng Cao
  - Fedi Zouari
  - Philip Tin Yun Lee
  - Russell W. Chan
  - Adrien Touboul

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-11-11T00:00:00Z'
doi: '10.1109/EMBC40787.2023.10340392'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 2023 45th Annual International Conference of the IEEE Engineering in Medicine & Biology Society 
publication_short: In IEEE EMBC 2024

abstract: Recently, deep learning based methods have shown potential as alternative approaches for lung time difference electrical impedance tomography (tdEIT) reconstruction other than traditional regularized least square methods, that have inherent severe ill-posedness and low spatial resolution posing challenges for further interpretation. However, the validation of deep learning reconstruction quality is mainly focused on simulated data rather than in vivo human chest data, and on image quality rather than clinical indicator accuracy. In this study, a variational autoencoder is trained on high-resolution human chest simulations, and inference results on an EIT dataset collected from 22 healthy subjects performing various breathing paradigms are benchmarked with simultaneous spirometry measurements. The deep learning reconstructed global conductivity is significantly correlated with measured volume-time curves with correlation > 0.9. EIT lung function indicators from the reconstruction are also highly correlated with standard spirometry indicators with correlation > 0.75.Clinical Relevance— Our deep learning reconstruction method of lung tdEIT can predict lung volume and spirometry indicators while generating high-resolution EIT images, revealing potential of being a competitive approach in clinical settings.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

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
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
