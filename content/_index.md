---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing
# type: widget_page


sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection #collection
    id: pub
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false   
    design:
      columns: '1'
      view: list
---
