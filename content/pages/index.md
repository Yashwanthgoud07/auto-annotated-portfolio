---
type: PageLayout
title: Home
colors: colors-e
backgroundImage:
  type: BackgroundImage
  url: /images/gallery-1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: inset
    title: YASHWANTH GOUD BOMMAGOUNI
    subtitle: ' Welcome to My Portfolio! I’m thrilled to share my journey and showcase my work through this portfolio. Here, you''ll find a collection of projects that highlight my skills and creativity, as well as details about my work experiences and certifications that have shaped my professional path.'
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
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: right
        textDecoration: underline
        fontStyle: italic
        fontWeight: 500
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    media:
      type: ImageBlock
      url: /images/1714048266498.jpg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: LabelsSection
    title: Skills
    subtitle: The section subtitle
    items:
      - type: Label
        label: 'CYBERSECURITY FOUNDATIONS '
        url: ''
      - type: Label
        label: ''
        url: ''
      - type: Label
        label: ORACLE CLOUD INFRASTRUCTURE
        url: ''
      - type: Label
        label: SQL
        url: ''
      - type: Label
        label: PYTHON
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
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
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: MediaGallerySection
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: logo one
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo2.svg
        altText: logo two
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo3.svg
        altText: logo three
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo4.svg
        altText: logo four
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo5.svg
        altText: logo five
        caption: Caption of the image
        elementId: ''
    colors: colors-a
    spacing: 16
    columns: 5
    aspectRatio: '16:9'
    showCaption: true
    enableHover: false
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
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
  - type: QuoteSection
    quote: |
      "LET CONSISTENCY BE YOUR SUPERPOWER"

      ![](/images/images.jpg)
    name: YASHWANTH GOUD BOMMAGOUNI
    title: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        fontWeight": 500
        textAlign: center
      title:
        fontWeight": 400
        textAlign: center
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: 'INTERESTED TO WORK WITH ME '
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
      submitLabel: 'Submit '
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
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
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
