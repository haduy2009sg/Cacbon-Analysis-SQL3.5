# Cacbon-Analysis-SQL3.5
# What is the project about?
![image](https://images.unsplash.com/photo-1611273426858-450d8e3c9fce?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
Photo by Chris LeBoutillier (unsplash.com)

This report aims to analyze carbon emissions to examine the carbon footprint across various industries. We aim to identify sectors with the highest levels of emissions by analyzing them across countries and years, as well as to uncover trends.

Carbon emissions play a crucial role in the environment, accounting for over 75% of global emissions and posing a significant environmental challenge. These emissions contribute to the accumulation of greenhouse gases in the atmosphere, leading to climate change, planetary warming, and involvement in various environmental disasters.

Through this analysis, we hope to gain an understanding of the environmental impact of different industries and contribute to making informed decisions in sustainable development.
# Data Source: Where Our Data Comes From
Our dataset is compiled from publicly available data from nature.com and encompasses the product carbon footprints (PCF) for various companies. PCFs represent the greenhouse gas emissions associated with specific products, quantified in CO2 (carbon dioxide equivalent).
# Data Structure
The dataset consists of 4 tables containing information regarding carbon emissions generated during the production of goods

![image](https://github.com/user-attachments/assets/e2a592c8-004d-4cfa-825e-3b8a9b7e83c7)


### Tables' columns description
### Table 'product_emissions'
1. **id**: Identifier for each product emission record.
company_id: Identifier for the company associated with the product.
2. **country_id**: Identifier for the country where the product is being produced.
3. **industry_group_id**: Identifier for the industry group to which the product belongs.
4. **year**: The year in which the emissions data was recorded.
5. **product_name**: The name of the product associated with the emissions data.
6. **weight_kg**: The weight of the product in kilograms.
carbon_footprint_pcf: The carbon footprint of the product, measured in CO2 equivalent.
upstream_percent_total_pcf: The percentage of the total carbon footprint attributed to upstream activities.
operations_percent_total_pcf: The percentage of the total carbon footprint attributed to operations.
downstream_percent_total_pcf: The percentage of the total carbon footprint attributed to downstream activities.
### Table 'industry_groups'
1. **id**: Unique identifier for each industry group.
2. **industry_group**: The name of the industry group, categorizing businesses within similar sectors based on their products or services offered.
### Table 'companies'
1. **id**: Unique identifier for each company.
2. **company_name**: The name of the company, identifying the specific organization within the dataset
### Table 'countries'
1. **id**: Unique identifier for each country.
2. **country_name**: The name of the country.
