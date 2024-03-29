---
title: Home
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-a
    title: Reazzi
    subtitle: Real Quick. Real Eazy.
    text: >
      **Reazzi** paves the way to make your finances a cinch! Regardless of your
      experience or knowledge we’ll guide you to success. Whether you are a
      first home buyer uncertain on the home ownership journey or a seasoned
      investor looking to refinance your portfolio.


      With our **smart apply** engine you can apply for any loan, from
      everywhere, so you can spend less time worrying about finances and more
      time finding your dream home.


      Every step is **Reazzi**…*that is Real Quick, and Real Eazy.*
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
        title: For You
        text: >
          We've searched far and wide to find **every** available home loan so
          you don't have to! **Reazzi** will always allow you to search every
          product available.
        featuredImage:
          type: ImageBlock
          url: /images/15984328721530513410-128.png
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
          url: /images/16235136021643432432-128.png
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
          url: /images/noun-snap-1984955-227f4f4d.png
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
    subtitle: Real Quick. Real Eazy. Reazzi
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
    colors: colors-f
    backgroundSize: full
    title: Contact us
    text: We look forward to hearing from you.
    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: hello@reazzi.com
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: address
          label: Message
          placeholder: Your message
          isRequired: true
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
