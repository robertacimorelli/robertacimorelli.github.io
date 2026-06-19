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

abstract: Many security and privacy-sensitive systems must control access to encrypted data based on dynamic operational context, such as workflow stage, safety mode, or emergency conditions. Data producers cannot anticipate which context will apply at processing time, and the component observing context cannot be trusted with plaintext or policy structure. Existing mechanisms, including Access Control Encryption (ACE), assume that all authorization-relevant information is fixed at encryption time, and offer no mechanism to incorporate context that becomes available only after the data has been produced and forwarded. We introduce Contextual Reading ACE (CR-ACE), a framework for enforcing context-dependent read authorization without a trusted reference monitor. An honest-but-curious intermediary sanitizes sender ciphertexts and attaches public contextual attributes while remaining oblivious to message contents, principal identities, and authorization logic. Receivers locally enforce authorization as the conjunction of the global ACE policy and a contextual predicate embedded in their key material. We formalize a security model for CR-ACE, provide a construction and prove that it achieves contextual payload privacy, sender anonymity, sanitization security under context, and correct enforcement of both global and context-dependent authorization in our non-collusion model.


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

