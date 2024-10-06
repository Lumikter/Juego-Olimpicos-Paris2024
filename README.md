![Olimpic Games Paris 2024](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/OlimpicGamesParis2024.PNG)

## Objective

Develop a comprehensive analysis of the Paris 2024 Olympic Games through data visualizations that highlight the most 
successful countries and sports, as well as analyze the demographic distribution of athletes by age and gender.
The objective is to provide key insights into performance and global trends in the competition,
enabling strategic decision-making for future sports investments, inclusion policies, and talent development programs.

## Tools

1. Power Query.
2. Data Modeling.
3. Visualization.
4. Matplotlib.
5. Seaborn.

## Structure

**1. Cover Page/General Summary:**

- Project title: Paris 2024 Olympic Games.
- Summary with key metrics: number of sports, events, participating countries, and the percentage of countries that won medals.
- Performance indicators: Athlete success probability and average sports success index by country.
    
**2. Geographic Distribution and Medal Tally:**

- Medal map by country showing the distribution of gold, silver, and bronze medals.
- Ranking of the top 10 medal-winning countries, showing the accumulation of medals by type (gold, silver, bronze).
- Ranking of the top 10 sports with the most medals, showing the distribution and cumulative percentage.

**3. Athlete Demographics:**

- Distribution of athletes by age, segmented into adolescents, young adults, adults, and older adults.
- Medal distribution by age, showing the relationship between age and the type of medal won.

**4. Gender and Educational Level Analysis:**

- Distribution of athletes by gender and educational level, identifying patterns in male and female participation.
    
**5. Medals by Continent and Sport:**

- Distribution of medals by continent and sport in a heatmap, identifying concentrations of sporting success in specific regions.
    
**6. Success Index by Country and Main Physical Requirement:**

- Analysis of sports success indexes by country.
- Comparison of the main physical skills required by different sports (agility, strength, precision).

## Data Analysis

**1. Tittle and Main Indicators:**

![Tittle](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Tittle.png)

**2. Summary Indicators for Medals and Athletes:**

**- Medals by country:** Displays the total medals divided into gold, silver, and bronze.

**- Medals by athlete:** Details the number of athletes who have won medals in various categories, providing insights into the success rate per participant.

**- Participating athletes:** Indicates the total number of athletes, with additional details such as minimum, maximum, and average age, offering a demographic overview of the competitors.

![Summary Indicators for Medals and Athletes](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Summary%20Indicators%20for%20Medals%20and%20Athletes.png)

**3. Athlete Success Probability:**

A gauge-type chart that represents the percentage of athletes likely to succeed (medal winners) compared to all participants. This indicator gives a general idea of individual competition and difficulty.

![Athlete Success Probability](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Athlete%20Success%20Probability.png)

**4. Country Success Probability:**

A gauge-type chart that represents the percentage of country likely to succeed (medal winners) compared to all participants. This indicator gives a general idea of individual competition and difficulty.

![Country Success Probability](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Country%20All%20Sport%20Success%20Index.png)

**5. Geographical Medal Distribution Map:**

This map uses a color scheme to represent the distribution of medals won by country. Countries are colored according to their performance, allowing for a quick visual comparison of Olympic success across regions.

Red for the most winner, Blue for the worst and White for Countries wich weren't won or participate.

![Geographical Medal Distribution Map](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Geographical%20Medal%20Distribution%20Map.png)

**6. Country Sports Success Index:**

Represented by colored bars, this index ranks countries based on their success in terms of medals won relative to their participation. A "final ranking" is also included to reflect the cumulative performance.

That visualization reflect that the quantity of medals is not related with index success sport, if the ranking will be orderer for the last indicator we could see some changes like the first 5 places.

| Country | Ranking by Success | Index |
| ----------- | ----------- | ----------- |
| USA | 1 | 0.55 |
| Kenia | 2 | 0.46 |
| China | 3 | 0.44 |
| Saint Lucia | 4 | 0.40 |
| Korea | 5 | 0.38 |

<p align="center">
  <img src="https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Country%20Sports%20Success%20Index%201.png" alt="Country Sports Success Index1" height="500px">
  <img src="https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Country%20Sports%20Success%20Index%202.png" alt="Country Sports Success Index2" height="500px">
</p>

**7. Top 10 Medal-Winning Countries:**

A stacked bar chart showing the total medals (gold, silver, and bronze) for the top 10 most successful countries, with an analysis of the cumulative percentage of each medal type, offering a clear view of dominant nations concentring the 56% of total medals avaible.

![Top 10 Medal-Winning Countries](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Top%2010%20Medal-Winning%20Countries.png)

**6. Medals by Sport Ranking:**

Similar to the country ranking but applied to sports, showing which disciplines were the most awarded. Each bar indicates the type of medal and its percentage, allowing for an evaluation of each sport's success.

Maybe the countries wich want to win more medals will must concentraite their effors in develop this kind of disciplines to increase the sport index success.

![Medals by Sport Ranking](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Medals%20by%20Sport%20Ranking.png)

**8. Athlete Age Distribution:**

A histogram that segments athletes into four age groups (Teenagers, Young Adults, Middle-Aged Adults, and Older Adults). This chart provides a clear view of the age profile of competitors.

![Athlete Age Distribution](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Athlete%20Age%20Distribution.png)

**9. Medals by Age Distribution:**

Using a scatter plot, this chart analyzes the relationship between athlete age and medals won. Different colors represent medal types and age groups, highlighting the most successful age ranges.

![Medals by Age Distribution](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Medals%20by%20Age%20Distribution.png)

**10. Athletes by Gender and Education Level:**

A horizontal bar chart comparing the number of male and female medalists, with an additional breakdown between athletes with or without advanced educational backgrounds, providing a socio-educational perspective of the Olympic sport.

![Athletes by Gender and Education Level](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Athletes%20by%20Gender%20and%20Education%20Level.png)

**11. Medals by Continent and Sport Distribution:**

A heatmap crossing information between continents and sports to identify patterns of success. Darker colors indicate a higher number of medals, facilitating comparison between regions.

![Medals by Continent and Sport Distribution](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Medals%20by%20Continent%20and%20Sport%20Distribution.png)

**12. Sports Success Index by Main Physical Demand:**

A radar chart that categorizes sports based on their main physical demand (agility, precision, strength), helping to interpret which skills are more crucial for achieving success in the Olympic Games.

![Sports Success Index by Main Physical Demand](https://github.com/Lumikter/Paris-2024-Olimpic-Games/blob/main/Visualizations/Sports%20Success%20Index%20by%20Main%20Physical%20Demand.png)

## Conclusion

One of the most prominent conclusions is the ongoing dominance of traditional powerhouses like the United States and China in the medal standings. However, there is also a rising representation from emerging nations in less infrastructure-dependent sports. The demographic analysis shows that most of the winners fall into the 20-30 age bracket, highlighting this period as the peak for athletic performance. Moreover, there's a noticeable increase in female representation, although a slight gender gap remains in favor of male athletes.

The analysis by continent and sport emphasizes geographical specializations: Europe excels in precision and endurance sports, while Africa shines in athletics. This indicates a strong connection between geography, investment, and tradition in sports. Additionally, countries with fewer resources tend to focus on more accessible disciplines, such as boxing and wrestling.
