---
layout: page
permalink: /projects_and_data/
title: projects & data
description: Below you will find the description and request links for datasets used in my research.
---

<h3 class="year">Projects</h3>

<br/>
**-- Data Science Applied to Secondary Education (2020-ongoing)**
<br/>
In this project, the goal was to develop machine learning models for different
challenges faced by secondary education, i.e., evasion prediction and content
recommendation for adaptive learning.

<br/>
**-- Machine Learning for Automatic Log Classification (2019)**
<br/>
In this project, the goal was to apply machine learning and natural language
processing techniques to automatically classify printers' logs into hardware
fault or non-faulty examples.


<h3 class="year">Datasets and source code</h3>
<br/>
**-- SMDI-700k**
<br/>
The SMDI-700k dataset was obtained from a customer supermarket of [HiMarket](http://himarket.club/).
It contains data from August 1st, 2019, to November 30th, 2019.
This dataset is characterized by implicit feedback, i.e., there are only positive observations (interactions between users and items) available.
These interactions represent items purchased by supermarket users and were collected from 131125 supermarket transactions during the analyzed period.
We made available three versions of the dataset, the original one (SMDI-700k_original.csv) and two preprocessed versions (SMDI-400k_max500repeated.csv and SMDI-400k_max200unique.csv).
For all dataset version, the ratings are chronologically ordered and reported in the <user; item; rating; timestamp> form.
In addition to the rating information, we also provide additional data about users and items.
On the user content level, considering that only purchase information’s was collected, we calculate de RFM score (recency, frequency and monetary).
The normalized recency, frequency, and monetary values, calculated at the end of each month and also based on the total period, are available at file SMDI-700k_users.csv, as the number of ratings and unique ratings per user.
On the item content level, the price, session to which the item belongs, and the brand are available (for the session and brand, only the identifiers are shown).

<span style="color:blue">**This manuscript is currently under review. If you are reviewing the paper, you should have received a direct link to download the dataset. The actual link for downloading this dataset will be made available upon paper acceptance.**</span>


**-- Adaptive global k-Nearest Neighbors for hierarchical classification on data streams**

<br/>
The Global kNN-hDS is a method tailored for classifying potentially unbounded hierarchical data streams.
This proposal is a global hierarchical kNN and was designed to predict single and full depth label paths of hierarchically structured classes from data streams.
As a global approach, the method can processes new instances with less computational efforts when compared to methods that use local approaches. Furthermore, it works with constant memory by using a memory buffer set by the user.


<span style="color:blue">**This manuscript is currently under review. If you are reviewing the paper, you should have received a direct link to download the dataset and source code. The actual link for downloading this dataset will be made available upon paper acceptance.**</span>
