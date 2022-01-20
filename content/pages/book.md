---
title: Careers
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-h
    title: El Ranchito 3
    subtitle: MEXICAN RESTAURANT
    media:
      type: ImageBlock
      url: /images/1.jpg
      altText: Hero section image
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
          - pt-36
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-a
    backgroundSize: full
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        url: /
        style: primary
    backgroundImage: null
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
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: CtaSection
  - elementId: contact-form
    colors: colors-f
    backgroundSize: inset
    title: Contact us
    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: first-name
          label: Your first name
          hideLabel: true
          placeholder: First name
          isRequired: false
          width: 1/2
        - type: TextFormControl
          name: last-name
          label: Your last name
          hideLabel: true
          placeholder: Last name
          isRequired: false
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Your email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
        - type: TextFormControl
          name: address
          label: Your address
          hideLabel: true
          placeholder: Address
          isRequired: false
          width: full
      submitLabel: Submit
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: center
      text:
        textAlign: center
    type: ContactSection
---
