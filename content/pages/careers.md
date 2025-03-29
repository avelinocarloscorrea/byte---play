---
title: Carreras
slug: carreras
sections:
  - title:
      text: Un equipo que trabaja unido para innovar
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Únete a nuestro equipo y transforma el futuro digital
    text: >
      En Byte & Play, creemos en la colaboración y el crecimiento continuo. Nos
      esforzamos por crear un ambiente donde cada miembro del equipo pueda
      desarrollar su máximo potencial mientras trabajamos juntos para ofrecer
      soluciones digitales innovadoras.
    actions:
      - label: Ver posiciones abiertas
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
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
      altText: Equipo colaborando
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - title:
      text: Conoce al equipo
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
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
      text: Posiciones abiertas
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Encuentra tu próxima oportunidad
    items:
      - title: Ejecutivo de Cuentas
        subtitle: Ventas
        text: >-
          Forma parte de nuestro equipo de ventas y ayuda a conectar a nuestros
          clientes con soluciones digitales personalizadas.
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
      - title: Ingeniero de Software Open Source
        subtitle: Desarrollo
        text: >-
          Contribuye al desarrollo de proyectos innovadores y de código abierto
          que impactan a empresas en todo el mundo.
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
      - title: Ingeniero Senior de Software
        subtitle: Ingeniería
        text: >-
          Lidera proyectos complejos y colabora con un equipo talentoso para
          crear soluciones digitales de alto impacto.
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
      - label: Postúlate ahora
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
  metaTitle: Carreras - Byte & Play
  metaDescription: Únete al equipo de Byte & Play y transforma el futuro digital.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
