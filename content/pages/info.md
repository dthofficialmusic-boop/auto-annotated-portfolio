---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: "# Our Mission\n\nCotidor was founded on a simple, powerful belief: extraordinary talent should be heard. In a digital age saturated with content, emerging artists often struggle to break through the noise. Cotidor exists as a dedicated platform to provide the strategic amplification and foundational support that turns potential into presence.\n\nWe are more than a service—we are a partner in the journey. Founded by Yllona Madison Ebanks, Cotidor was born from firsthand recognition of the gap between raw artistic brilliance and sustainable audience growth. Our mission is to bridge that gap, offering the tools, strategy, and advocacy that allow artists to focus on what they do best: creating.\n\n\n\n### Our Core Services\n\n#### 1. Strategic Promotion & Digital Amplification\n\nWe transform your music into a moving target that algorithms and audiences can’t ignore.\n\n*   Organic Growth from the Cotidor Hub:\_We leverage our curated platform and social channels to introduce our community to your sound, providing a stamp of discovery and credibility.\n\n*   Precision-Targeted Advertising:\_We design and execute sophisticated ad campaigns (Instagram, Meta, streaming platforms) that place your music in front of listeners most likely to become fans, based on detailed demographic and behavioral data.\n\n*   Cross-Platform Narrative Building:\_We ensure your release tells a compelling story across all digital touchpoints, creating a cohesive and engaging fan experience.\n\n#### 2. Artist Development & Career Roadmapping\n\nWe build the blueprint for your long-term journey, not just your next release.\n\n*   Strategic Content Planning:\_We collaborate with you to build a release calendar and content roadmap that aligns your artistic vision with market opportunities.\n\n*   Brand & Narrative Development:\_We help clarify and amplify your unique story, ensuring your visual identity and messaging are consistent, professional, and authentic.\n\n*   Goal-Oriented Strategy:\_We work with you to define milestones—from playlist placements to sync licensing goals—and create a actionable plan to achieve them.\n\n#### 3. Industry Liaison & Access\n\nWe open doors. Cotidor acts as your representative to the wider music ecosystem.\n\n*   Playlist Pitching:\_We utilize our network to pitch your music to independent and major streaming platform curators.\n\n*   Sync Licensing Advocacy:\_We identify and pitch your tracks for opportunities in film, television, and advertising.\n\n*   Partner Introductions:\_We facilitate connections with trusted producers, video directors, and booking agents to expand your creative and professional network.\n\n#### 4. Community Management & Fan Retention\n\nWe help you build and nurture your most valuable asset: your fanbase.\n\n*   Subscriber Strategy:\_We develop systems to convert listeners into subscribers and engaged community members through exclusive content and seamless onboarding.\n\n*   Fan Relationship Nurturing:\_We design communication flows to keep your audience engaged, informed, and invested in your evolution over time.\n\n*   Data-Driven Engagement:\_We analyze fan behavior to personalize interactions and maximize the lifetime value of your supporter base.\n\n\n\n### Why Cotidor?\n\nWe understand that an artist's journey is multidimensional. Success requires more than a one-time boost; it requires a holistic ecosystem of support. Cotidor integrates promotion, development, industry access, and community building into a single, synergistic framework.\n\nWe are selective in our partnerships, choosing to work deeply with artists whose work we genuinely believe in. This ensures our passion matches yours, and our strategic efforts are fueled by a shared commitment to your authentic growth.\n\n\n\n### Founder’s Vision\n\n*\"Cotidor was imagined from a place of shared frustration and unwavering optimism. I saw too many brilliant artists with the talent to captivate the world, but lacking the specific toolkit to navigate it. We are here to be that toolkit—to provide the strategic clarity, the impactful exposure, and the unwavering support that allows artists to rise. This isn't just about plays; it's about building legacies.\"*\n— Yllona Madison Ebanks, Founder\n\n\n\n### Get in Touch\n\nAre you an emerging artist ready to build momentum with a dedicated partner?\n\nLet’s build your audience, together.\n\n\n\n"
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**

          * freelance @freelance.me

          **2018-2021**

          * fullstack at this startup

          **2015**

          * senior front-end at this place

          **2013**

          * intern developer at a big company

          **2011**

          * flipping burgers
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        subtitle: Physical Offices
        text: >+
          **Main Office — for the world excluding the United States and Canada
          (Cayman)**


          *   40 Frank Sound Rd. North Side Grand Cayman




          **Satellite Office — servicing the Continental U.S. and Canada**


          *   5031 SW 199th Ave Southwest Ranches, Florida

        styles:
          self:
            textAlign: left
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: Let’s talk... 💬
    colors: colors-f
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
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
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
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
