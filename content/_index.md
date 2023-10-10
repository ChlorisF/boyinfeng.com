---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: collection
    content:
      title: Research Papers
      filters:
        folders:
          - research
      #  exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: boyin.feng.21@ucl.ac.uk
      address:
        street: 2 Xisanhuan North Avenue
        city: Beijing
        postcode: '100089'
        country: China
        country_code: CN
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
