---
type: PageLayout
title: Home
colors: colors-f
# Clean, minimal background
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      Hi, I'm Hieu Pham - a passionate software engineer and data enthusiast.
    subtitle: >-
      Welcome to my digital space! I'm a passionate software engineer and data enthusiast with a deep fascination for turning complex problems into elegant solutions. Based in Fort Worth, TX, I'm pursuing my B.S. in Data Science with minors in Mathematics at Texas Christian University, maintaining a 3.9 GPA. My journey in technology spans from full-stack development to advanced data science and machine learning. I'm driven by the intersection of code and data, where I can build robust systems that not only work efficiently but also provide meaningful insights. Explore my projects and let's connect to discuss how we can work together.
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
          - pb-16
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: center
    type: HeroSection
    actions:
      - type: Link
        label: '📄 Download CV'
        url: '/files/Hieu_Pham_CV.pdf'
        style: 'primary'
        elementId: 'cv-download-btn'
      - type: Link
        label: '🚀 View Projects'
        url: '/projects'
        style: 'secondary'
        elementId: 'projects-btn'
      - type: Link
        label: '📝 View Blogs'
        url: '/blog'
        style: 'secondary'
        elementId: 'blogs-btn'
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-one.md
      - content/pages/blog/dsa-guide.md
      - content/pages/blog/quantitative-analysis.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Let's work together!\U0001F4AC"
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
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
  - type: FeaturedItemsSection
    subtitle: 'Connect with me:'
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Button
            label: LinkedIn
            url: 'https://www.linkedin.com/in/hieu-pham-50a2ab136/'
            showIcon: true
            icon: linkedin
            iconPosition: left
            style: secondary
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        actions:
          - type: Button
            label: GitHub
            url: 'https://github.com/duchieu260503'
            showIcon: true
            icon: github
            iconPosition: left
            style: secondary
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        actions:
          - type: Button
            label: Instagram
            url: 'https://www.instagram.com/canquaca2605/'
            showIcon: true
            icon: instagram
            iconPosition: left
            style: secondary
        styles:
          self:
            textAlign: center
    columns: 3
    spacingX: 120
    spacingY: 16
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
---
