# Analysis of a telecommunications company ConnectaTel

## Objective
The companys’s objective was to identify to identify usage patterns, detect atypical behaviors and understand which customer segments exhibit differentiated needs with the purpose of optimizing the commercial offering and enhancing the overall user experience.

Key questions to address
  * Which customer segments exhibit higher or lower usage of calls and messages?
  * Which users show atypical values that may indicate unusual behavior, potential fraud, or data entry errors?
  * How does usage vary according to age and the type of plan subscribed?
  * What patterns can inform the design of improved plans, support commercial optimization, and enhance customer satisfaction?

For this analysis, two real data sources were used:
  * **plan.csv:** contains the details of the current mobile plans offered by the company, including: price, minutes, GB, cost of additional usage.
  * **user_latam.csv:** provides customer information, including: age, city, resgitration date, susbscribed plan.
  * **usage.csv:** Contains the actual usage behavior of each customer, specifically call duration and message length. 

Stages of the analysis   
  1. **Load an explore**
      - ***Action:*** load and explore dataframes plans, users_latam, usage.
      - ***Business outcome:*** clear understanding of the structure and column types of each dataset.
  2. **Identify data quality issues**
      - ***Action:*** count missing values, detect sentinel values, and review out-of-range dates.
      - ***Business outcome:*** prioritized list of issues that could bias business decisions.
  3. **Basic cleaning**
      - ***Action:*** replace sentinel values, convert date formats, and impute or flag missing values according to defined rules.
      - ***Business outcome:*** Consistent and reliable data ready for statistical analysis.
  4. **Summary statistics**
      - ***Action:*** review key metrics in categorical and numerical variables.
      - ***Business outcome:*** key indicators (mean, median, percentiles) that reveal typical and extreme usage behavior.
  5. **Visualization & outliers**
      - ***Action:*** create histograms and boxplots to explore distributions and detect anomalies.
      - ***Business outcome:*** visual identification of biases, usage patterns and atypical data points.
  6. **Segmentation**
      - ***Action:*** build customer segments based on clear rules; visualize proportions using countplots.
      - ***Business outcome:*** actionable segments to support offer design, marketing campaigns and plan migration strategies.
  7. **Executive insight**
      - ***Action:*** draft conclusions and commercial recommendations based on the previous steps..
      - ***Business outcome:*** address key business questions and propose concrete data-driven actions. 
      <br><br>
