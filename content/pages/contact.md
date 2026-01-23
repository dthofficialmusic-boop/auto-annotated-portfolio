---
type: PageLayout
title: contact
sections:
  - type: HeroSection
    title: MeDIUMS OF CONTACT
    subtitle: You may contact us via email
    text: |+
      **General Inquiries**

      <info@cotidor.com>

      **Artist Management & Recruitment**

      <artists@cotidor.com>

      **Administration & Internal Affairs**

      <admin@cotidor.com>

    actions: []
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
  - type: ContactSection
    title: SUPPORT TICKET FORM
    text: ''
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          width: 1/2
          isRequired: false
        - type: TextFormControl
          name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          width: 1/2
          isRequired: false
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Email
          width: full
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell us about your inquiry...
          width: full
          isRequired: true
      submitLabel: Submit 🚀
      elementId: sign-up-form
      styles:
        self:
          textAlign: center
    colors: colors-b
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
