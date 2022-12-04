---
title: "Estimation and uncertainty quantification of magma interaction times using statistical emulation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Stéphane Guerrier
- Chiara P. Montagna
- Maria-Pia Victoria-Feser
- Luca Caricchi

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-12-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: EarthArXiv
publication_short:

abstract: Evolution of volcanic plumbing systems towards eruptions of different styles and sizes largely depends on processes at crustal depths that are outside our observational capabilities. These processes can be modeled and the outputs of the simulations can be compared with the chemistry of the erupted products, geophysical and geodetic data to retrieve information on the architecture of the plumbing system and the processes leading to eruption. The interaction between magmas with different physical and chemical properties often precedes volcanic eruptions. Thus, sophisticated numerical models have been developed that describe in detail the dynamics of interacting magmas, specifically aimed at evaluating pre-eruptive magma mingling and mixing timescales. However, our ability to explore the parameters space in order to match petrological and geophysical observations is limited by the extremely high computational costs of these multiphase, multicomponent computational fluid dynamics simulations. To overcome these limitations, we present a statistical emulator that is able to reproduce the numerical simulations results providing the temporal evolution of the distribution of magma chemistry as a function of a set of input parameters such as magma densities and reservoir shapes. The whole rock composition of volcanic rocks is one of the most common measurable parameter collected for eruptions. The statistical emulator can be used to invert the observed distribution of whole rock chemistry to determine the duration of interaction between magmas preceding an eruption and identify the best matching input paramaters of the numerical model. Importantly, the statistical emulator intrinsically includes error propagation, thus providing confidence intervals on predicted interaction timescales on the base of the intrinsic uncertainty of the input parameters of the numerical simulations.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://doi.org/10.31223/X5D36F
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
# example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
