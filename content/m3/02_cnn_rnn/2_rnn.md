---
title: "Recurrent Neural Networks"
weight: 2
disableToc: true
draft: false
---


{{% notice tip %}} Use the tabs to access content. Theory part is general, R & Python application part language specific.
{{% /notice %}}

This session introduces to recurrent neural networks (RNN) and Long-Short-Term Memory Networks (LSTM), which model sequential data well (eg. text, timeseries)

## Suggested Datacamp courses
* Recurrent Neural Networks for Language Modeling in Python


{{< tabs >}}

  {{< tab name="Theory - Recurrent Neural Networks">}}
  
  <h2>Video: Introduction CNNs</h2>
    {{< loom  d1b775f28a194fa7a6f6c62d037a9870 >}}
  
  <h2>Slides</h2>  
    Use arrows keys on keyboard to navigate. Fullscreen slides <a href="https://sds-aau.github.io/SDS-master/M3/notebooks/RNN_intro.html" target="_blank"> available here </a>
      {{< IncludeSlides "https://sds-aau.github.io/SDS-master/M3/notebooks/RNN_intro.html" >}}
    
  {{< /tab >}}


{{< tab name="R Application - RNN">}}

Also check Python MAterial

<div>
   <h3>Follow along</h3>
  <ul>
    <li>{{< awesome fas fa-laptop-code >}} <a href="https://sds-aau.github.io/SDS-master/M3/notebooks/RNN_application_R.nb.html" target="_blank">HTML Notebook</a> </li>
  </ul>

  <h2>Video 1: Intro RNN</h2>
  {{< loom eaf2f07b85ef498fbf7a356ad25e9ee9>}}
  
  <h2>Video 2: IMDB Case </h2>
  {{< loom 36ac6f7d36fa4c16b6df77dcdb2135b9>}}
  
</div>
{{< /tab >}}


{{< tab name="Python Application - RNN">}}
<div>
   <h3>Follow along</h3> 
  <ul>
    <li> Simple Timeseries{{< awesome fas fa-laptop-code >}} <a href="https://colab.research.google.com/github/SDS-AAU/SDS-master/blob/master/M3/notebooks/RNN_simple_timeseries.ipynb" target="_blank">Colab Notebook</a> </li>
    <li> Bi-LSTM on IMDB {{< awesome fas fa-laptop-code >}} <a href="https://github.com/SDS-AAU/SDS-master/blob/master/M3/notebooks/bidirectional_lstm_imdb.ipynb" target="_blank">Colab Notebook</a> </li>

  </ul>

  <h2>Video 1: Simple Timeseries</h2>
  {{< loom ac7d5a60b72a4e5d9c7ac03c38aa6401>}}
  
  <h2>Video 2: Bi-LSTM on IMDB </h2>
  {{< loom ee51f2982a34497eafa5ae77238d72ea>}}
  
</div>
{{< /tab >}}


{{< /tabs >}}

