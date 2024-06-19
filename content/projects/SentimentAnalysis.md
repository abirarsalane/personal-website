---
title: "Sentiment Analysis on Climate Change in Morocco"
description: "Scrapping the entire internet to conduct a Sentiment Analysis on Climate Change in Morocco in darija. AN NLP CHALLENGE!"
dateString: July 2023
draft: false
tags: ["NLP", "M;", "Python", "Scrapping", "Models", "Training", "Topic Modeling", "Sentiment Analysis"]
weight: 104
cover:
    image: "/projects/Sentiment-analysis/climatechange.png"
---


# Introduction
Have you ever thought of knowing what moroccan people in Morocco on social media think about Climate Change? And no, not in english, not in french, and definitely not using latin alphabet (Fun Fact: Darija can be typed in latin alphabet in case you didn't know, and it would have made the job way easier). If the answer is yes, it's your lucky day, because I've already done all the heavy lifting and now you can enjoy the results. The idea behind this project is scrapping **ALL** social media platforms to understand what moroccans think about climate change.

# Results and process
Read this first, it combines everything. If you have more time, you can scroll down for more details.

![](/projects/Sentiment-analysis/sentiment-analysis1.png)
![](/projects/Sentiment-analysis/sentiment-analysis2.png)

# Challenges
## Scapping
Scrapping was A CHALLENGE, not only because scrapping from social media platforms is already a challenge (it's no secret), but also because NO ONE talked about climate change (at least not in darija), you can find moroccans talking about the issue in english, french or darija in latin alphabet never in arabic alphabet, so scrapping took a **LONG LONG** time. This goes without even mentionning the struggle of scrapping from facebook, instagram, youtube, twitter (X)..

## Pre-processing
Preprocessing data in darija? Yes, no problem, it's not like we combine 2,3,4 words in one.. 

## Labeling
Ok, good luck trying to understand what the person **ACTUALLY** meant with what they said. Are they happy? sad? Was that sarcastic? It's time to put Machine Learning aside and tackle psychology because you know, Machine Learning is definitely NOT the challenge here. And even if you don't have to worry about the emotion, you will definitely have to worry about the intentions and context, because the same sentence can have many many meaning depending on the context and the intentions of the person. Picture this: I was literally reading teh sentence out loud and trying to match the vibe through different tonations. FUN TIME!

## Models Training
After all the hard work done before, we have finally reached the **Machine Learning** part, and surprisingly (or not) it's the easiest. All I had to do was improve the accuracy of the best performing model. In this case it was Logistic Regression. After that, I implemented K-means to do Topic Modeling finding out that there are 3 main topics: political, religious and social.

## Data Viz
And finally, I plotted the variation of emotions throught the months and the rate of comments in the matter globally, and for each topic.


