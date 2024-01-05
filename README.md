### Analyzing correlation between development and emission rates (CS 319 Final Project at UW-Madison)

This is a final project for CS 319 at UW-Madison. In this project, my teammate and I used two datasets from CORGIS Dataset Project - global_development.json and emissions.csv - to analyze how emission rates vary depending on a country's level of development. "Development" in this data has been measured by variables such as rural and urban population growth, development of agricultural land, and the level of communication infrastructure in each country. The emissions data set contains emission data by type (CO2, NO2, CH4) and by industry (power, buildings, transport, other industry and sectors). For our analysis, we created a new dataset subsetting only the countries listed in both data sets, and containing information from 1980-2013. 

We are not making causal inferences about development and level of emissions. This is because we are not able to find the exact definition of each variable in these data sets. For example, we do not know what “other industry” or “other sectors” represent in the emissions dataset and what portion the agricultural sector counts for the data under “other industry and sectors”. Some of the headings are not explicitly defined either. It is unclear what “rural development land area” means in emissions.csv. Not all of the data from global_development.json include units, such as the development areas. Lastly, some of the countries in both data sets do not match up, which would result in not all the countries listed in each able to be analyzed. 

With this caveat, the following are the relationships we explored using the subsetted dataset: 

- Total population or population growth <--> emissions sector (power industry)
- Urban population density or urban population percent growth <--> emissions power industry/ emissions sector buildings/ ratio per GDP/ ratio per capita
- Life expectancy (female and male) <--> total emissions of the three types 
- Rural development agricultural land <--> certain emission type
- Telephone lines per 100 people <--> emissions sector (transport) 
- Arable land/arable land percent <--> rural population growth
- Population growth <--> how it is divided between rural population growth and urban population percent growth
- Urban population density <--> emissions sector transport
