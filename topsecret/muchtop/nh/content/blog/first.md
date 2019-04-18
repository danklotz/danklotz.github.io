+++
categories = ["paper"]
comments = false
date = "2016-10-02T15:59:13-04:00"
draft = false
showpagemeta = false
showcomments = false
slug = ""
tags = ["HESS", "#1","LSTM"]
title = "Rainfall–runoff modelling using Long Short-Term Memory (LSTM) networks"
description = "In this paper, we propose a novel data-driven approach for rainfall–runoff modelling, using the long short-term memory (LSTM) network, a special type of recurrent neural network. We show in three different experiments that this network is able to learn to predict the discharge purely from meteorological input parameters (such as precipitation or temperature) as accurately as (or better than) the well-established Sacramento Soil Moisture Accounting model, coupled with the Snow-17 snow model."
+++


<img src ="/blog/first_files/hess.png">


### Authors
- Frederik Kratzert (kratzert@ml.jku.at)
- Daniel Klotz
- Claire Brenner 
- Karsten Schulz 
- Mathew Herrnegger 

### Abstract
Rainfall–runoff modelling is one of the key challenges in the field of hydrology. Various approaches exist, ranging from physically based over conceptual to fully data-driven models. In this paper, we propose a novel data-driven approach, using the Long Short-Term Memory (LSTM) network, a special type of recurrent neural network. The advantage of the LSTM is its ability to learn long-term dependencies between the provided input and output of the network, which are essential for modelling storage effects in e.g. catchments with snow influence. We use 241 catchments of the freely available CAMELS data set to test our approach and also compare the results to the well-known Sacramento Soil Moisture Accounting Model (SAC-SMA) coupled with the Snow-17 snow routine. We also show the potential of the LSTM as a regional hydrological model in which one model predicts the discharge for a variety of catchments. In our last experiment, we show the possibility to transfer process understanding, learned at regional scale, to individual catchments and thereby increasing model performance when compared to a LSTM trained only on the data of single catchments. Using this approach, we were able to achieve better model performance as the SAC-SMA + Snow-17, which underlines the potential of the LSTM for hydrological modelling applications.

#### Links
- [Paper](https://www.hydrol-earth-syst-sci.net/22/6005/2018/)
- [EarthArXiv](https://eartharxiv.org/qv5jz/)
- [Peer-Review](https://www.hydrol-earth-syst-sci.net/22/6005/2018/hess-22-6005-2018-discussion.html)