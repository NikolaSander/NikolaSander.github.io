---
title: Estimating the Lone Spaniard
author: Nikola Sander
layout: post
permalink: /lone-spaniard
tags:
  - flow data estimation
  - opendata
  - The Global Flow of People
---

In a paper published in [Science](http://www.sciencemag.org/content/343/6178/1520) on March 28, Guy Abel and I present a new methodology for estimating bilateral migration flows between 196 countries from United Nations [migrant stock data](http://esa.un.org/unmigration/TIMSO2013/migrantstocks2013.htm). We are absolutely flabbergasted by all the (social) media attention and positive feedback we are getting! When exploring our interactive visualisation of [The Global Flow of People](http://www.global-migration.info), you might come across a number that makes you think *Huh? That can't be right!*

<figure>
    <a href="/images/lone-spaniard.jpg"><img src="/images/lone-spaniard.jpg"></a>
</figure>

The *Lone Spaniard*, first uncovered by [Leo @ Null2 Berlin](https://twitter.com/Null2Berlin), is likely to cause such a reaction. Why on earth would we estimate the total outflow from Spain to be just 1 in the period 2000 to 2005? We all know from looking at existing flow data published by the UN and Eurostat, that people are constantly migrating! The reasons why we estimate such a small number lie in the way we define migration and in the UN migrant stock data that our estimates are based upon.
<br>
<br>
We define migration as the number of people who changed their country of residence over 5-year periods. In contrast, existing flow data define migration as the number of moves that people make in a year. The figure above illustrates how our estimates only capture *one* move per person over 5 years, while all other moves people make; and that are captured by existing flow statistics are just shadows in our estimates. Our data are not per se less accurate, our methodology of linking stocks to flows just requires a different definition of migration. The big advantage of our data is, of course, that we can directly compare the sizes of flows across 196 countries, something that hasn't been possible so far.
<br>
<br>
Besides capturing only one move over 5 years, our model also estimated the Lone Spaniard because the stock data for Spain changed in very unusual ways between 2000 and 2005. Normally, we estimate an outflow from a given country because the stocks tell us that the number of people living overseas increased. In addition, our model estimates an outflow of people returning home if the number of foreigners in the country decreases. The Lone Spaniard was caused by no increase in the Spanish population living overseas, and no decrease in the number of foreigners living in Spain. Instead, we saw a strong increase in foreigners, causing a massive immigration wave (which, of course, melt into thin air in the last few years because of the economic crisis).
<br>
<br>
The Lone Spaniard really illustrates how our estimates are different from existing flow data. Our focus has not been on estimating the *true* flow for every country in the world. Instead, we present the first ever estimates of migration flows that can be compared across countries and that allow a truly global perspective. Having said that, we are very much aware that this is only a first step, and that both the quality of the underlying stock data and our methodology can be improved.
<br>
<br>
If you want to learn more about the (statistical) details of our methodology, please take a look at the supplementary materials of our Science paper ([Accepted Version](/images/Abel_Sander2014.pdf)).
