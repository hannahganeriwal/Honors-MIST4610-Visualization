# Honors-MIST4610-Visualization


#### Tableau Workbook Included: "Honors Visualization MIST4610"

Hannah Ganeriwal [@hannahganeriwal](https://github.com/hannahganeriwal/Honors-MIST4610-Visualization)

## Describing your dataset and what data it contains:

We were able to pull this dataset from the data.gov website titled “NCHS - Leading Causes of Death: United States.” This dataset shows recorded information about deaths for the 10 leading causes of death in all 50 states in the United States, starting in 1999 until 2017. Populations used for computing death rates after 2010 are postcensal estimates based on the 2010 census, estimated as of July 1, 2010. The 10 leading causes include Alzheimers, Strokes, CLRD (chronic lower respiratory disease), Diabetes, Heart Disease, Influenza and pneumonia, Suicide, Cancer, Kidney Disease, and unintentional injuries. Within this dataset, there are 10,868 rows, and each row represents a specific cause of death in a specific year for a specific state. This means that each row is a death statistic for a disease in a specific state for the year. For each case, the dataset recorded the year of death (as an INT), the ICD classified 113 Cause Name (VARCHAR), the commonly used Cause Name (VARCHAR), the state the death occurred in (VARCHAR), the Deaths total (INT), and the Age-Adjusted Death Rate (DECIMAL), which is the amount of deaths per 100,000 people of the population. This results in a table of 10,868 rows and 6 columns. This dataset is very effective in communicating the death rates for each state. It is very easy to see what causes of death are the most prevalent. It also allows us to look into how these death rates changed over time, and what sort of effect the geography of them had on these rates.

## Question 1: What are the leading causes of death in Georgia for 2017?

### Importance/Analysis
This graph shows the causes of death in the state of Georgia just for 2017. With this being said, the 2 leading causes of death in Georgia were both Cancer and Heart Disease by at least 12,000. 
Visualizing this graph could be crucial for various reasons. Firstly, it provides a concise overview of the leading causes of mortality in the state, allowing healthcare professionals and public health officials to identify and prioritize areas for intervention and resource allocation. By visually representing the distribution of deaths across different causes, both as a percentage and count, policymakers can gain insights into the prevalent health issues within the population and tailor preventive strategies accordingly. Limiting the visualization to just one year can also be impactful as it analyzes trends and patterns within that specific time frame. It allows for the identification of any sudden changes or fluctuations in mortality rates, which may indicate emerging health threats or shifts in disease burden. By doing this also focuses on the current population, as the population in Georgia significantly increases overtime. So, after thorough analysis of the visualization I created, it was interesting to note how huge heart disease and cancer caused death. This graph showed the total deaths in Georgia in 2017 which was 60,932 and the 2 leading factors combined equal 58.30% of the total deaths which is substantial. To put this into a broader perspective, around every 6 out of 10 people die from either, which further implies the need for interventions to help decrease these numbers. 

### Manipulations: 
In regards to manipulations to this dataset, I had to filter out both the United States in the state column and All causes in the cause name column. Both of these showed the total number of deaths within the US or total number of deaths in that year, which ended up skewing the data heavily. So, filtering those two out normalizes the set and allows for an easy read. Additionally, on the analytics tab, in order to find out the grand total of deaths in the state, I had to bring over totals so that I could calculate the percentage of deaths that were led from heart disease and cancer. I then decided to put both of these graphs in a dashboard because although they show the same thing, I wanted to examine based on percentage and the actual numbers which then included the grand total at the bottom. 



