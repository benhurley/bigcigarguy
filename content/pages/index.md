---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Crafted For The Modern Cigar Buff
      color: text-dark
      type: TitleBlock
    subtitle: Est. 2018
    text: >
      For those that love blasting a smooth ‘gar on the weekends, or enjoying a
      cold one after a day filled with corporate wins.
    actions:
      - type: Button
        label: Visit Our Shop
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
      label: Big CIGAR GUY (BCG)
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
    colors: bg-neutral-fg-dark
    type: GenericSection
seo:
  metaTitle: Home | Big Cigar Guy
  metaDescription: A Lifestyle Brand Crafted For The Modern Cigar Buff
  socialImage: /images/Testimonial.JPG
  type: Seo
  addTitleSuffix: false
  metaTags: []
type: PageLayout
---
