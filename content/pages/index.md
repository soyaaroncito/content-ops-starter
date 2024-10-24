---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: 'Maná del Día: Devocional'
      color: text-dark
      type: TitleBlock
    subtitle: ¡Ahora disponible en Amazon!
    text: >
      Este libro ha sido cuidadosamente creado con un enfoque especial en todas
      aquellas personas que desean profundizar su fe y anhelan fortalecer su
      relación con Dios.
    actions:
      - label: Comprar ahora
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Enséñame como
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/Captura de pantalla 2024-10-24 134352.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: COMPRAr AHORA
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Todo lo puedo en CRISTO que me fortalece.
      color: text-dark
      type: TitleBlock
    subtitle: 'Filipenses 4:13'
    text: ''
    actions: []
    media:
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: NUESTRO LEMA
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        justifyContent: center
        flexDirection: col-reverse
    type: GenericSection
  - type: FeaturedItemsSection
    title:
      text: Nuestros programas
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: La palabra de Dios para todos
    items:
      - type: FeaturedItem
        title: Desayuno Espiritual
        subtitle: Facebook
        text: >+
          Imágenes con versículos para reflexionar cada día acerca de nuestra
          relación con Dios y con el mundo, acerca de cómo debemos vivir en
          Cristo y para Cristo.

        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/favicon.svg
          styles:
            self:
              borderRadius: x-large
      - title: Cápsulas de audio
        subtitle: 'Por: Siempre Habrá un Nuevo Amanecer'
        text: |+
          #### **¡Próximamente!**

        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Cita de la semana
        subtitle: Blog
        text: |+
          #### **¡Próximamente!**

        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
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
      - label: ¡Únete ahora!
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: MANA DEL DIA
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Queremos escucharte
      color: text-dark
      type: TitleBlock
    subtitle: ¿Tienes dudas?
    text: >
      Ayúdanos a mejorar para que más personas puedan acercarse a Dios por medio
      de su palabra.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Nombre
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Correo Electrónico
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: 'Recomendaciones, sugerencias, dudas, etc.'
          width: full
          type: TextareaFormControl
          isRequired: true
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: ContactANOS
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Inicio - Maná del Día
  metaDescription: ''
  socialImage: /images/hero3.svg
  type: Seo
  addTitleSuffix: false
type: PageLayout
---
