---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: ''
      text: ''
    design:
      columns: '1'
      spacing:
        padding: [0, 0, 0, 0]
      css_style: 'min-height: 42vh;'
      background:
        image:
          filename: 'authors/banner-bahia-lomas.jpg'
          size: cover
          position: center
          filters:
            brightness: 0.85
      section_break:
        fade_bottom: '#ffffff'
        size: '16rem'
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: ''
        url: ''
      headings:
        about: 'Biografía'
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: false

      spacing:
        padding: ['1rem', '0', '2rem', '0']

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'Proyectos Actuales'
      subtitle: ''
      text: |-
        **Estado de las Aves de Chile** — un informe nacional sobre el estado de las aves, construido a partir de datos de eBird Status & Trends y de rasgos de AVONET, que resume las tendencias poblacionales y el estado de conservación de la avifauna chilena.

        **Aves Playeras CCAP Chile** — estimaciones poblacionales de aves playeras chilenas en colaboración con Manomet, replicando y extendiendo la metodología previa (Faria et al.) con modelos mejorados basados en glmmTMB.
    design:
      columns: '1'
      spacing:
        padding: ['1rem', '0', '2rem', '0']
  - block: collection
    id: papers
    content:
      title: Publicaciones
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: news
    content:
      title: Noticias Recientes
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
