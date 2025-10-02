---
title: 'Leveraging Propagated Infection to Crossfire Mutants'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Vijay Krishna Palepu
  - James A. Jones

# Author notes (optional)
author_notes:

date: '2025-05-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In ICSE 2025: 47th IEEE/ACM International Conference on Software Engineering'
publication_short: In *ICSE 2025*

abstract: 'The mechanics of how a fault reveals itself as a test failure is of keen interest to software researchers and practitioners alike. An improved understanding of how faults translate to failures can guide improvements in broad facets of software testing, ranging from test suite design to automated program repair, which are premised on the understanding that the presence of faults would alter some test executions.
In this work, we study such effects by mutations, as applicable in mutation testing. Mutation testing enables the generation of a large corpus of faults; thereby harvesting a large pool of mutated test runs for analysis. Specifically, we analyze more than 1.1 million mutated test runs to study if and how the underlying mutations induce infections that propagate their way to observable failures.
We adopt a broad-spectrum approach to analyze such a large pool of mutated runs. For every mutated test run, we are able to determine: (a) if the mutation induced a state infection; (b) if the infection propagated through the end of the test run; and (c) if the test failed in the presence of a propagated infection.
By examining such infection-, propagation- and revealability-effects for more than 43,000 mutations executed across 1.1 million test runs we are able to arrive at some surprising findings. Our results find that once state infection is observed, propagation is frequently detected; however, a propagated infection does not always reveal itself as a test failure. We also find that a significant portion of survived mutants in our study could have been killed by observing propagated state infections that were left undetected. Finally, we also find that different mutation operators can demonstrate substantial differences in their specific impacts on the execution-to-failure ripples of the resulting mutations.'

# Summary. An optional shortened abstract.
summary: Many faults propagate without revealing as failures, suggesting that observing propagated infections can substantially improve test effectiveness through assertion amplification.

tags:
  - Mutation Testing
  - Empirical Study
  - RIPR Model
  - Fault Error Propagation

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: https://doi.org/10.1145/3597503.3639179

# Custom links
links:
  - type: pdf
    url: "conference-paper.pdf"
  - type: slides
    url: slide.pptx

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Ripples of Mutations  in JfreeChart, aggregated by 320,357 mutation runs'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!Tip]
> Our large-scale study of 1.1M mutated test runs shows that while infections often propagate, while many do not manifest as observable test failures, leaving faults undetected. These findings highlight that mutation operators differ in how faults ripple into failures, and that detecting propagated infections may significantly improve test effectiveness through assertion amplification.


<!--# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).-->
