---
title: About
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-e
    styles:
      self:
        width: wide
        padding:
          - pt-0
          - pb-4
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedPeopleSection
    colors: colors-d
    elementId: ''
    variant: variant-c
    title: About us
    subtitle: Featured people section example
    actions: []
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/hilary-ouse.json
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
      actions:
        justifyContent: center
  - type: TextSection
    colors: colors-d
    variant: variant-a
    title: About me
    text: >
      I am a data-driven nerd that hopes to explore and work on projects that
      involve utilizing data to make informed decisions. Currently a graduating
      senior who hopes to gain more experiences in various fields/industries in
      the coming future. I have a Bachelor of Science in Economics and I've
      grown interested in coding and machine learning as well.


      I firmly believe that data has the power to tell epic stories and provide
      insight to better our individual lives and shape tomorrow's society.


      <https://www.linkedin.com/in/dchen564/>


      <https://github.com/Wisequacker>


      ![](/images/gasworksparkdanny-6431cedd.png)
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-32
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - elementId: ''
    colors: colors-e
    quote: |+
      ```
      “No data is clean, but most is useful”


      ```

    backgroundImage:
      type: BackgroundImage
      url: /images/chris-liverani-dBI_My696Rk-unsplash.jpg
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 70
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
          - pt-96
          - pb-10
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: left
      name:
        fontWeight: '400'
        fontStyle: normal
        textAlign: left
      title:
        fontWeight: '400'
        fontStyle: normal
        textAlign: left
    type: QuoteSection
    name: '-Dean Abott'
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
---
