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
        about: 'Bio'
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
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: 'How individual movement decisions scale up to population dynamics in migratory birds — and what that means for conservation.'
    design:
      columns: '1'
      spacing:
        padding: ['1rem', '0', '0.5rem', '0']
  - block: cta-image-paragraph
    content:
      items:
        - image: 'research/movement-ecology.svg'
          title: 'Movement Ecology'
          text: >-
            Using GPS and satellite telemetry, I study how birds move through Patagonian
            landscapes — from probabilistic flight-altitude models assessing wind-turbine
            collision risk in the Two-banded Plover to migration strategies of high-latitude
            shorebirds and passerines.
    design:
      spacing:
        padding: ['0.5rem', '0', '0.5rem', '0']
  - block: cta-image-paragraph
    content:
      items:
        - image: 'research/population-dynamics.svg'
          title: 'Population Dynamics'
          text: >-
            My core research uses mark-recapture, integral projection, and state-space models
            to estimate survival, growth, and abundance — from two decades of banding data on
            Patagonian forest birds to Bayesian abundance models for the Ruddy-headed Goose in
            Magallanes.
    design:
      spacing:
        padding: ['0.5rem', '0', '0.5rem', '0']
  - block: cta-image-paragraph
    content:
      items:
        - image: 'research/conservation.svg'
          title: 'Conservation'
          text: >-
            I translate population data into conservation action: coordinating Chile's national
            bird monitoring plan with the Red de Observadores de Aves y Vida Silvestre de Chile
            (ROC), leading the *State of Chile's Birds* report, and running the *CCAP Chile
            Shorebirds* population assessment with Manomet at Bahía Lomas.
    design:
      spacing:
        padding: ['0.5rem', '0', '0.5rem', '0']
  - block: cta-image-paragraph
    content:
      items:
        - image: 'research/evolutionary-ecology.svg'
          title: 'Evolutionary Ecology'
          text: >-
            My doctoral research examined how insularity shapes avian growth and body-size
            evolution in an island Silvereye population, combining phylogenetic meta-analysis
            with individual-based growth models to test predictions about life-history
            evolution on islands.
    design:
      spacing:
        padding: ['0.5rem', '0', '2rem', '0']
  - block: collection
    id: news
    content:
      title: Recent News
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
