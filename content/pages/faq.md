---
title: FAQ
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-a
    backgroundSize: full
    title: 'A great feature, we’re proud of'
    subtitle: ''
    badge:
      label: This is the badge
      elementId: ''
      styles:
        self:
          textAlign: left
    text: >-
      Share WIP, comment on each other’s work, approve what’s ready to go, ship
      together
    actions:
      - type: Button
        label: Sign Up
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
    title: Contact Us
    subtitle: ''
    text: >
      ### Lorem ipsum dolor sit amet, consectetur adipiscing elit, sedolorm
      reminusto&#xA;doeiusmod tempor condorico consectetur adipiscing elitut
      aliquip.
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
        - type: TextFormControl
          name: address
          label: Home address
          placeholder: Your home address
          isRequired: 'false'
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          isRequired: 'false'
          width: full
      submitLabel: Send Message
    media:
      type: ImageBlock
      url: /images/careers.jpg
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
