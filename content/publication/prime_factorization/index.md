---
title: 'Scaling up prime factorization using self-organizing gates: A memcomputing approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tristan Sharp
  - Rishabh Khare
  - Erick Pederson
  - Fabio Traversa

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-09-15T00:00:00Z'
doi: https://doi.org/10.48550/arXiv.2309.08198'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: arXiv
publication_short: arXiv

abstract: We report preliminary results on using the MEMCPU Platform to compute the prime factorization of large biprimes. The first approach, the direct model, directly returns the factors of a given biprime. The second approach, the congruence model, returns smooth congruences to address the bottleneck of standard sieve methods. The models have size-dependent structure, and the MEMCPU Platform requires structure-dependent tuning for optimal performance. Therefore, for both models, we tuned the platform on sample problems up to a given size according to available resources. Then we generated RSA-like benchmark biprimes to perform rigorous scaling analysis. The MEMCPU timings over the tuned range followed low degree polynomials in the number of bits, markedly different than other tested methods including general number field sieve. MEMCPU's congruence model was the most promising, which was scaled up to 300-bit factorization problems while following a 2nd degree polynomial fit. We also discuss the approach to tuning the MEMCPU Platform for problems beyond the reach of today's most advanced methods. Finally, basic analysis of the acceleration expected from an ASIC implementation is provided and suggests the possibility of real time factorization of large biprimes.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [memcomputing, prime factorization, optimization]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2309.08198.pdf'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: 'https://www.youtube.com/watch?v=9gNDh28CKdk'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
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

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
