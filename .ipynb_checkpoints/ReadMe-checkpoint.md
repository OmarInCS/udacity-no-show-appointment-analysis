# Project: Investigate No-show Appointment Dataset

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#fe">Feature Engineering</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
<li><a href="#action">Call to Action</a></li>
<li><a href="#references">Important References</a></li>
</ul>

<a id='intro'></a>
## Introduction

In this paper we will investigate a dataset that contains information about patients and their appointments, including a column shows if they show up at the appointment or not.

the report aim is to answers a question, what is the main three features make a patient miss his/her appointment?

to score the aim, the report will follow the steps of wrangling the dataset, building new features that hopefully will be more correlated to the dependent feture, then exploring the relations between different features and the 'no-show' feature


<a id='conclusions'></a>
## Conclusions

> Although, we have a lot of features which seem affecting the patient appointment missing, exploration analysis showed that none of them have a significant infelunce on missing the appointment. However, we can state three of the features that may help to make a rough prediction two of them are coorelated **SMS_recived** and **DaysDeference**, then the last one is **previous miss**.

> patients who make appointments in range of two days early tend to attend their appointment by a percent more than 90, this percent drop to below 70, for the patient who made their appointments more than a week a head.

> patients who miss their appointment once before, are 10% more likely to miss their new appointment.

<a id='action'></a>
## Call to Action
> It may be useful if the hospital limit prebooking to be only a week ahead, we recommend studying this option more. 
