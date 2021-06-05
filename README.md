# Introduction

Because GitHub has limited file size, please click the [link](http://203.195.140.107/dataset/download#/) to download the complete dataset.

File `1.json` is a collection of news obtained by searching keywords "China" and "coronavirus" on major media websites, and we use a crowdsourcing system to label each news article. The collection contains news from December 2019 to June 2020, with a total of 4115 articles.

File `2.json`  is a collection of news obtained by searching keywords "China" and "Coronavirus" on major media websites. The collection contains news from December 2019 to June 2020, with a total of 75838 articles.

File `3.json`  is a collection of news obtained by searching the keyword "coronavirus" on major media websites. The collection contains news from December 2019 to June 2020, with a total of 301681 articles.

The dataset may contain the following fields：

| KEY                  | DESCRIPTION                                                             |
|----------------------|-------------------------------------------------------------------------|
| news_title           |     News title                                                                    |
| news_content         |     News content                                                                   |
| news_source_url      |     Official website link of media website                                                                    |
| news_country         |     Media country                                                                    |
| emotion              | objective, agreeable, believable, good, hated, sad, worried             |
| stance_against_china | positive, neutral, negative                                             |
| about_china          | `true` means the news is related to China，otherwise `fasle`
| topic                | politics, society, technology, economy, sports, humanity, entertainment |
| type                 | fact, interview, essay, remark                                          |

For example:

```Json
{
    "news_title": "China orders sharp cuts in flights in, out of country to curb coronavirus risk",
    "news_content": "BEIJING (Reuters) - China has ordered airlines to sharply cut the number of flights in and out of the country out of concern that travelers from overseas could reignite the coronavirus outbreak that paralyzed the country for two months.\nThe Civil Aviation Administration of China (CAAC) said on Thursday it had directed Chinese airlines to maintain only one route to any country and limit the number of flights to one per week, effective March 29.\nThe authority also ordered foreign airlines to reduce their international routes to China to one per week and only operate one route into the country.\n“In accordance with the need for epidemic containment, CAAC may issue policy to further reduce the total number of international passenger flights,” the regulator said in a statement.\nAround 80% of international flights were already being canceled prior to the announcement, but Chinese airlines had been asked not to cut their international routes until Thursday’s order by the CAAC.\nChina also will temporarily suspend the entry of foreigners with valid Chinese visas and residence permits starting on March 28, the Foreign Ministry said on Thursday.\nThe moves, in conjunction with severe quarantine rules now being imposed on people arriving in the country, are set to slow the flow of inbound travelers to a trickle.\nBeijing is keen to prevent a resurgence of the coronavirus epidemic that emerged in the Hubei region’s capital Wuhan in late 2019 and has killed nearly 3,300 Chinese citizens to date and more than 21,000 people globally.\nSevere curbs on travel and transport brought the epidemic under control in China but at a heavy price, with some analysts expecting an outright contraction for the country’s economy in the first quarter. Beijing is exhorting industries to reopen, but the virus, which has now spread around the globe, continues to threaten China’s economy and the health of its people.\nMainland China has not seen any new locally transmitted coronavirus cases in six of the past eight days, shifting the focus to preventing infected people arriving from overseas from triggering a fresh outbreak in the country. All 67 new cases reported by the end of Wednesday were imported, as were all 47 reported the previous day, the National Health Commission said earlier on Thursday, putting the total number of confirmed cases to date at 81,285.\nThe commission reported a total of 3,287 deaths by the end of Wednesday, up six from the previous day.\nHubei, home to some 60 million people, reported no new cases on Wednesday and opened its borders.\nThe lockdown of Hubei’s capital Wuhan, where the virus first appeared late last year, will be lifted on April 8, a milestone in China’s war against the epidemic.\nAbout 90% of all the imported cases are Chinese passport holders, Vice Foreign Minister Luo Zhaohui told a press conference, adding that 40% of those were overseas Chinese students returning amid rising infections abroad.\n“We understand some overseas students are eager to come home...But under the current circumstances, by staying put, they can avoid being cross-infected in the hurried journey home or getting stuck mid-journey when the countries they transit in tighten border controls,” Luo said.\nShanghai will make every international traveler arriving from 6 p.m. local time (1000 GMT) on Thursday go into quarantine for 14 days, the local government announced.\nIt had previously only required this for travelers who had visited any of 24 badly-hit countries in the previous two weeks.\n",
    "news_source_url": "https://www.reuters.com/",
    "news_country": "The United Kingdom",
    "emotion": "objective",
    "stance_against_china": "neutral",
    "about_china": true,
    "topic": "politics",
    "type": "fact"
}
```


If you use the data for publication, please kindly cite the following papers:
```
@article{
    title="China in the eyes of news media: a case study under COVID-19 epidemic",
    author="Hong HUANG, Zhexue CHEN, Xuanhua SHI, Chenxu WANG, Zepeng HE, Hai JIN, Mingxin ZHANG, Zongya LI",
    journal="Frontiers of Information Technology & Electronic Engineering",
    volume="-1",
    number="-1",
    pages="",
    year="1998",
    publisher="Zhejiang University Press & Springer",
    doi="10.1631/FITEE.2000689"
}
```
