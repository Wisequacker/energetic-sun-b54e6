---
title: 'MCU: Avengers Character Network Analysis'
layout: PostLayout
date: '2022-02-21'
colors: colors-a
author: content/data/team/hilary-ouse.json
excerpt: >-
  Exploration of the vast character relationships within the Avengers utilizing
  machine learning.
featuredImage:
  type: ImageBlock
  url: /images/output_26_0.png
  altText: Post Thumbnail Image
media:
  type: ImageBlock
  url: /images/output_26_0.png
  altText: Post Image
bottomSections:
  - elementId: ''
    variant: variant-d
    colors: colors-d
    title: Read more
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
    showReadMoreLink: true
    readMoreLinkLabel: Read more
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
The Marvel Cinematic Universe: Avengers Character Network Analysis is the final project done with a group for the cultural analytics course. Currently, the Marvel Cinematic Universe has a lot of heroes, and these independent hero stories come together under the umbrella of the Avengers as they fight for humanity. Of these heroes, our team wondered who is the most important original Avenger in the Marvel Cinematic Universe-- Iron Man, Captain America, Hulk, Thor, Hawkeye, and Black Widow. This project is to debunk the relevance of characters in the major Avengers films where these six heroes appear together.

I thoroughly enjoyed this project because I was able to lead our group as the other three had limited experience with Python. This project was inspired by the Network of Throne project, a Game of Thrones Network Analysis by Andrew Beveridge and Jie Shan (<https://tinyurl.com/NetworkofThrones>). This was a meaningful project for us because we all liked the Marvel Cinematic Universe. I advocated for this ambitious project, despite most of my team members having limited coding experience because the cast of heroes in the MCU are quite vast. We all had favorites and we couldn’t decide who was the most connected and central character among the original six Avengers. I felt like there might be an overarching theme within the vast character connections despite their named and distinguished factions.

This project dataset was scraped from the movies wiki fandom (you can find more details on the collection and cleaning process on the GitHub \[] or the published report). This was an interesting project because we got to do analysis utilizing Natural Language Processing (NLP) and I got to web scrape for the first time. Although we were utilizing BookNLP (<https://github.com/dbamman/book-nlp>), I felt that being able to utilize NLP and network analysis has changed my perspective of how we analyze data and try to find relationships between entities. BookNLP was trained to work with books and it fit well in our opinion to this project given the limited time we had for the project. It was fitting because film scripts are essentially longer prose driven by consistent dialogue and a fair amount of scene description. Being able to locate the proximity of characters' names near each other was impactful to understand the centralized characters and reinforce their importance in the franchise via the NetworkX python package.

This data analysis had some interesting discoveries that highlighted particular film releases and also the character dynamics of the six original Avengers. Our general finding from the character network analysis is that both Captain America and Iron man are the top characters centralized acrossed films. These characters top the network analysis measures by having the most connections and connecting the most characters to each other.

![](/images/infinitywarbars.png)

![](/images/endgamebars.png)

Before the release of Avengers Endgame, there have been numerous Captain America and Iron Man films dedicated to their stories which makes sense as they are the most centralized heroes. These prior films also highlight the internal battle of being leaders, especially during the Captain America Civil War film that featured the same six original Avengers. However, I was pleasantly surprised to see that Thor wasn’t as central compared to both Iron Man and Captain America. I think this puts into relative perspective the data can derive character personalities. Thor is known to act independently and in the MCU he is definitely a mighty god that acts more than speaks. Furthermore, since the overarching villain is Thanos after Ultron died, I expected these villains to be quite central as well in their relevant films. Comparatively it seemed like Thanos was definitely more feared than Ultron and was a major villain in both Infinity War and Endgame. As a film watcher, this also makes a lot of sense given Thanos had a lot of character development compared to Ultron over the course of his two films. A thorough MCU Character Network Analysis report can be found on here: https://tinyurl.com/MCUCharacterNetwork

This character network analysis has allowed for the exploration of film releases and the development of heroes in the cinematic universe. It reinforces the ideas of leader, villain, and personality dynamics to shape the relationships of their heroes such as Iron Man, Captain America, Thor, Ultron, and Thanos. Overall, it feels like there are more ways to refine and continue to explore the vast character network in the Marvel Cinematic Universe. There are possible advancements in the project. In the future, it would be beneficial to thoroughly parse and remove named entities that aren’t heroes/characters within the film script. It may also be an interesting project to look into the word count by heroes to gauge the distributions of lines within a film.  After this project, I think the ability to add more films would also help with the character network analysis. The MCU films included in this project are the ones that included all the original six Avengers, but there are other relevant films with most if not a few of the original six.
