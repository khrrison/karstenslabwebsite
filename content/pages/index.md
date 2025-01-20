---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Karstens Lab
      color: text-dark
      type: TitleBlock
    subtitle: Microbiome Bioinformatics
    text: >
      The Karstens Lab is an interdisciplinary group at [Oregon Health & Science
      University](www.ohsu.edu) in the Department of Medical Informatics,
      Division of Bioinformatics and Computational Biomedicine. We study the
      human microbiome and its relationship to health and disease using
      high-throughput sequencing and analytical chemistry approaches. We
      specialize in the urinary microbiome and other low microbial biomass
      niches, but also have projects involving the gut microbiome.
    actions: []
    media:
      url: /images/user-full-2.jpg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
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
  - posts:
      - content/pages/blog/microshades-featured-by-asm-journal.md
      - content/pages/blog/karstens-lab-at-2023-augs-pfd.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: small-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
    title:
      type: TitleBlock
      text: Posts
      color: text-dark
    subtitle: Lab news and updates
    showExcerpt: true
    actions: []
  - type: FeaturedItemsSection
    title:
      text: Skills
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: We specialize in the following
    items:
      - type: FeaturedItem
        title: Microbiome Analysis
        tagline: ''
        subtitle: ''
        text: ''
        image:
          type: ImageBlock
          url: /images/microbiome.svg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
      - type: FeaturedItem
        title: R Software
        tagline: ''
        subtitle: ''
        text: ''
        image:
          type: ImageBlock
          url: /images/R_logo.svg.png
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
      - type: FeaturedItem
        title: Data Analysis
        tagline: ''
        subtitle: ''
        text: ''
        image:
          type: ImageBlock
          url: /images/generated-svg-image.svg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
      - type: FeaturedItem
        title: Bioinformatics
        tagline: ''
        subtitle: ''
        text: ''
        image:
          type: ImageBlock
          url: /images/bioinformatic.svg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions: []
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
        fontWeight: 400
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
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Projects
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: All things are difficult before they are easy
    items:
      - type: FeaturedItem
        title: Low Microbial Biomass Enviornments
        subtitle: ''
        text: >
          Sequencing data that is used to study the microbiome is error prone,
          especially in samples originating from low microbial biomass
          environments.
        image:
          type: ImageBlock
          url: >-
            /images/featured_hu328730d3d81b0f94c3c9c34ef2462253_99968_680x500_fill_q90_lanczos_smart1.jpg
          altText: Lightning bolt symbol on red background
          elementId: ''
          styles:
            self:
              borderRadius: x-large
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
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Microshades
        subtitle: ''
        text: >
          An R package for improving color accessibility and organization of
          complex data. 
        image:
          type: ImageBlock
          url: >-
            /images/featured_huedd9dfebf0fe41e7bd9b508ee542a504_262054_680x500_fill_q90_lanczos_center.jpg
          altText: Featured icon two
          elementId: ''
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
      - type: FeaturedItem
        title: Urinary Microbiome
        subtitle: Faster
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
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
    actions:
      - type: Button
        label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    badge:
      type: Badge
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
    elementId: ''
    variant: big-list
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
