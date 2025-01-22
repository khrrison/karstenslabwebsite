---
type: PageLayout
title: Team
sections:
  - type: FeaturedPeopleSection
    title:
      type: TitleBlock
      text: Lab Members
      color: text-dark
      styles:
        self:
          textAlign: center
    people:
      - content/data/lisakarstens.json
      - content/data/keishaharrison.json
      - content/data/christina-turner.json
    actions: []
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
    subtitle: Current
  - type: FeaturedPeopleSection
    people:
      - content/data/katie-bowie.json
      - content/data/justine-nguyen.json
      - content/data/jeanphilippegourdine.json
      - content/data/erin-dahl.json
      - content/data/emory-neer.json
      - content/data/anagha-shenoy.json
      - content/data/alec-barstad.json
    actions: []
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
    subtitle: Alumni
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: Social Media Management
        tagline: Feature 1
        subtitle: Increase your reach
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Featured item
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
slug: team
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
