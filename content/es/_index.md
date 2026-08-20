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
    id: research
    content:
      title: 'Investigación'
      subtitle: ''
      text: 'Cómo las decisiones individuales de movimiento se traducen en dinámica poblacional en aves migratorias — y lo que eso significa para la conservación.'
    design:
      columns: '1'
      spacing:
        padding: ['1rem', '0', '0.5rem', '0']
  - block: cta-image-paragraph
    content:
      items:
        - image: 'research/movement-ecology.svg'
          title: 'Ecología del Movimiento'
          text: >-
            Mediante telemetría GPS y satelital, estudio cómo las aves se desplazan por los
            paisajes patagónicos — desde modelos probabilísticos de altitud de vuelo para
            evaluar el riesgo de colisión con aerogeneradores en el Chorlo de Doble Collar,
            hasta estrategias migratorias de aves playeras y paseriformes de alta latitud.
    design:
      spacing:
        padding: ['0.5rem', '0', '0.5rem', '0']
  - block: cta-image-paragraph
    content:
      items:
        - image: 'research/population-dynamics.svg'
          title: 'Dinámica Poblacional'
          text: >-
            El eje de mi investigación usa modelos de marca-recaptura, de proyección integral
            y de espacio de estados para estimar supervivencia, crecimiento y abundancia —
            desde dos décadas de datos de anillamiento de aves de bosque patagónicas hasta
            modelos bayesianos de abundancia para el Canquén Colorado en Magallanes.
    design:
      spacing:
        padding: ['0.5rem', '0', '0.5rem', '0']
  - block: cta-image-paragraph
    content:
      items:
        - image: 'research/conservation.svg'
          title: 'Conservación'
          text: >-
            Traduzco los datos poblacionales en acción de conservación: coordinando el plan
            nacional de monitoreo de aves con la Red de Observadores de Aves y Vida Silvestre
            de Chile (ROC), liderando el informe *Estado de las Aves de Chile* y ejecutando la
            evaluación poblacional *Aves Playeras CCAP Chile* con Manomet en Bahía Lomas.
    design:
      spacing:
        padding: ['0.5rem', '0', '0.5rem', '0']
  - block: cta-image-paragraph
    content:
      items:
        - image: 'research/evolutionary-ecology.svg'
          title: 'Ecología Evolutiva'
          text: >-
            Mi investigación doctoral examinó cómo la insularidad moldea el crecimiento y la
            evolución del tamaño corporal en una población insular de Zosterops, combinando
            meta-análisis filogenético con modelos de crecimiento individual para poner a
            prueba predicciones sobre la evolución de la historia de vida en islas.
    design:
      spacing:
        padding: ['0.5rem', '0', '2rem', '0']
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
