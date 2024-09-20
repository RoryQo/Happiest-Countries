# Happiest-Countries

#### Results
After viewing the correlogram, we can see the data is highly correlated; because of this, we continue with Principal component analysis. We then create clusters from the PCA to determine the happiest countries. From our plot, we can see that 3 is the optimal number of clusters, and from these clusters, we can see that the PAM clustering is equivalent to k means clustering as there is a difference of only 2 out of over 150 countries.

After we separated the countries into clusters, we created data visualizations factored by cluster, with some of the top contributors from the PCA (GDP/capita, and Social Support. These visualizations show that cluster 1 is consistently (and statistically significantly) better off than the other 2. The countries in this cluster are the ones that are the happiest. Cluster 1 has 25 countries in it, a full list of these countries is displayed on the last page.

#### Data
The World Happiness Report is a landmark survey of the state of global happiness. The first report was published in 2012. We will explore the 2018 data.

+ `Overall rank:` Happiness rank; numeric. Range: 1 to 156
+ `Country or region:` Character. 156 values
+ `Score:` or subjective well-being; numeric. Range: 0 to 10
+ `GDP per capita`
+ `Social support`: the national average of the binary responses (either 0 or 1) to the GWP question “If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?”
+ `Healthy life expectancy`
+ `Freedom to make life choices:` the national average of responses to the GWP question “Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”
+ `Generosity:` the residual of regressing national average of response to the GWP question “Have you donated money to a charity in the past month?” on GDP per capita.
+ `Perceptions of corruption:` the national average of the survey responses to two questions in the GWP: “Is corruption widespread throughout the government or not” and “Is corruption widespread within businesses or not?”
