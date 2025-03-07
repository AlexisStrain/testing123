---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        The Kato Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Kato Lab** investigates cellular responses to environmental factors using microalgae and plants. The lab employs a range of techniques, including 3D printing, light and fluorescence microscopy, bioluminescence analysis, cellular assays, genetic modification, nucleotide and protein analyses, chromatography, and mathematical modeling.
:
Beyond fundamental research, the team is actively engaged in applied science. One of their key projects focuses on developing biodegradable Mardi Gras beads using bio-based materials, addressing environmental concerns associated with traditional plastic beads.

Another major initiative aims to establish a microalgae-based industry in Louisiana by converting salt-intruded rice fields into large-scale microalgae cultivation facilities. These microalgae produce medically relevant compounds, which are then extracted and purified for therapeutic applications.

The lab also explores the potential of these natural compounds in treating human diseases, such as asthma, through experiments using cultured human cells and mouse models. 
  
  - block: collection
    content:
      title: Latest News
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
      page_type: post
    design:
      view: card
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
          filename: coders.jpg
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
      title: Latest Preprints
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
