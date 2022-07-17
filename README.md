# Cyclistic-Bike-Share Chicago
Google Data Analytics capstone project
Author : Millicent Ofobuike
Data Date: April 2020 - March 2021.

### Introduction

In 2016, Cyclistic launched a successful bike-share offering. Since then,
the program has grown to a fleet of 5,824 bicycles that are geotracked and
locked into a network of 692 stations across Chicago. The bikes can be unlocked
from one station and returned to any other station in the system anytime.
Until now, Cyclistic’s marketing strategy relied on building general awareness
and appealing to broad consumer segments.One approach that helped make these
things possible was the flexibility of its pricing plans: single-ride passes,
full-day passes,and annual memberships. Customers who purchase single-ride or
full-day passes are referred to as casual riders. Customers who purchase annual
memberships are Cyclistic members.
Cyclistic’s finance analysts have concluded that annual members are much more
profitable than casual riders. Although the pricing flexibility helps Cyclistic
attract more customers, Moreno believes that maximizing the number of annual
members will be key to future growth. Rather than creating a marketing campaign
that targets all-new customers, Moreno believes there is a very good chance to
convert casual riders into members. She notes that casual riders are already
aware of the Cyclistic program and have chosen Cyclistic for their mobility
needs.
Moreno, the director of marketing, has set a clear goal: Design marketing
strategies aimed at converting casual riders into annual members. In order to
do that, however, the marketing analyst team needs to better understand how
annual members and casual riders differ, why casual riders would buy a
membership, and how digital media could affect their marketing tactics. Moreno
and her team are interested in analyzing the Cyclistic historical bike trip data
to identify trends.

As a junior data analyst working in the marketing analyst team at Cyclistic,
The director of marketing, Moreno, believes the company’s future success depends
on maximizing the number of annual memberships. Therefore,the team wants to
understand how casual riders and annual members use Cyclistic bikes differently.
From these insights, the team will design a new marketing strategy to convert
casual riders into annual members.

#### **Business** **Task**

How do annual members and casual riders use Cyclistic bikes differently?
Use Cyclistic’s historical trip data to analyze and identify trends.

#### **Key** **Stakeholders**

      Lily Moreno
      Cyclistic marketing analytics team
      Cyclistic executive team

#### **Data** **Background**

The data is a public data made available by Motivate International Inc. under this 
license (https://www.divvybikes.com/data-license-agreement). For the sake of 
privacy, riders personal identifiable information were not included.This is a
link to the dataset: (https://divvy-tripdata.s3.amazonaws.com/index.html).

I downloaded the previous 12 months of Cyclistic trip data (April 2020-March 2021).
I unzipped and created a folder in my desktop to house the files.

R was chosen to analyze the data due to the size of the dataframe.

To import and analyze the dataframes, I installed and loaded readr,tidyverse,
lubridate,dplyr packages.

```{r}
library(readr)
library(tidyverse)
library(lubridate)
library(dplyr)
```
