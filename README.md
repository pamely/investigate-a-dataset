# Investigate a dataset

## Project overview
This project aims to analyse a dataset and communicate findings using Pandas, Numpy and Matplotlib.

## Project specifications

- A note specifying which the dataset analyzed
- A statement of the question(s) posed
- A description of what is done to investigate those questions
- Documentation of any data wrangling done
- Summary statistics and plots communicating final results

## Introduction
In this project, we will be analyzing data associated with female breast cancer. In particular, we will be interested in finding trends between the number of breast cancer deaths, the number of breast cancer new cases, income per person (GDP per capita) and population growth in differents countries in 2006 and 2016. Below are the questions we will be exploring: 

- Have certain regions of the world been growing in breast cancer more than others ?
- How does income relate to breast cancer deaths ?
- How does income relate to breast cancer new cases ?
- How does population growth relate to breast cancer deaths ?
- How does population growth relate to breast cancer new cases ?
- Which country in West Africa recorded the most cases of breast cancer deaths in 2006 ?
- Which country in West Africa recorded the most cases of breast cancer deaths in 2016 ?
- What is the relationship between breast cancer deaths, income and population ?

The last question will summarize our findings. Therefore, it will help us draw conclusions from the whole analysis.

The datasets used in this project, have been downloaded from [Gapminder](https://www.gapminder.org/data/). 

## Conclusions
In the previous section, we explore our data. Indeed, we created visualizations regarding the research questions we have been addressing. In this section, we will be summarizing our findings and the results that have been performed.

> **Note:** The number of breast cancer deaths/new cases used for visualizations is greater than the average number of breast cancer deaths/new cases in 2006 and 2016. 
>
* **Have certain regions of the world been growing in breast cancer more than others ?**
  * After plotting the number of breast cancer deaths per country in 2006 and 2016, we notice that both of the plots have the quite same shape. Indeed, countries that represent 2006's plot spikes are the same on 2016's plot. These countries are: **Brazil, China, India, Japan, Paskistan, Russia, United States**. Nevertheless, we should note that, the number of breast cancers deaths significantly grow from 2006 to 2016. In fact, 2006's plot overlaps 2016 ones, especially on the spikes. However, the number of breast cancer deaths didn't increase much for countries like : Russia, Romania, Poland, South Africa. From this findings, it can be inferred that breast cancer is growing faster and more in some countries than others. <br/> <br/>
  * We notice that some countries are not on 2006 breast cancer deaths plot but are on 2016 one. These countries are: **Afganistan, Columbia, Congo Dem Rep, Iran, Iraq, Morocco, South Korea**. This is a proof that these countries grow in breast cancer more than others. <br/> <br/>
  * After visualizing the number of breast cancer new cases per country in 2006 and 2016, we can notice that its distribution is the same as breast cancer deaths. Indeed, coutries with high number of breast cancer deaths have a high number of new cases. It should also be noted that breast cancer new cases significantly increased in some countries from 2006 to 2016. Thus, this is growing more in some  countries than others. <br/> <br/>
  * We can notice that developed countries are most affected by breast cancer. It seems like there could exist some factors such as lifestyle or others can be favourable  to the growth of cancer. However, only the number of breast cancer deaths or new cases in countries don't allow to draw objective conclusion about that. <br/> <br/>
* **How does income relate to breast cancer deaths ?**
  * After plotting the proportion of breast cancer deaths in terms of countries income groups, we can observe that people from low and high income countries are more likely to die of breast cancer. It should be noted that breast cancer deaths are significantly higher in low income countries than others. This finding can bring us to the conclusion that there could exist a correlation between breast cancer the economic and social factor status of countries.  <br/> <br/>
* **How does income relate to breast cancer new cases ?**
  * Like breast cancer number of deaths, the proportion of breast cancer new cases are higher in low and high income countries more than others. Nevertheless, more in low income countries. Therefore, the economic situation of countries more specifacally the income per person (GDP per capita) may be favourable to breast cancer. Since the notion of economic status implicitly refers to the notion of social classes, we might wonder which class of people are more prone to breast cancer. This will open up gaps for further analysis. Indeed, much more interesting analyses could then be carried out taking into account other variables such as: the quality of the food consumed, environmental conditions, the quality of hospital infrastructure, etc.  <br/> <br/>  
* **How does population growth relate to breast cancer deaths ?**
  * After plotting the proportion of breast cancer deaths and population growth in terms of income groups, we can see on the hand that, low and high income countries have the highest number of population growth. On the other hand, countries with a high population growth have the highest breat cancer deaths. It can be inferred that it could have a corelation between breast cancer deaths and population growth.
* **How does population growth relate to breast cancer new cases ?** 
    * Like breast cancer deaths, we can see on the plot of breast cancer new cases and population growth proportion in terms of income groups that, low and high income countries have the highest population growth. On the other hand, countries with a high population growth have the highest number of breat cancer deaths. Popuation growth can be a key factor in breast cancer growth. We need more variables to be sure that there is a link between population growth and breast cancer, that is, variables which affect population growth and check if they are favorable for breast cancer or not. Nevetheless, since population growth imply new births, breast cancer is maybe hereditary. The analyses can therefore be further developed from this perspective.
* **Which country in West Africa record the highest number of breast cancer deaths in 2006 ?**
   * After plotting the number of breast cancer deaths in west african countries, we can observe that Nigeria has the highest record with more than 60% of cases recorded. Thus, Nigeria is the most affected west african country by breast cancer. 
* **Which country in West Africa record the highest number of breast cancer deaths in 2016 ?**
   * Like in 2006, we can observe that Nigeria still has the highest record of breast cancer deaths. Thus, Nigeria still is the most affected west african country by breast cancer. 
* **What is the relationship between breast cancer deaths, income and population ?** 
    * The questions underlying our analysis are intended to allow us to see the relationship between breast cancer,  the income per person (GDP per capita) of certain countries and their population growth. These counries are the  most affected by breast cancer since their death rate and new registered cases are above the average number of all countries taken into account in our work.  Our analysis showed us that poor and very rich countries are more affected by breast cancer. More precisely, countries with very low income per citizen on the one hand and those with a relatively high income per citizen on the other. These countries are experiencing a considerable demographic boom, especially in poor countries. It could therefore be said that the demographics and economic situation of these countries are very favourable to breast cancer growth. However, we do not have more information to ensure that these assumptions are verified. Nevertheless, our analysis allows us to have an interesting orientation to have much more interesting results. Data could therefore be collected according to variables that affect the economies of these countries and their demographics. These variables must also take into account their socio-cultural aspects. For example, when we take food, it has socio-cultural origins. But it can be an important factor in explaining the origins of breast cancer. 

## Limitations
There are not all the world's countries in our dataset. For instance, the **United Kingdom Overseas Territory of Saint Helena, Ascension and Tristan da Cunha** is not in the dataset. However, it is a west african country. So, the analysis we made did not take into account some countries.

## Useful links
[Gapminder](https://www.gapminder.org/data/)

[World bank: The classification of countries by income](http://datatopics.worldbank.org/world-development-indicators/stories/the-classification-of-countries-by-income.html)

[World development indicators: Gross national income](http://datatopics.worldbank.org/world-development-indicators/themes/economy.html#gross-national-income)

[West Africa countries](https://en.wikipedia.org/wiki/West_Africa)
