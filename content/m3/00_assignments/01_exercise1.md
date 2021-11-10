
---
title: Workshop 1 - AirBnb revisited
weight: 2
disableToc: true
---

## Introduction 

### Context: Flashback to AirBnb Data that we used in Workshop 3 of M1


In this workshop we are going to explore the [insideairbnb](http://insideairbnb.com/) using deep learning techniques.
We used the data in a research project some years ago and you can check out a conference presentation below:


## 1. Build a neural net for price prediction.

Your job is to build a feed-forward network using Keras to predict the price.
Can you beat the performance of other models that we explored in M1 (using the same set of independent variables)? Start with a "simpler" baseline model using 1 2 layers only (one input layer one output layer).

## 2. Tune the network.

Experiment with different set-ups changing e.g.:

- number of neurons
- number of layers 
- number of epochs and batch size
- activation functions (reasonable choices)
- optimizers and losses (again: reasonable choices)

Use the Keras documentation and community sources to identify best practices. However, do not spend hours on grid search!

## 3. Prevent overfitting

This part is related to 2. Explore the training process (over the epochs). Explore and describe 2 common approaches used to prevent overfitting in deep feed-forward neural nets.


## In class Notebooks

* R team [:::: HERE ::::](https://sds-aau.github.io/SDS-2021/workshops/2021//M3_workshop1_ann.nb.html)
* [{{< awesome fas fa-laptop-code >}} Py Team](https://colab.research.google.com/github/SDS-AAU/SDS-master/blob/master/M3/notebooks/M3_W1_AirBnb_revisited_with_Neural_Nets.ipynb)


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
