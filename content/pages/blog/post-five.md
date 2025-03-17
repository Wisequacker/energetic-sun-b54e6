---
title: Investigating Small HR Database
layout: PostLayout
# date: '2022-02-19'
author: content/data/team/hugh-saturation.json
excerpt: >-
  Diving into a mini-project looking into a small HR database from a company
  utilizing SQL transactions.
featuredImage:
  type: ImageBlock
  url: /images/sebastian-herrmann-O2o1hzDA7iE-unsplash.jpg
  altText: Post Image
media:
  type: ImageBlock
  url: /images/campaign-creators-gMsnXqILjp4-unsplash.jpg
  altText: Post Image
  elementId: guitar
bottomSections:
  - elementId: ''
    variant: variant-d
    colors: colors-d
    title: Read more
    showDate: false
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
    actions: []
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
metaDescription: >-
  Sunset fishing is a beautiful time of day to relax and get in touch with
  nature
socialImage: /images/desmond-eagle.png
addTitleSuffix: true
---
The following project was conducted as I was wanting to look at this sample HR database of a small business (database found from: https://www.sqltutorial.org/sql-sample-database/). To perform data analysis, I utilized SQL transactions to help answer pertinent questions from the database to consult the HR of a small business. I’ve grown to appreciate the relational database storage format because it is easy to edit/modify the database as needed and to reduce redundancy due to similar elements found in multiple rows of data in contrast to something like a spreadsheet or csv file. I would like to see more usage of relational databases to maintain information in the future because sometimes working with csv files aren’t that optimal.   

By examining this HR data provide indicators of the relationships between the small company and their employees. Some points of interest include employee pay, operational locations, and benefits. The end goal of this database exploration was to create a condensed report that would answer relevant questions I had about this company to help better understand its relationship with its employees. This way I could advise and make suggestions to help foster this company’s growth.  

General findings:

·        It’s a small company with only 40 total employees/hires.

·        The company has operations happening in a total of four countries.

·        Regional data presented doesn’t included the continent of Australia or Antarctica

![](/images/countriesHR.png)

·        Hiring data has information that spans 1987 to 1999.

·        After July 1994 the company saw the highest frequency of hirings and that month it had the maximum number of hirings in counting.

·        30 total dependents and departments with the most dependents are purchasing and finance w/ six.

·        Majority of employees tend to have a salary lower than the average salary pay for their particular occupation.

·        Average maximum salary of all jobs on the market: $13,210.53

·        Workers are paid below the averages of their respective salaries

A more detailed report with visualizations can be found: https://drive.google.com/file/d/1droIn-avBqmZ3vRLnXugIwl875-Cdz_A/view?usp=sharing

Based on the above findings, this company likely imports goods and sells these imported products because of their various roles that revolve around purchasing and selling. Since the business’ market details aren’t explicitly stated, that would be my best guess on the field of interest for this company. Additionally, this company is mostly based in North America (US and Canada) with workers working abroad in Europe. I think based on what I’ve seen I think it’s best to continue to grow their base in the United States before expanding to a more global reach as 1/3 of the hires are from the UK, Canada, and Germany. Furthermore, the data shows that workers are being paid less than typical salaries of such roles. I think this should definitely change as the company continues to grow; however, it is also likely that the company is currently too small and they have other possible benefits for their employees like stock shares or insurance coverage that makes their jobs worthwhile.           

Overall, I feel like this SQL project was rewarding because this analysis allowed for the investigation of a small company to seek valuable information that could hint at the current relationship of its workers and the firm. I would have liked to see more information existing in this database because the data seemed quite limited since there are only 40 employees. Additionally, there is more room to gather relevant HR data for this company. I would like to see more information on the duration of hires since some employees quit/leave the company over time. I think moving forward from this project I would like to work with a larger dataset/database and create meaningful data visualizations and dashboards.
