
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
| 9:10-9:30   | Indivitual/Groups work making sense of data, preprocess                   |
| 9:30-9:45   | Follow up in class               |
| 10:00-11:00 | Train SML model for congress and classify the pres. debate tweets  R/Py split                                     |
| 11:10-11:30 | Discuss solutions R/Py split                                          |
| 11:30-12:00 | Joint review, Hand out Peergrade assignment                           |  




## In class Notebooks

* R team [:::: HERE ::::](https://sds-aau.github.io/SDS-2021/workshops/2021/M2_workshop_nlp_R.nb.html)

* Python team [:::: HERE ::::](https://colab.research.google.com/github/SDS-AAU/SDS-2021/blob/master/static/workshops/2021/SDS21_M2W2.ipynb)


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
