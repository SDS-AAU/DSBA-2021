---
title: Day 1 - Networks
weight: 1
disableToc: true
---

## Practical info
Place: DHØ 1.23
Time: 8:15 (we start 15 min later) - 13:20


## Schedule for the day

|           | Time        | Activity        | Data           |
|-----------|-------------|-----------------|----------------|
| Session 1 | 8:15-9:00   | Intro , Q\&A, Introducing dataset | [Danish power elites](https://openpolicing.stanford.edu/)  |
| Session 2 | 9:00-11:30 | Network exploration | [Danish power elites](https://openpolicing.stanford.edu/) |
| Session 3 | 12:00-13:15 | WS: AI as a service  | |

## Dataset & Context

### Introduction 

#### Context: The Danish Power Elites

* [Antons PhD Thesis](https://magtelite.dk/wp-content/uploads/2015/09/Anton-Grau-Larsen-PhD-Elites-in-Denmark.pdf)
* [Brief Summary of findings (CBS)](https://www.cbs.dk/en/alumni/news/a-look-the-danish-power-elite)
* [Journal Paper in Sociology](https://journals.sagepub.com/doi/abs/10.1177/0038038512454349)
* More to be found with googleling...

#### Data

* [Github (R Repository)](https://github.com/antongrau/eliter)
* [Magteliten website](https://magtelite.dk/data/)
* Or, easier... on [our github](https://github.com/SDS-AAU/SDS-master/raw/master/00_data/networks/elite_den17.csv)

### Tasks

* Who are the most central persons?
* Communities?
* What characterizes them?
* * Link up with additional data?

## Workshop: AI as a Service

By guest: Andreas Markussen 

### Introduction 

The purpose is to demonstrate a minimum viable product of an ML model deployment. Keeping with the DSBA spirit, I would keep the section hands-on. I would cover a minimal ML pipeline using data that is already preprocessed. The model will be saved to a static file and served through an API. When done, we will have created a web service from scratch, that can be used by any user in their browser. The project will be conducted in Python, with a little HTML added.


### Structure:

- Very brief introduction to how the web works - 15 mins
- Building model and exporting to static file - 15 mins
- Building Flask web app - 10 mins
- Adding APIs - 10 mins
- Adding some HTML and concluding the complete web service - 10 mins
- Deployment to Heroku free account, short showcase of extensions and other applications (no code here) and rounding off - 15 mins

### Preperation

To get most of this workshop, you should have: 

- Some existing knowledge of Python
- A local installation of Python
- Good understanding of an ML flow.
- No understanding of the web in general



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


