---
# Leave the homepage title empty to use the site title
title: Raven Otero
date: 2022-10-24
type: landing

sections:
#  - block: about.avatar
#    id: about
#    content:
 #     # Choose a user profile to display (a folder name within `content/authors/`)
 #     username: admin
 #     # Override your bio text from `authors/admin/_index.md`?
 #     text:
  - block: markdown
    id: poem
    content:
      title: neomexicana
      subtitle:
      text: <p style="text-align: center;">strive to constellate<br>
            dare to love at the crossroads<br>
            reach for the paradigm at dusk<br>
            <br>
            billowing from the plateau ripped to the bone<br>
            what silver steel would have stained with red clay<br>
            a mahogany portrait from days long past is carried<br>
            with a howl and a sigh.<br>
            <br>
            walking as a shifter<br>
            sifting the sands of mixed blood<br>
            survival is painted through turquoise abstraction, preliminary love.<br></p>
  - block: markdown
    id: section-2
    content:
      title:
      subtitle:
      text: <p style="text-align: justify;">Raven Delfina Otero-Symphony is an incoming graduate student at the International Space University and first-generation graduate of The University of New Mexico. Interdisciplinary research is the cornerstone of her community scientist journey.</p>
  - block: experience
    content:
      title: Experience
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
          date_start: '2022'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Bachelor of Science, Statistics
          company: University of New Mexico
          company_url: 'https://www.unm.edu'
          company_logo: org-x
          location: New Mexico
          date_start: '2018'
          date_end: '2022'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: tag_cloud
    content:
      title: Explore
    design:
      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
 # - block: portfolio
 #   id: projects
 #   content:
 #     title: Projects
 #     filters:
 #       folders:
 #         - project
 #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
 #     default_button_index: 0
 #     # Filter toolbar (optional).
 #     # Add or remove as many filters (`filter_button` instances) as you like.
 #     # To show all items, set `tag` to "*".
 #     # To filter by a specific tag, set `tag` to an existing tag name.
 #     # To remove the toolbar, delete the entire `filter_button` block.
 #     buttons:
 #       - name: All
 #         tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
 #   content:
 #     title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: contact
#    id: contact
#    content:
#      title: Keep in Touch
#      subtitle:
#      text: |-
#        How to make a subscription box?
#      # Contact (add or remove contact options as necessary)
#      email: ravenotero@unmalumni.com
#      # Automatically link email and phone or display as text?
#      autolink: true
#      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
#    design:
#      columns: '2'
---
