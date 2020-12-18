# Clustering_Countries
Grouping countries based on the success of the countries - by examining features from GDP Per Capita top Life Expectancy each country.


---
# <center>CONTENTS
> ## 1. Examining the Dataset
  >> Explore the Data Set examine all the different features
  >>#### Features Explanation
    
>>>   <b>country</b> - Country name
    
>>>  <b>child_mort (Child Mortality)</b> - Death of children under 5 years of age per 1,000 live births
    
>>>   <b>exports</b> - Exports of goods and services per capita. Given as percentage age of the GDP per capita
    
>>>   <b>health</b> - Total helath spending per capita. Given as percentage age of GDP per capita
    
>>>   <b>imports</b> - Imports of goods and services per captia. Given as percent age of the GDP per capita
    
>>>   <b>income</b> - Net income per person
    
>>>   <b>life_expec (Life Expectancy)</b> - The average number of years a new born child would live if the current mortality patterns are to remain the same
    
>>>   <b>total_fer (Total Fertility)</b> - The number of children that would be born to each woman if the current age-fertility rates remain the same
    
>>>   <b>gdpp (Gross Domestic Product per Capita)</b> - GDP per capita. Calculated as the Total GDP divided by the total Population.
> ## 2. Cleaning Data
  >> Check for any missing data and scrubing the data
  >> No data is missing, there are outliers - outliers are kept because data sample is small and the the outliers are representative of the existing countries or extremes.
> ## 3. Modeling Data
 >> ### A. K-Means Clustering
 >> ### B. Hierarchical Clustering
 >> ### C. DBSCAN Clustering
 >>> #### Each model includes PCA and UMAP dimensionality reduction in order to visualize and compare the models with each other
 >>> #### The Silhouette Score is also included as a comparison and as reference for each model

---
> ## 4. Conclusions
  >><b>After reviewing and examining each model - visually and comparing the silhouette scores, K-Means Clustering with UMAP Dimensionality reduction yields the best result.
  
  Silhouette Score: .5848<br>
Visually, we can see the clusters most distinctly in contrast to other models.<br>
Similar countries are grouped together as expected<br>
USA is grouped with other similar countries (UK, Japan, Germany, France, etc.)<br>
Further analysis needs to be conducted in examining how well these countries do in contrast to other countries.

---




