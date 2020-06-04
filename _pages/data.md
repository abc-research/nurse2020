---
layout: single
title: Data Description
permalink: /data_description/
date: 2020-01-08T00:00:00+09:00
---
The dataset consists of care activities that nurses do in the Care facility. The activities can be categorized in 3 principle types:
<ul>
  <li>Help in Mobility</li>
  <li>Assistance in Transfer</li>
  <li>Position change</li>
</ul>
![mobility](/nurse2020/assets/1.png "Help in Mobility") ![transfer](/nurse2020/assets/2.png "Assistance in Transfer") ![position](/nurse2020/assets/3.png "Position change")
This activities further divided into several categories as shown in the image below:
![activity list](/nurse2020/assets/actList.png)
The data was collected in an experiment lab and in the real field. The lab data was collected in the Smart Life Care Unit of the Kyushu Institute of Technology in Japan. In this experiment, 2 subjects participated who are professional nurses. To collect the data accelerometer sensor in Mobile phone and motion capture was used. But we are opening only the mobile phone accelerometer data for this challenge. For the real field data, it was collected in a Care Facility in Japan. Data collection was done using mobile phone accelerometer and 47 subjects participated in this experiment. We are opening data of 6 nurses for training and 3 nurses for testing in this challenge. 
<ul>
  <li>Position of the Mobile phone: Attached in right arm using armband</li>
  <li>Sampling rate: 60 Hz</li>
  <li>Preprocessing: No preprocessing method is applied on this data</li>
  <li>Training data: [Download the training data](https://ieee-dataport.org/open-access/nurse-care-activities-datasets-laboratory-and-real-field)</li>
  <li>Testing data: will be sent to the registered participants later</li>
</ul>

## Data structure
Training
<ul>
  <li>Field accelerometer data (6 subjects)</li>
  <li>Lab  accelerometer data (2 subjects)</li>
  <li>labels of field data</li>
  <li>labels of lab data</li>
</ul>
Testing
<ul>
  <li>Field accelerometer data (3 subjects) </li>
</ul>
