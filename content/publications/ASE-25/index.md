---
title: 'What’s DAT Smell? Untangling and Weaving the Disjoint Assertion Tangle Test Smell'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Monil Narang
  - admin
  - James A. Jones

# Author notes (optional)
author_notes:

date: '2025-10-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In ASE 2025: 40th IEEE/ACM International Conference on Automated Software Engineering'
publication_short: In **ASE 2025**

abstract: 'Writing and maintaining good unit tests is essential for quality assurance. However, developers often deprioritize such maintenance, leading to tests that exhibit code smells, are bloated, and may be less effective. In this work, we characterize a novel test-code smell—Disjoint Assertion Tangle (DAT)—which occurs when a test method verifies multiple, logically unrelated behaviors that can be separated. We propose a program analysis-based approach that automatically detects DATs and refactors them into separate focused test methods. We implemented this approach as a tool called U2W. By separating unrelated testing logic, U2W enhances readability, maintainability, and fault localization, while exposing hidden test clones and duplicated code. It then seizes these opportunities by converting structurally similar tests into compact, parameterized unit tests (PUTs), reducing redundancy and enabling more scalable, extensible test designs.

To evaluate our approach and tool, we conducted a number of evaluations: (1) a large-scale, quantitative study to study the prevalence of the test smell and the effects of their refactoring, (2) a user survey to assess developers’ opinions and preferences of the unrefactored and refactored test code, and (3) pull requests that were issued to original project maintainers to assess the acceptability of our refactorings. Our quantitative study was conducted on 42,334 tests across 49 open-source projects. We found the DAT smell in 95.9% of the subject projects, affecting an average of 8.59% of analyzed tests. In total, we identified and refactored 3,638 smelly tests, untangled them into 31,837 test-execution logics, and then weaved 14,343 of them into 1,713 extensible PUT methods. These refactorings reduced the executable test-code lines in smelly tests by an average of 36.33%. Our user survey involving 49 industrial and academic participants demonstrated strong preference for our refactored test cases over their original, unrefactored versions. Additionally, we submitted 19 pull requests based on our automated refactorings; 16 of these were accepted by project maintainers. These results suggest that U2W effectively improves test-suite quality, and validate our novel test smell aligns closely with developers’ intuitions and practices.'

# Summary. An optional shortened abstract.
summary: We introduce Disjoint Assertion Tangle (DAT), a novel test-code smell, and present U2W, a tool that detects and refactors such smells into focused and parameterized tests to improve readability, maintainability, and scalability.

tags:
  - Test Smell Refactoring
  - DAT
  - Eager Test

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
#  ids:
 #   doi: tobeupdated

# Custom links
links:
  #- type: pdf
  #  url: "conference-paper.pdf"
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

> [!Tip]
> Our large-scale study across 49 open-source projects shows that DATs are highly prevalent (affecting ~8.6% of tests) and that U2W’s automated refactorings reduce test-code size by 36% on average while exposing opportunities for parameterization. Developer surveys and accepted pull requests further confirm that U2W’s refactorings align with developer preferences and improve real-world test quality.
<!--# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).-->
