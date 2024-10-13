---
title: Careers
slug: careers
sections:
  - title:
      text: Equipo de Trabajo
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: 'SEO-posicionamiento: Líderes en Diseño Web y Estrategias SEO'
    text: >+
      En **SEO-posicionamiento**, estamos comprometidos en llevar tu negocio al
      siguiente nivel a través de soluciones integrales de diseño web y
      estrategias avanzadas de SEO. Nuestro equipo está liderado por **Oswaldo
      Talero**, un experto en posicionamiento digital con una amplia trayectoria
      en mejorar la visibilidad y rendimiento de sitios web en motores de
      búsqueda. Nos especializamos en crear páginas web personalizadas,
      funcionales y optimizadas para SEO desde su desarrollo, asegurando que no
      solo sean atractivas visualmente, sino también efectivas en atraer tráfico
      y generar conversiones. En **SEO-posicionamiento**, nuestro objetivo es
      que tu presencia online sea un motor de crecimiento para tu negocio.

    actions:
      - label: Contáctanos
        url: 'tel:322-957-6512'
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
        altText: 322 957 6512
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - title:
      text: Conoce al Equipo
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection
  - title:
      text: Posiciones Abiertas
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Postulaciones
    items:
      - title: Ejecutivos de Cuentas
        subtitle: Ventas
        text: |+
          Personal Experto en Ventas y Marqueting

        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: INGENIERO DE CÓDIGO ABIERTO
        subtitle: PROGRAMACIÓN
        text: |+
          Profesional en Programación

        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: Senior Software Engineer
        subtitle: Engineering
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: Apply now
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
