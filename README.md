# Data.2DII

## Overview

The 2° Investing Initiative (2DII) is an independent, non-profit think tank that coordinates some of the world’s largest research projects on sustainable finance.
Our research retail projects included data collection through surveys, focus groups, campaigns, among others. This package contains the raw data captured in those projects. 

## Installation

To install the package, first it is neccesary to install the package from Github: 
remotes::install_github("2DegreesInvesting/Data.2DII")

Then charge the library:
library(Data.2DII)

## Usage

Once you installed the package, you can upload the raw data calling it, as follow : 

|           Name        |                                                             Data information                                                     |N of participants | Countries | Year |
|----------------------:|----------------------------------------------------------------------------------------------------------------------------------|---| ---|---|
|EEI_2022               |This survey aimed to assess the retail investor demand and market potential for green/sustainable financial solutions in six EU countries. It is structured in 9 parts:A Interest in sustainable finance products, B Believes abouts sustainable finance products, C Sustainability objectives in relation to financial objectives, D Interst and preferences about voting , E+F Investments in and preferences for green financial products, G Interest in innovative green financial products (e.g. PE or infrastructure funds) , H Interest in green borrowing (e.g. green loans or energy performance contracts), I Sociodemographic profile |~6000| Belgium, Italy, the Netherlands, Poland, Spain, and Sweden. | 2022| 
|EEI_wealthgermany_2022 |The survey assess the private investor demand and market potential for green/sustainable financial solutions with a focus on wealthier people in Germany (with more than 250k euros in savings). It is structured in 9 parts: A Interest in sustainable finance products, B Believes abouts sustainable finance products, C Sustainability objectives in relation to financial objectives, D Interst and preferences about voting, E+F Investments in and preferences for green financial products, G Interest in innovative green financial products (e.g. PE or infrastructure funds) , H Interest in green borrowing (e.g. green loans or energy performance contracts), I Sociodemographic profile|~400 |Germany | 2022 |
|ESG_france_2021        |The survey aimed to retail investor sustainability preferences and their understanding of marketing claims. The survey is structured in 9 parts : A Sociodemographic information, B Financial information, C Sustainability profile, D Impact goals, E Evidence preferences, F Exclusion topics and scope, G Willigness for tradeoffs, H Misleading claims, I Believes about EEI/SEI products | ~1500 | France | 2021 | 
|Exclusion_Germany_2021 |The survey aimed to assess retail investor preferences about exclusion topics, i.e. most relevant exclusions, scope of exclusions (value chain and revenue thresholds) (results in German) | ~1000 | Germany | 2021 |
|Mystery_2022           |The focus of the this mystery shopping campaign was to assess the compliance with the new MiFID II regulation and broader sustainability motivations. We allocated 4 hypothetical investor profiles to the mystery shoppers including e.g. an impact-oriented green investor profile or a pure value-oriented investor profile. We assessed the following topics (please note that for duty of confidentiality we removed personal information of mystery shoppers and the bank name and recommended products):    - Explanation of sustainability preferences - Advisor knowledge and expertise - Identification of sustainability preferences - Financial product presentation/recommendation - Final conclusion of the meeting| ~250 | Denmark, Estonia, Germany, Greece, Ireland and Romania | 2022 - 2023 |
|Mystery_ESIP_2021      |The focus of the this mystery shopping campaign was to assess the compliance with the new MiFID II regulation and broader sustainability motivations. We allocated 6 hypothetical investor profiles to the mystery shoppers including e.g. Risk - averse, balanced and risk taker, and 2 groups per profile: want to invest green and agnostic. We assessed the following topics (please note that for duty of confidentiality we removed personal information of mystery shoppers and the bank name and recommended products):    - Explanation of sustainability preferences - Advisor knowledge and expertise - Identification of sustainability preferences - Financial product presentation/recommendation - Final conclusion of the meeting| ~199 | Denmark, Estonia, Ireland, Germany, Greece and Romania. | 2021 |
|Mystery_france_2021  |  The aim of this mystery shopping campaign was to find out how sustainability preferences are questioned by bank advisors and how they are handled once identified before the new MiFID II directive comes into force(please note that for duty of confidentiality we removed personal information of mystery shoppers and the bank name and recommended products)):- Sustainability assestment - Advisor knowledge and expertise - Identification of sustainability preferences - Conclusions. (Results in French) |  ~100 | France | 2021 | 
|Survey_ESIP_2021       |The survey assets to retail investors green consumer preferences. It containe: A. sociodemographic information, B. Believes, C. Sustainability objectives, D. Personal causes, E. Trade-offs, F. Green energy transition, G. Sustainability techniques, H. Applied sustainability techniques.| ~ 4000 | Germany, Greece, Estonia, Ireland, Romania and Denmark. | 2023 | 
|Mystery_EEI_2023       |The focus of the this mystery shopping campaign was to assess the compliance with the new MiFID II regulation and broader sustainability motivations. We allocated 2 hypothetical investor profiles to the mystery shoppers including. We assessed the following topics (please note that for duty of confidentiality we removed personal information of mystery shoppers and the bank name and recommended products):    - Explanation of sustainability preferences - Advisor knowledge and expertise - Identification of sustainability preferences - Financial product presentation/recommendation - Final conclusion of the meeting| 98 | Italy, Spain and The Netherlands + 8 visits for Sweden | 2023 |
sustainability_survey_2023 | The survey assets to understand the retail investors demand for sustainable finance products. It has 5 parts : A. Interest, B. Sustainable investing – General, C. Sustainability goals, D. Sustainability Preferences, E: Sociodemographic profile | ~2100 | Germany, Italy and The Netherlands. | 2023 |
Mystery_france_2023 | The focus of the this mystery shopping campaign was to assess the compliance with the new MiFID II regulation and broader sustainability motivations in France. (Results in French) | 64 | France | 2023 | 

## Documentation

The documentation of each dataset contains the metadata, with the description, usage, format, name variables and variables' description. 
