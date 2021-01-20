# Investigating No-show Appointments Dataset


This project is a part of the Advanced Data Analysis NanoDegree at [Egypt FWD](https://egfwd.com/data/), (first project)

#### -- Project Status: [Completed]

## Project Intro/Objective

A person makes a doctor appointment, receives all the instructions and no-show. Who to blame?

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment or not. 

### Methods Used

* Data Wrangling
* Exploratory Data Analysis
* Data Visualization

### Technologies

* Python
* Pandas, jupyter


## Project Description

This dataset contains some information about the patients like: 
<ul>
<li>Gender</li>
<li>Age</li>
<li>whether or not the patient is enrolled in Brasilian welfare program "Bolsa Família."</li>
</ul>  
Others about the appointment like: 
<ul>
<li>Day of the appointment</li>
<li>Day of the registeration for the appointment</li>
<li>Where the appointment takes place</li>
<li>SMS received, messages sent to the patients</li>
</ul>
And some diseases the patients have like: 
<ul>
<li>Hipertension</li>
<li>Diabetes</li>
<li>Alcoholism</li>
<li>Handcap</li></ul>
<hr>

### Questions
In my Investigation of this dataset I will try to check and answer these questions:
<ul>

<li>Does the patient's "Age/Gender" affect their show to the appointments?</li>
<li>On which days patients show more to their appointments?</li>
<li>Can we found any correlations between "the gap between the day of registration and the day of the appointments" and "the show-on the appointments"?</li>
<li>Are more messages sent to the patients increase their probabilities of showing up to the appointment? </li>
<li>What about patients enrolled in the Brasilian welfare program are those more likely to show up?</li>
<li>Does any deseases affect show/no-show to the appointments?</li>
</ul>

## Limitations

1. the dataset wasn't very easy to search into, all correlations were very small, and all the differences were the same for each case (absent vs attend) except for the Age and the gap between the day of registration and the day of the appointments
2. the dataset was very clean, although I found some outliers here and there but very small numbers as we saw -6 days and the 115-year-old guy

## Project Conclusions

1. Age doesn't affect No-show as much, but it appears that kids and elders are more likely to show on the appointment
2. Gender does not have any effect, but I found that more females are going to this appointment than males
3. It's more likely for the patient to No-show if there is a big gap between the day of registration and the day of the appointments
4. more SMS messages sent to absent patients doesn't seem to affect their attendance that much
5. Scholarship enrollment Doesn't affect the No-show phenomena but it appears that most of the dataset are covered by it
6. Having a disease doesn't appear to be the reason for the No-show phenomena