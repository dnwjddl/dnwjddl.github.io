---
title: blog
summary: paper-review
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: blog
    content:
      title: blog
      filters:
        folders:
          - blog
    design:
      view: article-grid
      columns: 2
---
