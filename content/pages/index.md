---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: inset
    title: >-
      Welcome to the official website of British tuba, organist and singer
      Ramon.
    subtitle: '                                                   '
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
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
    text: >+
      ###### Lovely tuba player that not only has the technical ability but very
      musical too. -

  - type: MediaGallerySection
    title: ''
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/IMGL2034.jpg
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: /images/IMGL2155.jpg
        altText: Image three
        caption: Image three caption
        elementId: ''
      - type: ImageBlock
        url: /images/IMGL2144.jpg
        altText: Image two
        caption: Image two caption
        elementId: ''
      - type: ImageBlock
        url: /images/2023ARB__MG_4741.jpg
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 2
    aspectRatio: '1:1'
    showCaption: false
    enableHover: false
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        textAlign: center
  - type: TextSection
    title: About
    text: >+
      ##### Ramon Branch Biescas was born in Tarragona, Spain in 2001. He began
      his musical journey at a young age, attending the choir school Escolania
      de Montserrat in Catalonia, where he received most of his early musical
      training. During his time there, he studied piano with Vicenç Prunés for
      four years and organ with Merce Sanchís for three years. As part of the
      choir, he performed in countries including Russia, France, the United
      States, Poland, Germany, China, and many regions across Catalonia.


      ##### Later, he moved to the United Kingdom to continue both his academic
      and musical education at Lancing College, where he studied organ with Neil
      Cox and piano with Adrian West. At the age of fourteen, he began learning
      the tuba with Dave Whitson and, a year later, was accepted into the Junior
      Royal Academy of Music to study with Stephen Wick. Following his GCSEs,
      Ramon attended the Purcell School for Young Musicians, where he continued
      to grow as a tuba player while maintaining his skills on other
      instruments. During this time, he gained a wide range of performance
      experience and developed as a well-rounded musician. He achieved high
      distinction in all his Grade 8 ABRSM exams and is now working towards his
      diplomas in singing and organ.


      ##### Ramon has performed with a variety of orchestras including the
      London Symphony Orchestra, London Lawyers Symphony Orchestra, Fidelio
      Symphony Orchestra, Junior Academy Symphony Orchestra, Purcell School
      Symphony Orchestra, Jove Orquestra Nacional de Catalunya, and the
      Guildhall Symphony Orchestra. He is currently studying with Ben Thomson,
      Principal Tuba of the London Symphony Orchestra, and Kevin Morgan,
      Principal Tuba of the Royal Philharmonic Orchestra.


      ##### Alongside his tuba studies, Ramon continues to nurture his other
      musical talents. He is receiving second-study singing lessons with Adrian
      Thompson, sings as a choral scholar at St Mary’s Hendon, and regularly
      plays the organ at churches across London. He is also an active chamber
      musician, performing with the Heron Brass Quintet, who recently reached
      the semifinal round of the Royal Over-Seas League Competition.


      ##### Having finished his master’s studies, Ramon is now looking forward
      to working as a freelance musician and offering private music teaching

    colors: colors-f
    variant: variant-a
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        textAlign: left
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-c
    subtitle: Concerts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Contact
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
      submitLabel: "Submit \U0001F680"
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
    media:
      type: ImageBlock
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
---
