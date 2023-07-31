# Analyzing Suicidal Tweets 

## Introduction
This code is for my senior thesis project to graduate from Waseda University in the year 2023. The thesis is titled "Exploring Suicidal Expression in Online Spaces: An Ethical Analysis on Emotion Prediction and Suicide-Related Content on Social Media." The aim was to shed light on suicideal ideation and expressions of self-harm on social media, with a primary focus on Twitter. The project examines the emotional reactions of users to tweets containing the phrase "殺してくれる人" (*koroshitekureru hito* - someone to kill me) by employing emotion mining techniques. 

## Data Sources and References
1. Suicide Data
     The data on suicide in Japan was obtained from Japan's Ministry of Health, Labour and Welfare's annual [report](https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/hukushi_kaigo/seikatsuhogo/jisatsu/jisatsu_year.html) on suicide statistics. There are several years worth of reports and data containing details such as age, gender, time periods, occupation, etc.

2. Twitter Scraper
    [snscrape](https://github.com/JustAnotherArchivist/snscrape) by [JustAnotherArchivist](https://github.com/JustAnotherArchivist) was used to obtain the tweets for this project.

3. Emotion Mining Techniques
     The emotion mining techniques employed were based on the research paper [Emotion Analysis of Writers and Readers of Japanese Tweets on Vaccinations](https://aclanthology.org/2022.wassa-1.10/) of which the code can also be found on [GitHub](https://github.com/Ramos-Ramos/BERT-Japan-vaccination/blob/main/README.md).

