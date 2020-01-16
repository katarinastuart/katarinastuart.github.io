---
title: YAML Front Matter
description: A very simple way to add structured data to a page.
permalink: /research/

defaults:
  # _pages
  - scope:
      path: ""
      type: pages
    values:
      layout: single
      author_profile: true
      
---
<h1> {{ title }} </h1>
<p> {{ description }} </p>
Page content here...
