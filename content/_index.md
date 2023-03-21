---
# Leave the homepage title empty to use the site title
title: Raven Otero
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: markdown
    id: description
    content:
      title:
      subtitle:
      text: Raven Delfina Otero-Symphony is an incoming graduate student at the International Space University and first-generation graduate of The University of New Mexico. Her professional experience and research interests are an interdisciplinary weaving of her rigorous and creative ability to explore, innovate, and persevere in the face of challenge, injustice, and tribulation.
  - block: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Master of Space Studies
          company: International Space University
          company_url: 'https://www.isunet.edu'
          company_logo: org-gc
          location: France
          date_start: '2023-08-31'
          date_end: ''
          description: |2-
              Research interests:

              * New Space Ecosystem
              * Space Policy & Ethics
              * Sustainability
        - title: Bachelor of Science, Statistics
          company: University of New Mexico
          company_url: 'https://www.unm.edu'
          company_logo: org-x
          location: New Mexico
          date_start: '2018-08-16'
          date_end: '2022-05-14'
          description:  |2-
              Research interests:

              * Biostatistics Methods
              * Spatio-Temporal Modeling
              * Qualitative Methodology
    design:
      columns: '2'
  - block: tag_cloud
    content:
      title: Explore
    design:
      columns: '2'
---
