# World-Happiness

Intro: I chose this to be my very first solo project because we currently face a mental health crisis around the world and I am looking to understand just exactly what are the most important factors that contribute to a country's overall happiness. I started by choosing this dataset as it had an abundance of countries to choose from as well as important variables that correlate heavily with an individual's well-being wherever they reside. I started by importing my dependencies and cleaning my dataframes to rid of any metrics that I was not interested in measuring for the project. I chose to use the .drop(columns=['']...) function to make my data frame concise. Following this, I decided to fix my decimals for my values in each respective variable I planned to incorporate by using the .round(decimals=2) at the end of my data frame function.

In order to get a preview with the statistics I would be analyzing I created multiple frames using the .groupby function comparing two or more metrics. I did a Region vs Happiness Score, Country vs Happiness Score, Happiness Rank vs Freedom score, Region vs Health (life expectancy), and a Happiness vs Govt Corruption score. I used these frames to see the top 10 of each region or country to see where they score in a general sense. 

Happiness Score
Using the groupby function, I was able to compile each country into their respective regions and determine which regions have the highest happiness scores. The ten regions ranked by their happines score are as follows.

1. Australia and New Zealand (7.32)
2. North America (7.10)
3. Western Europe (6.69)
4. Latin America and the Carribean (6.10)
5. Eastern Asia (5.62)
6. Middle East and Northern Africa (5.39)
7. Central and Eastern Europe (5.37)
8. Southeastern Asia (5.34) 
9. Southern Asia (4.56)
10. Sub Saharan Africa (4.14)

The top 10 happiest countries are
1. Denmark
2. Switzerland 
3. Norway 
4. Iceland 
5. Finland
6. Canada 
7. Netherlands
8. New Zealand
9. Australia
10. Sweden

The top 10 saddest countries are
1. Burundi
2. Syria
3. Togo
4. Afghanistan 
5. Benin 
6. Rwanda 
7. Guinea
8. Liberia
9. Tanzania
10. Madagascar 

