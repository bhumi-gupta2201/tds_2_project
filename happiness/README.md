# Automated Data Analysis
## Analysis of happiness.csv
### Summary Statistics
              year  Life Ladder  Log GDP per capita  Social support  Healthy life expectancy at birth  Freedom to make life choices   Generosity  Perceptions of corruption  Positive affect  Negative affect
count  2363.000000  2363.000000         2335.000000     2350.000000                       2300.000000                   2327.000000  2282.000000                2238.000000      2339.000000      2347.000000
mean   2014.763860     5.483566            9.399671        0.809369                         63.401828                      0.750282     0.000098                   0.743971         0.651882         0.273151
std       5.059436     1.125522            1.152069        0.121212                          6.842644                      0.139357     0.161388                   0.184865         0.106240         0.087131
min    2005.000000     1.281000            5.527000        0.228000                          6.720000                      0.228000    -0.340000                   0.035000         0.179000         0.083000
25%    2011.000000     4.647000            8.506500        0.744000                         59.195000                      0.661000    -0.112000                   0.687000         0.572000         0.209000
50%    2015.000000     5.449000            9.503000        0.834500                         65.100000                      0.771000    -0.022000                   0.798500         0.663000         0.262000
75%    2019.000000     6.323500           10.392500        0.904000                         68.552500                      0.862000     0.093750                   0.867750         0.737000         0.326000
max    2023.000000     8.019000           11.676000        0.987000                         74.600000                      0.985000     0.700000                   0.983000         0.884000         0.705000
### Missing Values
Country name                          0
year                                  0
Life Ladder                           0
Log GDP per capita                   28
Social support                       13
Healthy life expectancy at birth     63
Freedom to make life choices         36
Generosity                           81
Perceptions of corruption           125
Positive affect                      24
Negative affect                      16
### Correlation Matrix
![Correlation Matrix](correlation_matrix.png)
### Outliers
![Outliers](outliers.png)
### Trend Analysis
![Trends](trends.png)
### Analysis Story
### Summary of Happiness Dataset

1. **Dataset Description:**
   This dataset contains information about happiness across various countries and years, focused on multiple factors such as economic status, social support, and personal freedoms, quantified by metrics like the "Life Ladder" and "Log GDP per capita." It encompasses data from 2005 to 2023 with a total of 2,363 observations.

2. **Analysis and Key Insights:**
   The analysis highlights a significant correlation between the "Life Ladder," which represents subjective well-being, and several socio-economic and psychological factors. The strongest correlations include:
   - A strong positive correlation between "Life Ladder" and "Log GDP per capita" (0.78), suggesting that higher economic prosperity is closely linked to increased happiness.
   - Positive associations with "Social support" (0.72) and "Healthy life expectancy" (0.71) further support the importance of health and community in enhancing well-being.
   - Interestingly, the "Perceptions of corruption" have a negative correlation with the "Life Ladder" (-0.43), indicating that higher corruption perceptions may detract from happiness levels.

3. **Surprising or Important Findings:**
   - There are notable levels of missing data for several variables, particularly in "Generosity" (81 missing values) and "Perceptions of corruption" (125 missing values), which could affect the integrity of analyses.
   - The presence of outliers, especially in "Life Ladder" (2 outliers) and "Social support" (48 outliers), suggests potential anomalies that may skew overall findings and warrant further investigation.
   - The negative correlation between "Negative affect" and "Life Ladder" (-0.35) indicates that increased feelings of negativity are linked to lower levels of happiness.

4. **Real-World Actions or Implications:**
   - Policymakers should focus on enhancing economic conditions and reducing poverty to improve overall happiness, emphasizing the importance of financial stability.
   - Strengthening social support systems and community engagement initiatives could lead to increases in subjective well-being, suggesting that investments in social infrastructure are crucial.
   - Addressing issues of corruption can foster trust in institutions and potentially improve the happiness levels reported by citizens.
   - Finally, efforts targeted towards reducing negative sentiments within the population, such as mental health awareness programs, could also contribute positively to enhancing the overall happiness index.
