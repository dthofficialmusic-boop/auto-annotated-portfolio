---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg3.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    colors: colors-a
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: center
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: COTIDOR—A MODERN TAKE on music
    subtitle: >-
      WE ARE AN ARTIST DEVELOPMENT COLLECTIVE AIMING TO EMPOWER, GUIDE, AND
      TRANSFORM ARTISTS—ON THEIR OWN TERMS.
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
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: center
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: WHAT WE DO
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: WANT TO BE A COTIDOR ARTIST? TELL US...
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit 🚀
      styles:
        self:
          textAlign: center
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
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
  - type: FeaturedItemsSection
    title: Contact
    items:
      - type: FeaturedItem
        title: EMAIL(S)
        subtitle: ''
        text: |+
          **General Inquiries**


          <info@cotidor.com>



          **Artist Management & Recruitment**


          <artists@cotidor.com>



          **Strategic Partnerships & Brand Collaborations**


          <partners@cotidor.com>

        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: OFFICE(S)
        subtitle: ''
        text: >+
          **Main Office — for the world excluding the United States and
          Canada** 


          *   40 Frank Sound Rd. North Side Grand Cayman


          **Satellite Office — servicing the Continental U.S. and Canada**


          *   5031 SW 199th Ave Southwest Ranches, Florida






        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-d
    columns: 2
    spacingX: 16
    spacingY: 16
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        textAlign: left
socialImage: /images/IMG_5663.png
---
