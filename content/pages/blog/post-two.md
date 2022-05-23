---
title: Teamfight Tactics Analyzer
layout: PostLayout
author: content/data/team/desmond-eagle.json
excerpt: >-
  A Teamfight Tactics competitive match data analyzer on player's team
  composition choices.
featuredImage:
  type: ImageBlock
  url: /images/tft galaxy midset.jpg
  altText: Post Image
bottomSections:
  - elementId: ''
    variant: variant-d
    colors: colors-d
    title: Other Projects
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 3
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
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: RecentPostsSection
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
media:
  type: ImageBlock
  url: /images/TFT set3.5.png
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
date: '2020-03-28'
---
Teamfight Tactics (TFT) is a strategic autobattler game under owned by riot games. Autobattler as a game genre has been around since 2019 with the first competitive addition of Dota Autochess, a in game client mod. I loved the idea of crafting a team of units and letting them fight in a simulation battle as you manipulate their positioning to skew the simulation and have a strategic plan. The deployable characters in this game aren’t all equal in strength and their synergies with units of the same class/origin are also not always equally matched throughout the course of a 20-to-40-minute match.


Since TFT was still a relatively new game that patches quite frequently and there wasn’t a way to see the meta game. To better analyze the top comps that people were playing I wanted to examine the match data utilizing data analysis to understand the trends of team compositions. This form of information would be helpful to pushing the information to a public as biweekly game patches alter the meta a bit, but rarely destroy existing compositions in the meta.


The following project utilized switch case with dictionaries because the json format pulled for Riot’s API are key value pairs. It helped us parse through the data and attempt to classify the main compositions that have been played by big professional streamers of the game. Having digestable data is a big part of figuring out how the developers attempt to balance their games. As a consumer of the game, it is also possible to get a glimpse of whether or not claims about strong teams being actually strong and consistently placing top of the lobbies. We attempted to do the analyzing and then realized there might be more nuances besides the comps themselves because individuals can choose to slot out from the standard comp specific needs and play more flexible tech units given the game state or versus specific matchups.


This project was done in conjunction of mostly peer coding and my partner came up with the GUI addition to the project to allow for quick collection of analysis. I think having visualizing tools made this project very helpful if we ever decide to go back and try revitalize the project. We realized a lot of compositions weren’t being registered, so there might be more efficient ways to identify compositions more broadly. This is a project I might want to revisit in the future to see what other analysis because there are now more match augments and the Riot API provide more player data that’s friendly to developers and those wanting to work with their match data.
