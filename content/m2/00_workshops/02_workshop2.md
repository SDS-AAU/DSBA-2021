
---
title: "Workshop 2 - Classification of Political US Tweets"
weight: 2
disableToc: true
draft: false
---

## Introduction 

### Context: Presidential Debate 2020


Yes, we are going back in time to the Presidential Debate in the US 2020 - the time of lots of unhappy Tweeting. It's just too good a dataset and case to let it go...

![](https://ichef.bbci.co.uk/news/800/cpsprodpb/E505/production/_114692685_uspresidentialdebate2020timedonaldtrumpandjoebiden.jpg)

### Data

* Political tweets: `https://github.com/SDS-AAU/SDS-master/raw/master/M2/data/pol_tweets.gz` from https://github.com/alexlitel/congresstweets We've preprocessed a bit to make things easier. 0: Dems. 1: Rep.

* Tweets around the time of the debate in oktober 20 (8000): `https://github.com/SDS-AAU/SDS-master/raw/master/M2/data/pres_debate_2020.gz`

Both datasets are in JSON format.



# Tasks

* Preprocess both datasets for NLP (supervised)
* Start by building a classification model for the congress tweets
* Use a well performing model to classify new data (tweets from the presidential debate)
* Explore the different classes


# Schedule for the workshop


| Time        | Activity                                                              |
|-------------|-----------------------------------------------------------------------|
| 11:40-12:00 | Introduction to the context                                           |
| 12:00-13:00 | Joint EDA and NLP refresher                                           |
| 13:15-14:45 | Setting up the NLP workflow on congress tweets                        |
| 15:00-16:00 | PRedicting on new data, evaluation of results                         |
| 16:15-17:00 | Hand out Peergrade assignment, Introduction to final project          |  



<!---
## In class Notebooks

* R team [:::: HERE ::::](xxx)

* Python team [:::: HERE ::::](xxx)
--->

<!---
* [{{< awesome fas fa-laptop-code >}} Py Colab - With comments](https://colab.research.google.com/github/SDS-AAU/SDS-master/blob/master/M2/exercises/M2_W1_Elites.ipynb
)
--->

<!---
{{< tabs >}}

{{< tab name="Joint recordings">}}
  <h2>Assignment 1 handout</h2>
  {{< panopto  "https://panopto.aau.dk/Panopto/Pages/Embed.aspx?id=4b2660d2-790f-49cf-84be-ada900ea3083&autoplay=false&offerviewer=true&showtitle=true&showbrand=false&start=0&interactivity=all" >}}

{{< /tab >}}



{{< tab name="R Application">}}
<div>

  <h2>R: Recording</h2>
 
 coming soon

</div>
{{< /tab >}}



{{< tab name="Python Application">}}
<div>
  
  
  <h2>Python group recoding </h2>
  {{< panopto "https://panopto.aau.dk/Panopto/Pages/Embed.aspx?id=3c6006e6-e8e2-4ac4-a0a8-ada900ea85bc&autoplay=false&offerviewer=true&showtitle=true&showbrand=false&start=0&interactivity=all" >}}
</div>
{{< /tab >}}

{{< /tabs >}}
 --->
