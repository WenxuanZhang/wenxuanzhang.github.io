---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Statistics
          description: A/B test + ANNOVA + Regression  
          icon: chart-line
          icon_pack: fas
        - name: Optimization
          description: LP/QP/NLP 
          icon: arrow-up-right-dots
          icon_pack: fas         
        - name: R
          description: tidyverse + xgboost + shiny  
          icon: r-project
          icon_pack: fab
        - name: Python
          description: pandas + scikit-learn + pytorch 
          icon: python
          icon_pack: fab
        - name: SQL
          description: database design + data pipeline 
          icon: database
          icon_pack: fas
        - name: Tableau
          description: dashboard design + Tableau Prep 
          icon: gauge
          icon_pack: fas
          
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
        - title: Revenue Management Lead
          company: Ferrero
          company_url: 'https://www.ferrero.com/'
          location: Chicago
          date_start: '2019-04-01'
          date_end: ''
        - title: Manager, Data Science 
          company: Inter Public Group
          company_url: 'https://www.interpublic.com/'
          location: New York
          date_start: '2015-09-14'
          date_end: '2019-03-21'
    design:
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Portfolio
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Marketing Mix Modeling
          tag: MMM
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false            
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'

   
 
---
