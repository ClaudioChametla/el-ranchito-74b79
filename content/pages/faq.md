---
title: FAQ
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-a
    backgroundSize: full
    title: From Our Family To Yours
    subtitle: ''
    badge:
      label: El ranchito 3
      elementId: ''
      styles:
        self:
          textAlign: left
    text: >
      El Ranchito Mexican Restaurant is proud to be a part of your neighborthood
      since 2012.


      We enjoy providing quality and beverages, warm friendly service and good
      value for you and your family.
    actions:
      - type: Button
        label: Order Now
        url: /
        style: primary
    media:
      type: ImageBlock
      url: /images/MASCOTA Y COMPLEMENTO.png
      altText: Hero image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeatureHighlightSection
  - elementId: ''
    colors: colors-a
    title: Check our contact info
    subtitle: ''
    text: |
      ###### 2447 Niagara Falls Blvd. Buffalo, NY 14228, United States
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
    type: TextSection
  - elementId: ''
    colors: colors-h
    backgroundSize: full
    title: Contact us
    text: We look forward to hearing from you.
    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: 'true'
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: 'true'
          width: 1/2
        - name: Message
          label: Write Us
          hideLabel: false
          placeholder: Your Message
          isRequired: false
          width: full
          type: TextareaFormControl
      submitLabel: Send Message
    media:
      type: ImageBlock
      url: /images/LOGO COMPLETO.png
      altText: Contact form image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
    type: ContactSection
---
