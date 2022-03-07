---
title: Home
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-a
    title: Love where you work
    subtitle: ''
    badge:
      label: This is the badge
      elementId: ''
      styles:
        self:
          textAlign: left
    text: >-
      One platform, one community, getting to the bottom line of everything
      employment.  Figure out your benefits, practice for interviews, get
      mentored, help peers, get helped in return.
    actions:
      - type: Button
        label: Sign Up
        url: /
        style: primary
    media:
      type: ImageBlock
      url: /images/hero.png
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
  - colors: colors-c
    elementId: ''
    title: How Will Reazzi Help
    items:
      - type: FeaturedItem
        title: Faster
        text: >-
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          type: ImageBlock
          url: /images/faster.svg
          altText: Item image
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        title: Smarter
        text: >-
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          type: ImageBlock
          url: /images/smarter.svg
          altText: Item image
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        title: Focused
        text: >-
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          type: ImageBlock
          url: /images/focused.svg
          altText: Item image
        styles:
          self:
            textAlign: center
    actions: []
    columns: 3
    enableHover: true
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
    subtitle: Bringing finances
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
