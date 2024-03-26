---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ""
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    content:
      title: Recent publications
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publications
    design:
      view: card
      columns: '1'
---