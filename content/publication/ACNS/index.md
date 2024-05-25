---
title: 'Identity-Based Matchmaking Encryption from Standard Lattice Assumptions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Andrea De Cosmo 
  - Anna Lisa Ferrara

# Author notes (optional)
author_notes:
  - 'University of Molise'
  - 'Leonardo S.p.A. Cyber & Security Solutions Division'
  - 'University of Molise'

date: '2024-10-16T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-031-54773-7_7'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 22nd International Conference on Applied Cryptography and Network Security (ACNS '24).*
publication_short: In *Proceedings of the 22nd International Conference on Applied Cryptography and Network Security (ACNS '24).*

abstract: Identity-Based Matchmaking Encryption (IB-ME), initially proposed by Ateniese et al. (Crypto 2019), is an extension of Identity-Based Encryption (IBE) that emphasizes privacy and authenticity. It ensures that the content of a message is only revealed when the recipient’s identity matches the intended recipient specified by the sender, and when the target sender’s identity, chosen by the receiver during decryption, matches the actual sender’s identity. In cases where there is a mismatch, no information about the sender, receiver, or message is disclosed. Francati et al. (IndoCrypt 2021) observed that the privacy definition for IB-ME solely guarantees the concealment of the message and sender identity when the receiver’s identity does not match the intended recipient specified by the sender. It does not consider whether the target sender’s identity matches the actual sender’s identity. To overcome this limitation, they proposed an enhanced privacy notion and developed an IB-ME scheme that achieves it in the plain model, even though relying on non-standard assumptions. In this paper, we address the problem of constructing an IB-ME scheme that offers enhanced privacy under standard assumptions with particular emphasis on post quantum security. Specifically, we first show how to obtain an IB-ME that achieves the notion of enhanced privacy using as building blocks any anonymous IBE and reusable computational extractors. Next, we show how to construct an IB-ME starting from an IB-ME satisfying enhanced privacy and a context-hiding homomorphic signature, thereby ensuring not only enhanced privacy but also authenticity. Notably, our framework allows for secure IB-ME schemes to be instantiated in the standard model from lattice assumptions, thus providing also post-quantum security.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

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
