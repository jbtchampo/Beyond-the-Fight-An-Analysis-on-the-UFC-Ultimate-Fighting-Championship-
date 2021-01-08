# Beyond the Fight: An Analysis on the UFC (Ultimate Fighting Championship)  

<p align="center">
  <img src="https://github.com/jbtchampo/Capstone-Project/blob/main/UFC_NewBeltInfoGraphic.jpg">
</p>



# Executive Summary

This project is an analysis of the UFC champions' (current and former)roster data and attempt to determine if there are any correlations or patterns between those athletes first and the likelihood for prospects, being fighters from other leagues that are likely to get a UFC contract and 2020 UFC newly drafted athletes, to win a World Championship. 
I looked at different associated factors such as fighters’ combat styles, and records pairing with outside data. I explored the top fighters having the best theoretical chance to win a world championship (or commonly called “Belt”). Given my knowledge of the recent history of this sport, I expected that there will be some inconsistency in data reporting from one website to another. Also, finding specific details on prospects (e.g., fighting stance) was going to be a challenge to overcome.


# Motivation

I chose this project as I have recently gained an appreciation and respect of the protocol put in place by the UFC to host their fights in the middle of the pandemic “COVID-19” while all the other major sports were on hold. Moreover, the UFC is one of the only major company that laid off less than 1% of their workforce and triple their revenue during this pandemic. Most importantly, I want to showcase the skills that all their different champions bring to the table. 
One of the more interesting aspects of this league is not only the risk associated with getting into a fist fight, but why specific athletes choose to join the “company”? as it is called and what are the underlying criteria that makes a champion? These are the questions that I want to answer!


# Data Question

Are there factors that can be used to determine the likelihood (or lack thereof) of a fighter winning the title? Do camps (or coaching staff) play an important role in grooming champions? Are there common trends between champions that could inform or help the UFC sign prolific prospects? 


# Data Sources

https://www.ufc.com/athletes (UFC Champions  stats)

http://ufcstats.com/statistics/fighters

http://rankingmma.com/top-50-mma-prospects/ - Webscraped list of top 50 MMA prospects from different MMA leagues

https://en.wikipedia.org/wiki/List_of_current_UFC_fighters  - Webscraped the list of UFC Champions & newlydrafted roster

https://www.sherdog.com/fighter/Jorge-Gonzalez-56318 - External data gathered for prospects (and newlydrafted statistics)

https://en.wikipedia.org/wiki/List_of_professional_MMA_training_camps' - Webscraped the list of Camps / coaches associated with current & previous UFC athletes

https://www.sportekz.com/list/highest-paid-ufc-fighters-2020/ 

https://www.sportekz.com/mma/bellator-245-salaries-purse-payouts/


# Tools leveraged

•	Excel: convert scraped data to CSV 

•	Python; scrape the data and EDA

•	Visual Studio Code; EDA, scratch pad

•	Jupyter Notebook; exploration and analysis

•	Tableau; visualize my findings


# Known Issues and Challenges

•	Scrapping the UFC website was nearly impossible. Therefore, I had to complement the data gathered from other websites scraped, such as wikipedia to match my results and confirm the accuracy of my dataset.

•	Changing formats so that the separate sources could be linked to one another via table joins. Essentially trying to format the data correctly so that tidy versions of the data could effectively be visualized in tableau. 

