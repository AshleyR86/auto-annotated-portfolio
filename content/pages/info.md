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
    text: >+
      ## Welcome to Ashley 2.0 – Your Virtual Assistant!


      This page will guide you on how to use the site to get the most out of
      your virtual assistant. Whether you need help with assignments, feedback
      on your work, or just a quick chat to clarify a concept, Ashley 2.0 is
      here for you!




      1\. **Ask a Question**


      Need help with a topic or have a quick question? You can use the **Ask a
      Question** feature to type your questions directly into the chat, and I’ll
      provide guidance as quickly as possible.


      **How to ask a question**:


      1.  Go to the “Ask a Question” section on the home page.


      2.  Type your question in the text box.


      3.  Hit **Submit** and wait for a response. I’ll provide an answer or
      direct you to the best resources to help.




      2\. **Upload Your Work**


      Have some working out or an assignment you’d like reviewed? Upload it
      directly to the site, and I’ll give you feedback.


      **How to upload your work**:


      1.  Navigate to the “Upload Work” section.


      2.  Click the **Upload** button and select the image or file you want to
      submit.


      3.  Once uploaded, I’ll review it and provide feedback or suggest ways to
      improve.


      Supported file formats: PDF, JPEG, PNG.




      3\. **Live Chat**


      Need to discuss something in real-time? You can chat live with me. Whether
      you’re stuck on a concept or need quick clarification, I’m just a message
      away.


      **How to start a live chat**:


      1.  Click on the **Live Chat** button at the top of the page.


      2.  A chat window will open where you can type your questions and receive
      answers in real-time.


      3.  You’ll receive instant help, and if I don’t know the answer right
      away, I’ll guide you to the right resources.



    media:
      type: ImageBlock
      url: /images/about.jpg
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
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
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: 'I worked with these folks:'
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/logo2.svg
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/logo3.svg
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/logo4.svg
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/logo5.svg
        altText: Logo five
        caption: Logo five
    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Twitter
            url: 'https://twitter.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: CodePen
            url: 'https://codepen.io/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Discord
            url: 'https://discord.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Instagram
            url: 'https://www.instagram.com/'
        styles:
          self:
            textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: 'You can find me here:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'WEB 1, 2, 3'
      - type: Label
        label: React
      - type: Label
        label: Microsoft Office
      - type: Label
        label: Next.js
      - type: Label
        label: Netlify
      - type: Label
        label: Pancakes
      - type: Label
        label: C++
      - type: Label
        label: Swift
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [thisismyemail.@myemail.me](mailto:thisismyemail.@myemail.me)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
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
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **2015-2018**

          * ba computer sciense at a semi fancy school

          **2014**

          * react certificate somewhere

          **2011**

          * my highschool
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
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
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
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
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
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
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
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
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
