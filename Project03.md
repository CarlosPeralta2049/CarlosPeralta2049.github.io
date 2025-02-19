**Objective:** Initially, texplore the effects of tariffs on economies. Consequently, to simulate the effects of a 10% tariff reduction on EU food imports from the US.

## Trade Barriers: International Trade and Tariffs
**Scenario 01. Market Equilibrium for avocados without international trade:**
If the equilibrium price of avocados is $250 the total quantity for avocados is 25 tones. Consumer surplus is found below the demand curve and above equilibrium price (250 * 25 * 0.5 = $3,125). Producer surplus is found above the supply curve and below the equilibrium price (250 * 25 * 0.5 = $3,125). **This example is shown below, on the left.**<br><br>
<img src="https://CarlosPeralta2049.github.io/Assets/Project03_01.jpg" alt="Sample Image" width="245" height="200">
<img src="https://CarlosPeralta2049.github.io/Assets/Project03_02.jpg" alt="Sample Image" width="245" height="200"><br><br>
**Scenario 02. Market Equilibrium for avocados under free trade:** 
When consumption (blue) is 40 (domestic demand) and Production (orange) is 10 (domestic supply), the price (per ton) is $100 and trade volume is 30 tons imported. Consumer surplus (blue) is found below the demand curve, above world price (Pw) and this is the height (500-100 = $400) * the base (40) * .5 = $8,000. Producer surplus (orange) is found above the supply curve, below world price, and it is the height ($100) * the base (10) * .5 = $500. **This example is shown above, on the right.**
<br>

**Scenario 03. Market Equilibrium for avocados including a $100 tariff:**
When consumption is 30 and production is 20, price = $200 and trade volume is 10 tones imported. Consumer surplus is the height (500 – 200 = 300) * base (30) * .5 = $4,500, and it has reduced to $3,500 ($8,000 - $4,500). Producer surplus is the height (200) * base (20) * .5 = $2,000, and it has decreased to $1,500 ($2,000 - $500). A new deadweight loss results from the tariff and it is made up of the following areas. The consumption effect (area D), which is the height (100) * base (40-30=10) * .5 = $500. The protective effect (area B), which is the height (100) * base (20-10) * .5 = $500. The redistributive effect of government revenue (area C). The total deadweight wellfare loss imposed on the economy is $1,000 (areas D + B). <br>**This example is shown below.**
<br><br>
![Image1](https://CarlosPeralta2049.github.io/Assets/Project03_03.jpg)<br><br>
<br>
## Sensitivity Analysis: International Trade and Tariffs
This analysis identifies the consequences of reductions of EU food import tariffs from the US by 0%, 10%, 100%. It simulates these shocks in food, manufacturing, and service sectors while adjusting varying levels of trade barriers to highlight trade liberalisation Consequences. The primary objective is to identify the implications of tariff reductions, and the secondary objective is to highlight historical economic correlations related to trade liberalisation efforts. 
<br><br>
To assess the implications of the primary objective, RunGTAP v3.75 is utilised. This is a visual user interface program that enables simulations which utilise GEMPACK (General Equilibrium Modelling Package), a suite of economic modelling software that runs computable general equilibrium models. Here, an experiment was set up to run the simulation of a 10% tariff reduction on United States food exports to the European Union. Settings were changed to the Gragg Solution Method using 3 solutions with solution steps 2-4-6. Automatic Accuracy setting was also selected to improve accuracy. The code ‘Shock tms("food","usa","eu")= -10 ;’ was placed in the shock tab to replicate the tariff reduction shock. Likewise, coding was added to create results with and without trade barriers.<br><br>
![Image2](https://CarlosPeralta2049.github.io/Assets/Project03_04.jpg)<br><br>

**Simulaton Results:** 
Consider that Terms of Trade (ToT) identifies if an economy is moving towards a trade surplus, increasing GDP. A ToT increase implies that the value of X can buy more than before and a ToT decrease implies the opposite. The simulation findings were as follows:<br>
Trade Balance (U.S.): Tariffs↑ turns the U.S. into importer at every tariff↓.<br>
Trade Balance (EU): Tariffs↓ makes exports ↑ then ↑.<br>
Trade Balance (RestOfWorld): Tariffs↓ makes exports↓ then ↑.<br>
Terms of Trade (U.S.): Tariffs↓ makes terms of trade↑ at every tariff↓.<br>
Terms of Trade (EU): Tariffs↓ makes terms of trade↓ at every tariff↓.<br>
Terms of Trade (ROW): Tariffs↓ makes terms of trade↓ at every tariff↓.<br>
Value of World Trade: With respect to overall trade, as tariffs↓, total trade↑.<br><br>
![Image3](https://CarlosPeralta2049.github.io/Assets/Project03_05.jpg)<br>
![Image4](https://CarlosPeralta2049.github.io/Assets/Project03_06.jpg)<br>

**Primary Objective Conclusion:**
The U.S. gains the most, and consistently from tariff reductions on its exports. World trade gains with a 49.1% increase as U.S. export tariffs are removed. Generally, a 10% tariff cut is the most beneficial combination for the world. However, these simulations give the results of a snapshot in time. Large countries like the U.S. can potentially benefit from tariffs. However, as they place tariffs retaliation and trade wars may rise.

RunGTAP software has a few drawbacks. The first is that simulations combine sectors into only three groups which are Food, Manufacturing, and Services. This does not allow for drill-through analysis within each sector. Secondly, it is updated in three-year cycles and data may not be accurate to the year. Thirdly, it is limited to static data which reflects a particular year and may not predict that similar change will continue to occur year on year. 

As part of the secondary objective and to overcome the limits of static data Microsoft Power Business Intelligence (BI) software is utilised with a dynamic data. Datasets were extracted from Macrotrends.net (sourced from datatopics.worldbank.org). Relating to economic correlations and the importance of trade liberalization efforts, this analysis here highlights a relationship between Trade as a Percentage of GDP and GDP from 1971 to 2022. The statistical relationship between the variables interpreted that the direction was positive, and its coefficient identifies that the strength of the relationship between the variables was very strong. The coefficient measures relationships with values between –1 and 1. -1 describes that there is a strong negative relationship between the variables, and 1 confirms that there is a strong relationship, and here the coefficient is 0.94.<br>
![Image4](https://CarlosPeralta2049.github.io/Assets/Project03_07.jpg)<br><br>

**Secondary Objective Conclusion:**
This analysis finds that an increase in the European Union’s balance of trade is very likely to increase Gross Domestic Product, resulting with greater economic over time.<br>

