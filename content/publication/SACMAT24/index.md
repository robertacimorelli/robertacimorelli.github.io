---
title: 'Hierarchical Key Assignment Schemes with Key Rotation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alfredo De Santis
  - Anna Lisa Ferrara
  - Barbara Masucci

# Author notes (optional)
author_notes:
  - 'University of Molise, Italy'
  - 'University of Salerno, Italy'
  - 'University of Molise, Italy'
  - 'University of Salerno, Italy'

date: '2024-06-25T00:00:00Z'
doi: 'https://doi.org/10.1145/3649158.3657037'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th ACM Symposium on Access Control Models and Technologies (SACMAT '24).*

publication_short: In *Proceedings of the 29th ACM Symposium on Access Control Models and Technologies (SACMAT '24).*

abstract: Hierarchical structures are frequently used to manage access to sensitive data in various contexts, ranging from organizational settings to IoT networks. A Hierarchical Key Assignment Scheme (HKAS) is designed to cryptographically enforce access control in hierarchical structures. It operates by assigning secrets and encryption keys to a set of classes within a partially ordered hierarchy. This approach ensures that the secret of a higher-level class can be used to efficiently derive keys for all classes positioned at a lower level in the hierarchy. In this paper, we introduce a novel cryptographic primitive that we name HKAS with Key Rotation (KR-HKAS). This extension enhances the current HKAS framework by enabling a provably secure mechanism for periodically rotating both encryption keys and secrets, without necessitating a complete setup reset. This proactive approach effectively mitigates the risk of security breaches due to compromised cryptographic material, aligning with the best security practice.


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
