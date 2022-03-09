---
title: Home
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-a
    title: Reazzi
    subtitle: ''
    text: >
      Reazzi is here to make your mortgage woes disappear. We want to help you
      buy a house in a day. Buying your first home? Real eazy. Refinancing? Real
      eazy. Investing? Real Eazy.


      Real quick. Real Eazi. Reazzi.
    actions: []
    media:
      type: ImageBlock
      url: /images/brandmark-design-1800x0.png
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
    type: HeroSection
  - colors: colors-e
    elementId: ''
    title: How Will Reazzi Help?
    items:
      - type: FeaturedItem
        title: 'Transparency '
        text: >
          We've searched far and wide to find **every** available home loan so
          you don't have to! **Reazzi** will always allow you to search every
          product available.
        featuredImage:
          type: ImageBlock
          url: /images/icons8-analytics-64.png
          altText: Item image
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        title: Ease
        text: >
          Regardless of where you are in the process, we're here to help take
          you forward and get the perfect home loan for your situation.
        featuredImage:
          type: ImageBlock
          url: /images/smarter.svg
          altText: Item image
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        title: Speed
        text: >
          Bringing home loans into the 21st century, **Reazzi's Smart Apply**
          engine will expedite your application allowing you to spend more time
          finding your perfect home and less time dealing with the banks.
        featuredImage:
          type: ImageBlock
          url: /images/focused.svg
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
    subtitle: 'Real Quick. Real Eazy. '
  - elementId: ''
    variant: variant-b
    colors: colors-a
    title: The Team
    subtitle: Meet the people behind Reazzi
    actions: []
    people:
      - content/data/team/person-a7lh066i5.json
      - content/data/team/person-0qzu1knj1.json
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
    type: FeaturedPeopleSection
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
    media: null
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
