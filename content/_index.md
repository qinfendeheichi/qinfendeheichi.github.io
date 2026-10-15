---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-10-01
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
      archive:
        enable: false
    design:
      view: citation
  - block: markdown
    id: education
    content:
      title: Education
      text: |
        <ul class="elegant-education">
          <li>
            <span class="elegant-ed-area">Ph.D. Software Engineering (continuing)</span>
            <span class="elegant-ed-inst">University of California, Irvine</span>
          </li>
          <li>
            <span class="elegant-ed-area">M.S. Software Engineering</span>
            <span class="elegant-ed-inst">University of California, Irvine</span>
          </li>
          <li>
            <span class="elegant-ed-area">B.S. Computer Science</span>
            <span class="elegant-ed-inst">Jilin University, China</span>
          </li>
        </ul>
  
---
