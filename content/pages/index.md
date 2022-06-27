---
title: Home
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-e
    styles:
      self:
        width: wide
        padding:
          - pt-0
          - pb-6
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: HeroSection
    colors: colors-a
    elementId: ''
    backgroundSize: full
    title: Welcome to my digital portfolio site!
    subtitle: Dedicated. Strategic. Mindful.
    actions:
      - type: Button
        label: View Projects
        showIcon: true
        icon: arrowRight
        style: primary
        url: 'https://energetic-sun-b54e6.stackbit.app/blog/'
        altText: View Projects
      - type: Link
        altText: linkedin
        url: 'https://www.linkedin.com/in/dchen564/'
        showIcon: true
        icon: linkedin
        iconPosition: right
        elementId: ''
      - type: Link
        altText: github
        url: 'https://github.com/Wisequacker'
        showIcon: true
        icon: github
        iconPosition: right
        elementId: ''
      - type: Link
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      altText: Hero image
      url: /images/IMG_20190122_154312_932.jpg
    backgroundImage: null
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
        borderColor: border-primary
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedPostsSection
    colors: colors-c
    elementId: ''
    showDate: true
    showAuthor: false
    showExcerpt: true
    showReadMoreLink: true
    readMoreLinkLabel: Read more
    variant: variant-a
    actions:
      - type: Link
        label: View all projects
        altText: See all adventures
        url: /blog
        showIcon: true
        icon: arrowRight
    styles:
      self:
        height: auto
        width: wide
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
        justifyContent: flex-start
    title: Recent Projects
    subtitle: ''
    posts:
      - content/pages/blog/post-five.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-two.md
  - type: QuoteSection
    colors: colors-e
    quote: >+
      “The greatest value of a picture is when it forces us to notice what we
      never expected to see.”


    name: John Tukey
    title: American Mathematical Statistician
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pr-4
          - pl-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
metaTags: []
---
