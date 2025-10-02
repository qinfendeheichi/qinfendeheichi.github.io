---
title: 'To Kill a Mutant: An Empirical Study of Mutation Testing Kills'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Vijay Krishna Palepu
  - James A. Jones

# Author notes (optional)
author_notes:

date: '2023-08-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In ISSTA 2023: Proceedings of the 32nd ACM SIGSOFT International Symposium on Software Testing and Analysis'
publication_short: In *ISSTA 2023*

abstract: 'Mutation testing has been used and studied for over four decades as a method to assess the strength of a test suite. This technique adds an artificial bug (i.e., a mutation) to a program to produce a mutant, and the test suite is run to determine if any of its test cases are sufficient to detect this mutation (i.e., kill the mutant). In this situation, a test case that fails is the one that kills the mutant. However, little is known about the nature of these kills. In this paper, we present an empirical study that investigates the nature of these kills. We seek to answer questions, such as: How are test cases failing so that they contribute to mutant kills? How many test cases fail for each killed mutant, given that only a single failure is required to kill that mutant? How do program crashes contribute to kills, and what are the origins and nature of these crashes? We found several revealing results across all subjects, including the substantial contribution of "crashes" to test failures leading to mutant kills, the existence of diverse causes for test failures even for a single mutation, and the specific types of exceptions that commonly instigate crashes. We posit that this study and its results should likely be taken into account for practitioners in their use of mutation testing and interpretation of its mutation score, and for researchers who study and leverage mutation testing in their future work.'

# Summary. An optional shortened abstract.
summary: Mutation scores alone can be misleading. The nature of kills must be considered when evaluating test quality.

tags:
  - Mutation Testing
  - Empirical Study
  - Source-code Oracles

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: https://doi.org/10.1145/3597926.3598090

# Custom links
links:
  - type: pdf
    url: "conference-paper.pdf"
  - type: slides
    url: slide.pptx

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Ways Mutants can be Killed in Joda Money: A Single Mutant can be Killed in Many Ways'
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
> The study reveals that mutant kills arise from diverse sources (e.g., crashes, assertions, multiple test failures), reflecting not just test effectiveness but also broader quality assurance practices in both source code and test code. This highlights that mutation scores alone can be misleading, and the nature of kills must be considered when evaluating test quality.


<!--# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).-->
