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
publication_short: In **ICSE 2025**

abstract: 'Mutation testing was proposed to identify weaknesses in test suites by repeatedly generating artificially faulty versions of the software (i.e., mutants) and determining if the test suite is sufficient to detect them (i.e., kill them). When the tests are insufficient, each surviving mutant provides an opportunity to improve the test suite. We conducted a study and found that many such surviving mutants (up to 84% for the subjects of our study) are detectable by simply augmenting existing tests with additional assertions, or assertion amplification. Moreover, we find that many of these mutants are detectable by multiple existing tests, giving developers options for how to detect them. To help with these challenges, we created a technique that performs memory-state analysis to identify candidate assertions that developers can use to detect the surviving mutants. Additionally, we build upon prior research that identifies “crossfiring” opportunities - tests that coincidentally kill multiple mutants. To this end, we developed a theoretical model that describes the varying granularities that crossfiring can occur in the existing test suite, which provide opportunities and options for how to kill surviving mutants. We operationalize this model to an accompanying technique that optimizes the assertion amplification of the existing tests to crossfire multiple mutants with fewer added assertions, optionally concentrated within fewer tests. Our experiments show that we can kill all surviving mutants that are detectable with existing test data with only 1.1% of the identified assertion candidates, and increasing by a factor of 6x, on average, the number of killed mutants from amplified tests, over tests that do not crossfire.'

# Summary. An optional shortened abstract.
summary: Sometimes a simple, localized edit, i.e., adding an additional assertion, may substantially improve the test suite effectiveness by crossfiring mutants.

tags:
  - Assertion Amplification
  - Mutation Testing
  - Crossfire

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: https://doi.org/10.1109/ICSE55347.2025.00150

# Custom links
links:
  - type: pdf
    url: "conference-paper.pdf"
  - type: slides
    url: slide.pptx

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Test and Assertion Crossfiring Capabilities'
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
> Up to 84% of surviving mutants can be detected by augmenting existing tests with additional assertions, and many are detectable by multiple tests, giving developers flexibility.

<!--# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).-->
