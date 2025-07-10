---
title: 'About Me'
date: 2023-10-24
type: landing

menu:
  main:
    weight: 14

sections:
  - block: hero
    content:
      title: "About Me"
      text: "A bit more about my background, interests, and what brought me to this work."
      image: my-photo.jpg
    design:
      background: primary
      image_position: right
      image_shape: circle
      alignment: left
  - block: collection
    content:
      filters:
        folders:
          - about
    design:
      view: article-grid
      fill_image: false
      columns: 1
---
