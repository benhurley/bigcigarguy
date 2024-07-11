---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: A Lifestyle Brand for the Modern-Day Cigar Enthusiast.
      color: text-dark
      type: TitleBlock
    subtitle: Since 2018
    text: >
      For those that love blasting a smooth ‘gar on the weekends, or enjoying a
      cold one after a day filled with corporate wins.
    actions:
      - type: Button
        label: Shop
        altText: ''
        url: 'http://bonfire.com/store/bigcigarguy'
        showIcon: true
        icon: shoppingBag
        iconPosition: left
        style: primary
        elementId: ''
    media:
      url: /images/Testimonial.JPG
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Big CIGAR GUY
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
  - type: FeaturedItemsSection
    title:
      text: About Us
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Our Start
        subtitle: ''
        text: >
          A few of us wanted a funny shirt to rock while lighting one up... then
          we sold a hundred of them.


          Today, our family-run organization continues to obsess over designing
          light-hearted, high-quality clothing at the lowest prices possible.
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
          url: /images/gard.jpg
          styles:
            self:
              borderRadius: x-large
      - title: Merch
        subtitle: ''
        text: >
          We typically drop new items 1-2 times a year, using our quick feedback
          loop to drive our next designs.


          Let us know what you want to rock and we might just bring it to life!
        image:
          url: /images/IMG_2438.JPG
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
      - title: Who's BCG?
        subtitle: ''
        text: |


          There is a Big Cigar Guy within all of us.

          To be fair, there might have been some inspiration for our logo...
        image:
          url: /images/Screen Shot 2019-05-28 at 11.30.02 PM.png
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
    actions: []
    badge:
      label: ''
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
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: false
    variant: two-col-grid
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
      text: Testimonials
      color: text-dark
    showExcerpt: true
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
      text: Drop us a Line
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: ''
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
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
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Featured Items
      color: text-dark
      styles:
        self:
          textAlign: left
    items:
      - type: FeaturedItem
        title: Hacker Sleeve
        subtitle: $10.49
        image:
          type: ImageBlock
          url: /images/koozie.jpg
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
            textAlign: left
            borderRadius: none
            flexDirection: col
            justifyContent: center
      - type: FeaturedItem
        title: gar'd
        subtitle: $23.50
        image:
          type: ImageBlock
          url: /images/Don.jpg
          altText: Cotton Knit Throws
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Cool Down
        subtitle: $117
        image:
          type: ImageBlock
          url: /images/IMG_4979.JPG
          altText: Chunky Cotton Knit Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-8
          - pr-8
        justifyContent: flex-start
      subtitle:
        textAlign: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
