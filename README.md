### CS 319 final project: Analyzing correlation between development and emission rates

For our grad project, we have chosen two datasets from CORGIS Dataset Project: global_development.json and emissions.csv. We picked these two datasets because they cover about the same period (1980-2013) and they contain international data. The global development dataset contains information about rural and urban population growth, development of agricultural land, and the level of communication infrastructure in each country. The emissions dataset classifies emissions by types (CO2, NO2, CH4) and by industries (power, buildings, transport, other industry and sectors). 

It will be challenging to make causal inferences about development and level of emissions just by tracing the relationships between variables in these two datasets. For example, we do not know what “other industry” or “other sectors” represent in the emissions dataset and what portion the agricultural sector counts for the data under “other industry and sectors”. Some of the headings are not explicitly defined either. For example, it is unclear what “rural development land area” means in emissions.csv. In addition, not all of the data from global_development.json include units, such as the development areas. Lastly, some of the countries in both data sets do not match up, which would result in not all the countries listed in each able to be analyzed. 

With this in mind, the following are the relationships we explored using these two datasets. We created a new dataset containing only the countries listed in both. 

- Total population or population growth -- emissions sector (power industry)
- Urban population density or urban population percent growth -- emissions power industry/ emissions sector buildings/ ratio per GDP/ ratio per capita
- Life expectancy (female and male) -- total emissions of the three types 
- Rural development agricultural land -- certain emission type
- Telephone lines per 100 people -- emissions sector (transport) 
- Arable land/arable land percent -- rural population growth
- Population growth -- how is it divided between rural population growth and urban population percent growth
- Urban population density -- emissions sector transport
