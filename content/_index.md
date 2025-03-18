---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        The Frequency Agile Solar Radiotelescope
      image:
        filename: FASR_illustration_sml.jpg
      primary_action:
        text: Get Started
        url: https://example.com
        icon: sparkles
      secondary_action:
        text: Read the docs
        url: https://example.com

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
        The **Frequency Agile Solar Radiotelescope (FASR)** is a next generation radio interferometer array dedicated to solar and space weather research. FASR will build upon the technology that enabled the [Expanded Owens Valley Solar Array](https://ovsa.njit.edu/), but with 10 times more antennas and an order of magnitude wider bandwidth, it will bring the transformative technique of "ultrawide-band radio camera" to solar and heliospheric studies. 

        ### Science Objectives

        ### Technical Overview

        ### Current Status
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: FASR_illustration_birdeye.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: FASR Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
