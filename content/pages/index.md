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
  - colors: colors-a
    elementId: ''
    title: Popular Dishes
    subtitle: There are some mexican dishes
    items:
      - type: FeaturedItem
        title: Tacos
        text: >
          All tacos come three, per order. Served with rice, beans, onions,
          cilantro and salsa


          *Tacos chihuahua*


          *$ 14.99*
        featuredImage:
          url: /images/Captura de pantalla de 2022-01-12 10-39-02.png
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
        title: Enchiladas
        text: >
          Enchiladas Supreme


          *Four enchiladas: 1 beef, 1 chicken, 1 cheese and 1 bean; covered wth
          enchilada sauce topped with lettuce, tomatoes and spur cream.*


          *$ 13.99*
        featuredImage:
          url: /images/Captura de pantalla de 2022-01-12 10-40-00.png
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
        title: Nachos & dips
        text: |
          All Nachos are served with pur famous queso sauce

          *Nachos Supreme*

          *$ 12.99*
        featuredImage:
          url: /images/Captura de pantalla de 2022-01-12 10-40-29.png
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
  - colors: colors-h
    elementId: ''
    items:
      - type: FeaturedItem
        title: Fresh Ingredients
        text: |
          Sed egestas, ante vulputa eros pede vitae luctus metus augue.
        featuredImage:
          type: ImageBlock
          url: /images/ingredients.png
          altText: Item image
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        title: Best Recipe
        text: |
          Sed egestas, ante vulputa eros pede vitae luctus metus augue.
        featuredImage:
          type: ImageBlock
          url: /images/cook-book.png
          altText: Item image
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        title: Happy Clients
        text: |
          Sed egestas, ante vulputa eros pede vitae luctus metus augue.
        featuredImage:
          type: ImageBlock
          url: /images/rating.png
          altText: Item image
        styles:
          self:
            textAlign: center
    actions: []
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedItemsSection
  - elementId: ''
    colors: colors-a
    backgroundSize: full
    title: Steak Plates
    subtitle: ''
    badge:
      elementId: ''
      styles:
        self:
          textAlign: left
    text: >
      1.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-28-26.png)
      Bistek Santa Fe . . . . . $ 24.00


      2. 
      ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-28-26-f8b270c1.png)
      House Special . . . . . . $ 24.00


      3. 
      ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-28-26.png)El
      ranchero . . . . . . . . . . $ 24.00


      4. 
      ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-28-26.png)Bistec
      a la Tampique??a . . .$ 24.00


      5.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-28-26.png)
      El Poblano . . . . . . . . . . . . $ 24.00
    actions: []
    media:
      type: ImageBlock
      url: /images/Captura de pantalla de 2022-01-12 11-12-51.png
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
        flexDirection: row
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
    backgroundSize: full
    title: Chicken Plates
    subtitle: ''
    badge:
      elementId: ''
      styles:
        self:
          textAlign: left
    text: >
      1.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png)
      Arroz Con Pollo . . . . . . . $ 13.90


      2.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png)
      El Pollo Loco . . . . . . . . . . $ 14.50


      3.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png)
      El pollo a la Diabla . . . . .  $ 14.50


      4. 
      ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png)Chori
      Pollo . . . . . . . . . . . . . $ 15.50


      5.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png)
      El pollo norte??o . . . . . . . . $ 18.50
    actions: []
    media:
      type: ImageBlock
      url: /images/Captura de pantalla de 2022-01-12 11-12-51.png
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
    backgroundSize: full
    title: Seafood Plates
    subtitle: ''
    badge:
      elementId: ''
      styles:
        self:
          textAlign: left
    text: >
      1.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png)
      Camarones al chipotle . . . . . .  $ 16.99


      2.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png)
      Camarones al Mojo de Ajo . . . $ 16.99


      3.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png)
      Coctel de camar??n . . . . . . . . . . $ 16.99


      4.  ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png) 
      Camarones a la Diabla . . . . . .  $ 16.99


      5. 
      ![](/images/Captura%20de%20pantalla%20de%202022-01-12%2021-32-18.png)Shrimp
      Chimochanga . . . . . . . . $16.99
    actions: []
    media:
      type: ImageBlock
      url: /images/Captura de pantalla de 2022-01-12 11-12-51.png
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
        flexDirection: row
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
    variant: variant-a
    testimonials:
      - quote: |
          ???I love the food of this restaurant???
        name: Johnna Doe
        title: Client
        image:
          url: /images/client.png
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
          "This is the best mexican restaurant"
        name: Carla Rogers
        title: Client
        image:
          type: ImageBlock
          url: /images/client.png
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
