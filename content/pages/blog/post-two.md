---
title: Teamfight Tactics Analyzer
layout: PostLayout
author: content/data/team/desmond-eagle.json
excerpt: >-
  A Teamfight Tactics competitive match data analyzer on player's team
  composition choices.
featuredImage:
  - elementId: 'guitar'
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
date: '2020-07-14'
---
Esports have gained popularity with a lot of online games have competitive quirks with multiple players. This project was initiated because as a competitive gamer myself I wanted to hone the in-game strategies of Teamfight Tactics (TFT) (https://teamfighttactics.leagueoflegends.com/en-us/set-overview/teamfight-tactics-galaxies/) in a time efficient manner. Similar to sport strategies, competitive Esport games like TFT have viable strategies that evolve throughout the game’s life. The game is currently saturated by claims made by professional players with little to no data backing such claims.


A TFT match has 8 players that are playing against each other for placement and the general rule of thumb is getting top 4 is considered a win—these individuals are rewarded with rank rating. The goal of the game is to create a team of units and to live as long as possible. The units in this game have traits which unlocks special perks when they are teamed up with other units of the same trait. Within each match, the players are to build a team composition following varying builds to develop their end game strategy. For the purpose of this project, we hoped to find the top placing end game strategies in terms of team compositions utilized to gain rank rating.


We utilized data collected from the Riot Games API which provides information on players and their competitive match history. It allowed for us to analyze the top players and the placements of their games based on their end game strategies.


I personally felt like analyzing the team compositions strategies of top players in their recent games was a good indicator of a composition’s strength. Despite TFT having more random nuances that influences a game, understanding the strategy can get any player quite far. As players understand the strategies, they can act and anticipate what other players might do similar to Game Theory. In TFT, it is a game of complete information where players can know exactly what they’re opponents are doing throughout the game by scouting out what their boards look like. With this capability it allows players to adjust their strategies towards the late game because of the limited unit pool. This facet of TFT discourages players in a match from pursuing the same exact strategy. With our data analysis, we can better understand the end game strategies in TFT and this knowledge can be beneficial to both players and developers. Most players can refine their strategies in a time efficient manner and professional players can have data backing their claims about the state of the game. Furthermore, TFT developers that balance and change the game can utilize such information to better the game itself.


The data analysis portion was completed via partner programming and my partner developed a GUI for the project to allow for simple visualization of analyzed data. I think having visualization tools made this project very helpful if we ever decide to go back and try revitalize the project. We realized a lot of compositions weren’t being registered, so there might be more efficient ways to identify compositions more broadly; however, due to personal experience I feel like this could easily be explained due to the flexible strategies that can be mixed and matched. In the future, I might want to revisit this project to see what other analysis could be done because there are other nuances related to a players’ strategy apart from end game strategies. Additionally, I’m curious what the Riot API might have to offer in regards to player/match data now since the game has developed even more.
