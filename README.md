# Stoccer!
FinTech Project: Valentina Buritica, Jeff Berger, Aidan Dowdle, &amp; Aaron Devaney<br>

## Introduction 

Stoccer is the comparison of investing in ownership of a soccer team vs investing<br>
through normal conventions. We decided that the acquisition of the Paris Saint German (PSG)<br>
football team by the Emir of Qatar would be the ideal case study to show the true<br>
ROI post acquisition as well as the upfront and continuous reinvestment costs of having a<br>
successful team. As background, European Football's free agency market operates<br>
differently than the big four sports in the US. It is structured similarly to that of<br>
the stock market where each individual player functions similarly to a firm listed on<br>
the NYSE. The value of each player is determined based off of their performance on<br>
the pitch and the additional endorsements, sales of merchandise and added ticket value<br>
that they could bring to the club. Since this is a free market across all European<br>
Leagues, clubs compete with each other for the acquisition of new players. This does<br>
lead to parity in the leagues with respect to teams who have more capital to spend.<br>
Through this case study, we will provide a breakdown of where transfers are coming from,<br>
analysis the top performing teams in Europe regarding their transfer spending and<br>
team statistics, analysis on the effective spending of PSG specifically and an overall<br>
comparison of the investment by the Emir against the stock market.

## Overview of European Soccer Transfer Market 
#### Top 20 Teams in the 2013-2014 Season 

We began our project knowing that we wanted to concentrate on the European soccer market. <br>
That said, given the amount of data we gathered and our time constraints we decided to focus our <br>
analysis on the Top 20 Teams in the 2013-2014 season. <br>

We selected the top 4 teams of the French League, English League, Spanish League, Italian League <br>
and the German League. These teams are the following: <br>

Paris Saint-Germain F.C., Lyon, Monaco, Marseille, <br>
Manchester United, Manchester City, Arsenal, Chelsea, <br>
Barcelona, Real Madrid, Atletico Madrid, Valencia, <br>
Juventus, Roma, Lazio, Fiorentina, <br>
Bayern Munich, VfL Wolfsburg, M’ Gladbach, Bayer. 

Below we created an interactive plot that has a “hover” feature which allows the end user to use their mouse <br>
to locate each team selected based on their stadium location. 

![top_20_teams](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/Top_20_Teams.png)

### Transfer Market in the 2013-2014 Season 

In addition, we wanted to create a visualization that would allow the end user to understand how busy the transfer <br>
player market is during any given season. With this in mind we used Folium a Python library and GeoPandas to create a map <br>
with lines representing the player transferred between teams. 

![transfer_market](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/Transfer_Market.png)

Please Note: For both of the visualizations above the following color code was utilized: <br>
Red = French League <br>
Blue = English League <br>
Orange = Spanish League <br>
Purple = German League <br>

##  Team Data 
A central question to analyze how the team performed is to judge it's peformance against<br>
its competitors and metrics set forward by the league.  PSG has over performed its competitors<br> 
since 2011. 2011 marked the first year after ownership of PSG changed hands and large scale<br> 
investment in the transfer market began.  Looking at the data, you can see a consistent and<br> 
accelerating uptick in the number of points that PSG is winning.  Interestingly, PSG peers<br> 
seem to have up and down seasons where PSG has been able to maintain a steady top level of<br> 
performance.<br>

![total_points](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/total_points.png)

Across European Soccer leagues, the winner of a given league is the team that collects the<br>
most points after playing a season (38 games) against its competitors. Three points are<br> 
awarded for a wine, one point for a draw, and none for a defeat, with the team with the most<br>
ponts at the end of the season winning the league title. Using the 2013-2014 top 4 finishers<br>
as a becnhmark across five leagues, the below graph is PSG’s total points versus the top 4<br> 
competitors in each of the English, French, Spanish, German and Italian leagues.<br>

![team_wins](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/team_wins.png)


Goal differential data is an important indicator of how well a team is performing. A team<br> 
that is able to limit its opponent's goals by having strong defense and goalkeeping that<br> 
is also able to pass and score more effectively have a significantly better chance of winning<br>
more games, and drawing more games against close competitors. Generally, PSG is winning it’s<br>
games by a lot larger margins than what its peers are doing. This demonstrates that the team<br> 
that the team that PSG has put together is significantly more competitive and productive than<br> 
the rest.<br>

![goal_differential](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/goal_differential.png)

## Analysis of Paris Saint-Germain Soccer Club as an Investment
In 2011, Tamim bin Hamad Al Thani, ruler of Qatar, purchased the Paris Saint-Germain soccer club for an undisclosed sum. The club was estimated to be worth $105 million at the time, so for the purposes of our project, we used that fair market price as the likely price that Al Thani paid.  Forbes Magazine publishes a list of the most valuable soccer club and Paris Saint-Germain appeared on that list from 2013 to 2019 so we were able to get the value of the club for that period of time. We also found data that showed the transfer fees paid by Paris Saint-Germain over our time frame.

Using the initial investment and the transfer fees paid by the club to bring in new players, we calculated the total investment in the club over the course of nine years. Using the Forbes Magazine data, we were able to calculate the value generated by their overall investment. We decided to compare what would have happened if Al Thani had used his initial investment to purchase certain stocks, and then instead of paying transfer fees, he made additional investments in that same stock. We pulled historical closing prices for the following stocks to use in our comparison:

 -AAPL
 -AMZN
 -NFLX
 -GOOG

 As you can see, an investment in any of the stocks listed above would have produced a vastly greater return on investment purely in terms of value. Given the difference, it appears that as an investment, Al Thani should have picked one of the listed stocks rather than investing in a soccer club. Please note that this analysis does not include income such as revenue generated from the soccer club or dividends paid by the stocks and it does not include intangibles such as prestige, which could change the analysis for certain investors. 

 ![psg_v_stock](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/psg_v_stock.png)

## Analysis of the Correlation Between Paying for Transfers and Generating Revenue
We used data from a list produced by Deloitte that lists the European soccer clubs with the most revenue. We sampled teams from the French, German, English, Italian and Spanish leagues, namely Paris Saint-Germain, FC Schalke 04, Chelsea, AC Milan and Real Madrid. It appears that revenue generated from soccer clubs has been uniformly increasing, which may distort the correlation. There does, however, appear to be some correlation between spikes in spending and increases in revenue, especially in our focus team, Paris Saint-Germain, which increased its spending in 2017 and experienced a revenue spike in 2018. Overall, the results are inconclusive for whether or not a soccer club can dramatically increase its solely through the transfer market.

![psg_rev](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/psg_rev.png)

![real_madrid_rev](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/real_madrid_rev.png)

![chelsea_rev](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/chelsea_rev.png)

![milan_rev](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/milan_rev.png)

![schalke_rev](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/schalke_rev.png)


## How does PSG stack up statistically with other top teams?

As the Emir invested and brought in players, the overall output increased to the levels of top performing teams<br>
and outperformed them in certain statistical categories. In 2018, PSG significantly outperformed top teams in<br>
goals averaged per 90 minutes played and this number trended consistently upward since the acquisition. However,<br>
assists per 90 stayed relatively stagnant in comparison. This may be an indication of a need for additional investment<br>
in playmakers rather than goal scorers. As a note, the data tails off due to stoppage of play as a result of the<br>
COVID-19 Pandemic.

### Goals Per 90 Minutes Played
![top_team_comparison_gls_per_90](png_file/top_team_comparison_gls_per_90.PNG)

### Assists Per 90 Minutes Played
![top_team_comparison_ast_per_90](png_file/top_team_comparison_ast_per_90.PNG)

### Total Goals Scored
![top_team_comparison_gls](png_file/top_team_comparison_gls.PNG)

### Total Assists
![top_team_comparison_ast](png_file/top_team_comparison_ast.PNG)

## Does buying the big-name player bring a large ROI?

The short answer is not necessarily. After looking at the production levels of midfield and forward position players,<br>
it was determined that some of the most expensive players were not actually worth the price paid in terms of production<br>
on the field. Neymar is the perfect example of a player that came with a high price tag but has not been as productive in<br>
his tenure at PSG. Zlatan Ibrahimović was acquired for a much lower fee and had a higher rate of production. However,<br>
acquiring the big-name player does put fans in the stands and bring media attention to the club. This does need to be<br>
factored into the ROI of a player that is being considered for acquisition. 

![midfield_vs_forward_cost](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/midfield_vs_forward_cost.png)

![midfield_vs_forward_prod](https://github.com/dowdlea86/project_one_submission/blob/main/png_file/midfield_vs_forward_prod.png)


#### File Preview:

psg_vs_market_dashboard: code file that includes dashboard presentation of information<br>
analysis_notebook_alpaca_api: file where alpaca API used for stock analysis<br>
Top_4_teams.ipynb: interavtive map that uses “folium” to show team locations on map<br>
Project One: copy of presentation<br>


