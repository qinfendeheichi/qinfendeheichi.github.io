---
title: 'Revealing Regressions: A Comparative Study of State-Capture
Strategies in Validating Program Behavior'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Vijay Krishna Palepu
  - James A. Jones

# Author notes (optional)
author_notes:

date: '2026-02-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-02-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In FSE 2026: ACM International Conference
on the Foundations of Software Engineering'
publication_short: In **FSE 2026 (accepted)**

abstract: 'A central challenge in software testing is deciding which parts of a program’s state to check as evidence of correct behavior to reveal regressions. These checks are embodied as test oracles, typically as assertions in test cases. State observation strategies play a decisive role in shaping how effectively regressions can be revealed. Such strategies range from exhaustive memory snapshots to selective attribute checks via getter methods and nullability checks. These strategies are deeply embedded in both research and practice: academic work has explored heuristic- and serialization-based oracles, while industry has widely adopted snapshot testing. Despite their importance, the effects of different state-capture choices remain poorly understood from a scientific perspective. In this work, we present an experimental framework for systematically analyzing these design choices along the dimensions of observation scope, extraction approach, and extraction depth. Using this framework, we conduct an empirical study across twelve real-world projects, measuring how state-capture strategies influence regression-revealing capability and the richness of oracle information. Our findings reveal that human-written assertions often under-utilize available program state, achieving well below the fault-revealing potential of systematic observation strategies. Simple design choices, such as exposing unchecked intermediate return values, carefully selecting getters, and deepening state extraction, can yield measurable improvements (avg. 35.7%) in regression detection without needing to observe an overwhelmingly large amount of program-state data. Additionally, we highlight the challenges of observability, assertion desirability, and the trade-offs of capturing richer program states. Such insights show how small design choices can yield major differences in regression detection and potentially offer concrete directions for both tool builders and practitioners.'

# Summary. An optional shortened abstract.
# summary: '[ASE 25] We introduce Disjoint Assertion Tangle (DAT), a novel test-code smell, and present U2W, a tool that detects and refactors such smells into focused and parameterized tests to improve readability, maintainability, and scalability.'

# tags:
#   - Test Smell Refactoring
#   - Parameterized Unit Test
#   - DAT
#   - Eager Test

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
 ids:
   doi: https://doi.org/10.1145/3797107

# Custom links
links:
  - type: pdf
    url: "conference-paper.pdf"
  #- type: slides
   # url: slide.pptx

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'A real-world test from APACHE SEATA exhibiting two semantically independent assertion clusters'
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

<!--# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).-->
