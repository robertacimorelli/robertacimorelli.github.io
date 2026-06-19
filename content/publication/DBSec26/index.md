---
title: 'Anonymous Hierarchical Key Assignment Schemes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alfredo De Santis
  - Anna Lisa Ferrara
  - Manuela Flores
  - Barbara Masucci

# Author notes (optional)
author_notes:
  - 'University of Molise'
  - 'University of Salerno'
  - 'University of Molise'
  - 'University of Molise'
  - 'University of Salerno'

date: '2026-01-01T00:00:00Z'
#doi: 'https://doi.org/10.1007/978-3-031-54773-7_7'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: To appear In *Proceedings of the 40th Annual IFIP WG 11.3 Conference on Data and Applications Security and Privacy (DBSec 2026)*
publication_short: To appear In *Proceedings of the 40th Annual IFIP WG 11.3 Conference on Data and Applications Security and Privacy (DBSec 2026)*

abstract: Hierarchical Key Assignment Schemes (HKAS) are cryptographic tools that enforce access control in partially ordered hierarchies, allowing each class to derive the keys of all classes below it. All existing schemes assume that the hierarchy structure is publicly known. In many modern applications, however, the topology of the access hierarchy is itself sensitive information that should be protected. We study the problem of extending existing HKAS to hide the hierarchy topology from adversaries who corrupt a subset of classes, without redesigning the underlying schemes from scratch. We formalize this goal through new security definitions capturing graph-hiding and topology privacy, and we propose a simple generic compiler that transforms any HKAS satisfying a natural anonymizability condition into one that achieves these stronger guarantees. Our main technical contribution is the identification of this condition, which requires that the joint distribution of the public values of the scheme be computationally indistinguishable from independently simulated random values. We show that this condition is not implied by the standard indistinguishability (IND-ST) security notion alone, by exhibiting a concrete counterexample based on the Akl-Taylor scheme. On the positive side, we verify that the Encryption Based Construction (EBC) and the Dynamic Encryption Based Construction (DEBC) of De Santis et al. both satisfy our condition and can therefore be made topology-private through our lightweight transformation.


# Summary. An optional shortened abstract.
summary: To appear In *Proceedings of the 40th Annual IFIP WG 11.3 Conference on Data and Applications Security and Privacy (DBSec 2026)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
 # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

