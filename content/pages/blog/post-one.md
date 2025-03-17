---
title: Mutual Fund Report
layout: PostLayout
# date: '2021-05-28'
author: content/data/team/dianne-ameter.json
excerpt: >-
  Report investigating the performance and similarity between 6 Vanguard Mutual
  funds.
featuredImage:
  type: ImageBlock
  url: /images/markus-winkler-IrRbSND5EUc-unsplash.jpg
  altText: Post thumbnail image
media:
  type: ImageBlock
  url: /images/index funds by the growth of a dollar.png
  altText: Post Image
  elementId: guitar
bottomSections:
  - type: RecentPostsSection
    colors: colors-d
    elementId: ''
    showDate: false
    showAuthor: false
    showExcerpt: true
    showReadMoreLink: true
    readMoreLinkLabel: Read more
    variant: variant-d
    actions: []
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
    title: Read more
    subtitle: null
    recentCount: 3
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
This was the final project for a course I took on computational econometrics. It was roughly a quarter long application project utilized to demonstrate the concepts and techniques taught. Analysis of six vanguard mutual funds helped figure out the general stability and variance/standard deviation between the various assets in question. The interesting metrics that I hoped to answer were the relative growth of the fund in comparison to each other, how similar the funds are, and much more.

First of all, this project put into perspective the necessary precautions with investments. Investment strategies aren’t cookie cutter and the individuals have different needs. It is important to cater to both risk aversion and the targeted return values of a portfolio. Diversification is a key element in order to help reduce the volatility that comes with uncertainty in the future. I think this puts into perspective the idea of trying to gain in the long term very meaningful because short term losses feel more impactful from a behavioral economics perspective. People have different reference points, but losses below someone’s reference point feel way worse than the equivalent gain of the same magnitude. This is explained from the perspective of loss aversion rather than risk aversion that challenges some of what classical economics has to say about people’s relation to fair gambles.  

Overall, each individual has their own risk tolerance and desirability for return goals. This project reinforced the ideas I’ve learned in terms of balanced portfolios based on the ratio of assets for an individual or given the possible trade restrictions with a balance of risk free and/or no risk-free assets.

Main Findings

 • Stock tracking mutual funds like vfinx, veurx, veiex, and vpacx tend to have similar time trends overtime. This was seen with the downward trend that was found in those Vanguard funds within the years of both 2015 and 2018.

 • The other two vanguard funds that track bonds, vbisx and vbltx, exhibited more movements together as there was a noticeable drop that occurred in the year of 2016 when Trump was elected. (Economic Times)

• Stock funds (vfinx, veurx, veiex, and vpacx) were positively correlated with another and the bond funds (vbisx and vbltx) were positively correlated with each other.

• The six Vanguard funds seemed to be normally distributed which allowed for GWN model analysis.

• Risk and return of some individual funds like vpacx, veurx and veiex were overshadowed because they had higher risk and overall lower returns comparatively to either vfinx or vbltx.

• Global minimum variance portfolio with or without short sale restriction had lower risk than holding any individual asset.

• Global minimum variance portfolio with short sale restrictions had a lower sharpe ratio and overall, more risk than the global minimum variance portfolio able to short sell.    

The following are some of the visualizations and calculations done within this project:

![](/images/fundprices.png)

1.A) Fund's prices across time

![](/images/fundreturns.png)

1.B) Fund's Return Across Time

![](/images/covariance%20comparison.png)

2.A) Covariance comparison of the various mutual funds

![](/images/risk%20and%20return%20sharpe%20ratio.png)

2.B) Risk and Returns of Various Funds/Sharpe Ratios of Assets

![](/images/returnsboxnwhisker-fc71221f.png)

2.C) Variability and Spread via Box-And-Whisker Plot of the Funds

![](/images/univariate%20descriptive%20statistics.png)

3.A) Univariate Descriptive Statistics of the Funds including Skewness and Kurtosis of Historical Data

![](/images/gmvNoSS.png)

4.A) Global Minimum Variance Portfolio -- Portfolio with the lowest amount of risk

![](/images/efficientfrontierMarkowitzbullet.png)

4.B) Markowitz Bullet/Efficient Frontier of Various Optimal Portfolios w/ and w/o trade constraints

After analysis it was possible to come up with the distributions, the type of assets these funds were tracking, and the optimal weights for short sell and short sell restricted scenarios for the funds. These samples of graphics above are some of the visualizations utilized to come up with such conclusions highlighted in the findings.

Going forward because of my interest in investments I hope to look more into the taxation aspects because it is an important facet as earnings are taxed. I wish to learn more about investments as there are ways to better portfolios and manage uncertainty. I feel like this is important both as an individual looking to partake in investments and also helping others make informed decisions about their own portfolios.
