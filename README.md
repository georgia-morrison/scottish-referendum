# The Scottish Referendum Report

## Section 1 – The Scottish Referendum
### 1.1	– Introduction
### In 2014, Scotland held a referendum in order to determine whether or not Scotland should leave the UK and become an independent state. The data this report will be examines voting patterns based on a series of variables. This report will focus on comparing the percentage of people voting No against unemployment rates, national identity and age. Similarly, this report will compare the turnout of voters against the same three variables. The data in each case is categorised by Scottish Council Area.
  

### 1.2 - Voting Plots

<img width="248" alt="image" src="https://user-images.githubusercontent.com/87599176/133622393-51102d29-3b8c-435d-9ee3-f4cfe6a64488.png">|<img width="244" alt="image" src="https://user-images.githubusercontent.com/87599176/133622566-3696c24e-93cd-45fd-9afc-b98e0896f2c3.png">
:---------------:|:---------------:
|Figure 1: A scatter plot comparing the percentage of voters voting No in the Scottish Referendum against the unemployment rate. The size of the points is proportionate to the number of voters in the council area.|Figure 2: The sames scatterplot as Figure 1, however each point in respersented by the name of the council area the data shows.|

Figure 1 demonstrates that there is a negative correlation between the percentage of voters voting No and the unemployment rate of an area. It is a general trend that the lower the unemployment rate, the more voters are not in favour of Scottish Independence. Comparing this with Figure 2 we see a geographical pattern. Council areas in the Central Scotland have a higher percentage of voters voting No, with a few exceptions such as West Dumbartonshire, Glasgow and North Lanarkshire. As a result, in general, it can be seen that areas around Glasgow tend to have a higher unemployment rate, again with some exceptions as mentioned previously. Dundee is also an anomaly, although it is East coast it has high levels of deprivation.

<img width="277" alt="image" src="https://user-images.githubusercontent.com/87599176/133624129-6cb4c49e-883e-4851-9852-14888757cdeb.png">|<img width="253" alt="image" src="https://user-images.githubusercontent.com/87599176/133624236-488ad0a7-3959-4da8-a431-310b67afdb38.png">
:---------------:|:---------------:
Figure 3: Scatter plot comparing the percentage of voters voting No in the Scottish Referendum against the percentage of voters identifying as only Scottish. The size of the points is proportionate to the number of voters in the council area.|Figure 4: The same scatter plot as Figure 3, however each point is represented by the name of the council area the data shows.

Figure 3 shows a negative correlation between the percentage of voters against independence and the percentage of voters identifying as only Scottish. It appears those with a strong feeling of identity with Scotland rather than Britain have voted for Independence rather than against, whereas in areas where people don’t exclusively identify as Scottish, there is less of a preference for Independence. The geographical pattern is not as clearly defined as in the previous scenario, with the council areas in  
the same region being more spread over the graph. 

<img width="253" alt="image" src="https://user-images.githubusercontent.com/87599176/133632372-1e7fce35-1825-47ed-b9db-e95e5683fcae.png">|<img width="244" alt="image" src="https://user-images.githubusercontent.com/87599176/133632834-ab86d995-d358-4a58-a890-035b1da4768c.png">
:----------:|:----------:
Figure 5: A scatter plot comparing the percentage of voters voting No in the Scottish Referendum against the percentage of voters over 65 in that council area. The size of the points is proportionate to the number of voters in the council area.|Figure 6: The same scatter plot as Figure 5, however each point is repre represented by the name of the council area the data shows.represented by the name of the council area the data shows.

Unlike the previous graphs there is a positive correlation between the variables in Figure 5. The correlation is not as strong as the previous scenarios. The more voters over 65, the higher the percentage of votes against independence. It can be seen in Figure 6 that major Scottish cities - such as Aberdeen, Edinburgh and Glasgow – have less voters over the age of 65, whereas more remote areas like Orkney and the Borders have an older voter population.

### 1.3 - Turnout Plots
|<img width="202" alt="image" src="https://user-images.githubusercontent.com/87599176/133633777-628a9d89-b386-449f-b0a2-36287245a54c.png">|
:---------:
Figure 7: A scatterplot comparing the percentage of people voting in the Scottish Referendum against the unemployment rate in that council area. The size of the points is proportionate to the number of voters in the area.

In general, Figure 7 demonstrates that the unemployment rate has little impact on the voter turnout. Overall, across the country a high percentage of those eligible to vote chose to exercise their right to vote in each council area. The only outliers who had a significantly lower turnout than other areas were Glasgow at around 75% and Dundee at just below 80%.

<img width="226" alt="image" src="https://user-images.githubusercontent.com/87599176/133634073-8da174a9-59c3-42cf-af7e-9e6b01a1bcee.png">|<img width="217" alt="image" src="https://user-images.githubusercontent.com/87599176/133634141-f991e706-5ff7-409f-a232-62731d633dcf.png">
:-------:|:-------:
Figure 8: A scatterplot comparing the percentage of people voting in the Scottish Referendum against the percentage of voters identifying as Scottish only. The size of the points is proportionate to the number of voters in the area.|Figure 9: The same scatterplot as Figure 9 however the points are represented by the name of the council area the data shows.

Figure 8 shows an interesting pattern in this comparison, which is the voter turnout of those identifying as Scottish only. There is a weak, negative correlation in the top-right of the graph. We then see four outliers at the lower end of the graph. Geographically, from Figure 9 we see that these four outliers are all major cities in Scotland.

|<img width="218" alt="image" src="https://user-images.githubusercontent.com/87599176/133634735-6aa189ad-2233-418c-891e-d84339b4518c.png">|
:---------:
Figure 10: A scatterplot comparing the percentage of people voting in the Scottish Referendum against the percentage of voters over the age of 65 in that council area. The size of the points is proportionate to the number of voters in the area.

We can see form Figure 10 thst there is a positive correlation between the percentage of those exercising their right to vote and the percentage of voters over the age of 65. Overall, in areas with an older voting population, there was a high turnout of voters. We again see that Glasgow and Dundee are outliers at the lower end of the graph.

### 1.4 - Summary and Conclusions

In summary a variety of factors impacted on voter patterns in the Scottish Referendum. Looking at unemployment we see that areas with a high unemployment rate tend to be more in favour of Scottish independence. Similarly, those areas with a strong sense of Scottish identity, where high percentages of people are identifying themselves as Scottish only, had a high percentage of votes for Independence. Geographically, we saw that there was a larger number of local authorities in Central Scotland that returned a Yes vote compared to other parts of the country. Looking at the variable of age, we see that areas with an older voter population had more voters against Independence and a higher turnout of voters. It can be noted from the graphs that Glasgow had a significantly lower turnout compared to the other council areas.

---

## Learnings From This Project
The main aspects of R I learned in this project all relate to graph formatting. Being able to change the point size, and format (shape, text, etc.) has taught me how data can be made more accessable. This makes it easier for more variables to be analysed within one graph, without cluttering the visuals.
