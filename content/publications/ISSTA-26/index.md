---
title: 'How Does Killing Surviving Mutants Help Detect Real Bugs with Assertion Generation: A Controlled Experiment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Vijay Krishna Palepu
  - James A. Jones

# Author notes (optional)
author_notes:

date: '2026-04-19T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In Proceedings of the 32nd ACM SIGSOFT International Symposium
on Software Testing and Analysis (ISSTA 2026)'
publication_short: In **ISSTA 2026 (accepted)**

abstract: 'Killing surviving mutants is a central activity of mutation testing. This activity is motivated by the coupling-effect hypothesis: tests that expose simple artificial faults can also detect more complex, previously unseen real bugs. Despite these claimed benefits, automated studies have not directly measured the causal impact of mutant killing on real-bug detection. This limitation stems from open-ended mutant-killing strategies and a fundamental evaluation asymmetry that obscures causal attribution. In this work, we present the first large-scale controlled experiment that directly measures whether killing surviving mutants, without knowledge of future real bugs, would have enabled their detection. We model mutant killing as a selective, incremental process under realistic budget constraints, and we restrict test improvements to assertion augmentation. This restriction enables precise attribution of each test augmentation to a specific mutant-killing action. To support the experiment, we design a fully automated, fault-based assertion-augmentation technique that operates uniformly on mutants and real bugs and integrate it into Defects4J. Our controlled experiment yields several key empirical insights: (1) Across 642 Defects4J bugs, we find that 104 bugs would become detectable by adding an additional assertion to an existing passing, non-triggering test. (2) When coupling exists, a real bug is, on average, coupled with 21 surviving mutants, through which mutant killing can produce triggering tests. This number is substantially higher than the average of two mutants reported in prior studies. In those studies, coupling is inferred solely from documented bug-fixing tests rather than from tests derived via mutant killing. (3) Among these bugs, 63 of the 104 are detectable through principled mutant-killing (test augmentation) process. Notably, killing a randomly selected 30% of relevant surviving mutants, using only one assertion per mutant, suffices to detect 84.5% of these bugs. (4) By substituting mutants with real bugs and comparing their resulting assertion augmentation outputs, we find that real bugs induce broader behavioral effects than mutants, affecting more memory state locations, variables, and tests. (5) When mutation-derived assertions detect real bugs, they validate program outputs that overlap with, and are often strict subsets of, those affected by the real bugs. This offers a mechanistic explanation for why killing simple mutants can enable the detection of more complex real bugs.'

# Summary. An optional shortened abstract.
# summary: ''

# tags:
#   - Mutation Testing
#   - Assertion Generation

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
# hugoblox:
#  ids:
#    doi:

# Custom links
links:
  # - type: pdf
  #   url: ""
  # - type: slides
  #   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---

<!--# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).-->
