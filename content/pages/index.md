---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-a
    title: El Ranchito 3 Mexican Restaurant
    actions:
      - type: Button
        label: Order Now
        url: 'https://www.stackbit.com/'
        style: primary
    media:
      type: ImageBlock
      url: /images/2.jpg
      altText: Image alt text
      caption: Image caption
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
          - pb-28
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - elementId: ''
    colors: colors-f
    backgroundSize: inset
    title: Best dish of the day
    text: |
      ###### Speedy Gonzales, Taco, enchilada, Rice or Beans.

      ## $8.99
    badge:
      type: Badge
      styles:
        self:
          textAlign: left
    actions:
      - type: Button
        label: Order Now
        url: /
        style: primary
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-16
          - pb-16
          - pl-16
          - pr-16
        justifyContent: center
        flexDirection: row
        alignItems: center
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeatureHighlightSection
    media:
      url: /images/1.jpg
      altText: Where did everyone go?
      caption: Team meeting
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
  - colors: colors-h
    subtitle: Order by
    elementId: ''
    images:
      - type: ImageBlock
        altText: Apple
        caption: Apple
      - type: ImageBlock
        altText: Google Play
        caption: Google Play
      - type: ImageBlock
        url: /images/ChowNow_Company_Logo_Transparent.png
        altText: PlayStation
        caption: PlayStation
      - type: ImageBlock
        altText: Gatsby
        caption: Gatsby
      - type: ImageBlock
        url: /images/DoorDash-Logo.png
        altText: Xbox
        caption: Xbox
      - type: ImageBlock
        altText: Skype
        caption: Skype
      - type: ImageBlock
        altText: ZCOOL
        caption: ZCOOL
    spacing: 3
    columns: 7
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
    imageSizePx: 240
    type: MediaGallerySection
  - colors: colors-a
    elementId: ''
    title: Mexican Drinks
    subtitle: These are some mexican drinks
    items:
      - type: FeaturedItem
        title: Mexican Beer
        text: |
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
        featuredImage:
          url: /images/beer.JPG
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Margarona
        text: |
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        featuredImage:
          url: /images/Captura de pantalla de 2022-01-07 08-51-00.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Especial Drinks
        text: |
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        featuredImage:
          url: /images/Captura de pantalla de 2022-01-07 08-51-18.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
    columns: 3
    enableHover: false
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
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - elementId: ''
    colors: colors-a
    variant: variant-a
    testimonials:
      - quote: >-
          “It’s great to see someone taking action while still maintaining a
          sustainable fish supply to home cooks.”
        name: Johnna Doe
        title: Product Marketing Manager at Acme
        image:
          url: >-
            https://assets.stackbit.com/components/images/default/default-person.png
          altText: Person photo
        elementId: ''
        styles:
          name:
            fontWeight: 400
            fontStyle: normal
          title:
            fontWeight: 400
            fontStyle: normal
      - quote: |
          They Say About Us
        name: Carla Rogers
        title: Nice Restaurant
        image:
          type: ImageBlock
          url: /images/carla.jpg
          altText: Photo of Carla Rogers
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-28
          - pb-56
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
    type: TestimonialsSection
---
