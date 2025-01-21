---
type: PageLayout
title: contact
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Contact
      color: text-dark
    subtitle: 'OHSU, Portland, OR 97239, USA'
    text: >+
      ```

      <!DOCTYPE html><html lang="en"><head><meta charset="UTF-8" /><title>OHSU
      Map</title></head><body><h1>OHSU
      Location</h1><iframewidth="600"height="450"style="border:0;"loading="lazy"allowfullscreenreferrerpolicy="no-referrer-when-downgrade"src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2795.2953911273656!2d-122.68832838447925!3d45.4996266791019!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x54950a03a2a1620f%3A0x1ab459d88243a974!2sOregon%20Health%20%26%20Science%20University!5e0!3m2!1sen!2sus!4v1642450983339!5m2!1sen!2sus"
        ></iframe></body></html>
      ```


      ###



    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
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
    badge:
      type: Badge
      label: Connect with us
      color: text-primary
    colors: bg-light-fg-dark
slug: contact
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
