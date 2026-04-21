---
title: "Dual-Forward-Secure Sanitizable Signatures"
authors:
- admin
- Anna Lisa Ferrara
date: "2026-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Sanitizable signature schemes allow a designated sanitizer to modify selected fields of a signed document without invalidating the signature. Existing schemes assume the sanitizer's key is permanently secure, but in practice sanitizer keys are long-lived: a hospital's data-release officer, a court registry, or a GDPR compliance system may hold the same sanitization capability for years or decades, making compromise a planning assumption rather than an exceptional event. We introduce Dual-Forward-Secure Sanitizable Signatures (DFS-SS), the first sanitizable signature scheme in which both the signing and the sanitization capability are forward-secure. After the signing key is compromised, past signatures remain unforgeable; after the sanitizer key is compromised, past sanitizations outside a configurable window W remain unforgeable. The window parameter captures a novel trade-off between operational flexibility and compromise resilience that does not arise in prior work. We formalize five security properties that jointly cover every non-trivial attack scenario, and give a generic construction from any forward-secure signature scheme, a forward-secure tagged chameleon hash (FS-TCH, a new primitive we introduce), and a collision-resistant Merkle commitment. The security model required particular care in ruling out two non-trivial attack vectors: an assembled-replay attack on the sanitization capability and a policy-reachability subtlety in the signer's unforgeability. We instantiate the construction with XMSS and a new lattice-based FS-TCH whose security reduces to Module-SIS, collision resistance of SHAKE-256, and PRG security of a GGM tree. A GGM-tree optimization keeps the sanitizer state under 500 bytes for practical parameters."
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []


#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
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
slides: ''
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
 -->