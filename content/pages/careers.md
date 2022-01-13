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
    colors: colors-h
    quote: |
      ## 2447 Niagara Falls Blvd

      ## Buffalo, NY 14228

      ## United States
    name: (716) 691-5806
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
          - pt-24
          - pb-36
        justifyContent: center
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
    type: QuoteSection
  - elementId: ''
    colors: colors-a
    images:
      - type: ImageBlock
        url: /images/Logo Complementario.png
        altText: People in the meeting room
      - type: ImageBlock
        altText: People in the meeting room
    spacing: 3
    columns: 2
    aspectRatio: '1:1'
    imageSizePx: 400
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
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
    type: MediaGallerySection
  - colors: colors-a
    elementId: ''
    title: Open Hours
    jobLists:
      - type: JobList
        items:
          - type: JobListItem
            text: |
              ##### Mon:11:00 AM – 9:00 PM

              ##### Tue:11:00 AM – 9:00 PM

              ##### Wed:11:00 AM – 9:00 PM

              ##### Thu:11:00 AM – 9:00 PM

              ##### Fri:11:00 AM – 9:00 PM

              ##### Sat:11:30 AM – 9:00 PM

              ##### Sun:12:00 – 8:00 PM
            actions: []
      - type: JobList
        title: MAP
        items:
          - type: JobListItem
            text: >
              ![](/images/Captura%20de%20pantalla%20de%202022-01-13%2008-52-56.png)


              ### 2447 Niagara Falls Blvd


              ### Buffalo, NY 14228


              ### United States
            actions: []
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
          - pt-32
          - pb-60
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: center
    type: JobsSection
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
