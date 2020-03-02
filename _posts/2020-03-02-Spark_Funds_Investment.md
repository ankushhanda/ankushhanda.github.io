---
title: "Case Study: Spark Funds Investment"
date: 2020-03-01
excerpt: Machine Learning
categories:
  - Machine Learning
tags:
  - Machine Learning
  - Data Science
header:
 image: "/images/unsplash-image-3.jpg"
---


## Scenario

Spark Funds is an asset management company. It wants to make investments in a few companies. The CEO of Spark Funds wants to understand the global trends in investments so that she can take the investment decisions effectively.

Spark Funds has few minor constraints for investments:
- It wants to invest between 5 to 15 million USD per round of investment
- It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in.
- It wants to choose one investment type from the 4 major types (Seed, Angel, Venture, Private Equity) for each potential investment they make.

What is the strategy?

Spark Funds wants to invest where most other investors are investing. This pattern is often observed among early stage startup investors.

Where did we get the data from?

We have taken real investment data from crunchbase.com.

### Datasets:

Name: companies.csv
Desc: A table with basic data of companies (Company details)

Name: rounds2.csv
Desc: Contains details about companies funding per round.

Name: mapping.csv
Desc: This file maps the numerous category names in the companies table (such 3D printing, aerospace, agriculture, etc.) to eight broad sector names. The purpose is to simplify the analysis into eight sector buckets, rather than trying to analyse hundreds of them.

### Business objective

The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.



You can check the code and dataset at [link](https://github.com/ankushhanda/data-science/blob/master/Spark_Funds_investment)