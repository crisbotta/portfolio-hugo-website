---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true
active: true

# Order that this section appears on the page.
weight: 80

# Section title
title: Gallery


# Section design
design:
  # Use a 1-column layout
  columns: "1"
  view: masonry
  
gallery_item:
- album: default
  image: Digitalizar0040.jpg
  caption: Write your image 1 caption here
- album: default
  image: Digitalizar0042.jpg
  caption: Write your image 2 caption here
---

{{< gallery album="default" resize-options="200x" >}}
