# World-Energy-Consumption

## Table of Content
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [The Dashboard](#the-dashboard)
- [Result and Findings](#result-and-findings)
- [Recommendation](#recommendation)
- [Limitation](#limitation)
- [Reference](#reference)
  

### Project Overview

This dataset is a collection of key metrics maintained by Our World in Data. It is updated regularly and includes data on energy consumption (primary energy, per capita, and growth rates), energy mix, electricity mix, and other relevant metrics.

### Data Source

The dataset was provided in a CSV file format by the company.

### Tools Used

Power BI - Data Cleaning, Transformation, Analysis, and Creating Reports

### Data Cleaning and Preparation

Our complete Energy dataset is available in CSV format. The CSV file follows a format of 1 row per location and year. The variables represent all of our main data related to energy consumption, energy mix, electricity mix as well as other variables of potential interest.
The dataset has over 1,000 rows and 122 columns, Iso_code, Country, Year, coal_prod_change_pct, coal_prod_change_twh, gas_prod_change_pct, etc.

![Screenshot_126](https://github.com/Solution92/World-Energy-Consumption/assets/144762124/88ab3eaf-f8ba-42aa-8886-4849188f6a20)

This is part of the ETL process in preparation for visualization. This dataset was properly cleaned and transformed in the Power Querry editor before loading it to the Power BI desktop for visualization.

### Exploratory Data Analysis (EDA)

I have generated the following key Performance Indicators (KPIs) and insights:

- No. of Countries = COUNT(‘World Energy Consumption’[country])
- Total Oil Consumed = SUM(‘World Energy Consumption’[oil_consumption])
- Total Carbon Consumed = SUM(‘World Energy Consumption’[low_carbon_consumption])
- Total Electricity Gen = SUM(‘World Energy Consumption’[electricity_generation])
- Sum of Solar Consumption by Country
- Sum of GDP by Year
- Sum of Oil Production by Country
- Sum of GDP by Country
- Total Electricity Gen. by Country
- Total Oil Consumed by Country

### The Dashboard

![Screenshot_127](https://github.com/Solution92/World-Energy-Consumption/assets/144762124/a8e2d474-41fd-4cec-879b-a2e158b8e3ec)

### Result and Findings

Below are my findings from the table analyzed

The sum of solar consumption was highest for Germany at 895, followed by Italy and Spain.  Germany accounted for 40.90% of Sum of solar consumption.  Across all 11 countries, the Sum of solar consumption ranged from 3 to 895.  
The sum of GDP was highest for 2016 at 16117000000000, followed by 2015 and 2014.  2016 accounted for 7.73% of the sum of GDP.  Across all 20 years, Sum of GDP ranged from 0 to 16117000000000, and 
Germany accounted for 26.96% of the sum of GDP.  
- Additionally, the Sum of oil production was highest for the United Kingdom at 12,324.07, followed by Italy and Austria.  The United Kingdom accounted for 93.24% of the Sum of oil production.  
- In the same vein, At 12,351.58, Germany had the highest Total Electricity Generated and was 1,733.07% higher than Portugal, which had the lowest Total Electricity Generated at 673.82. Germany accounted for 25.51% of Total Electricity Generated.  Across all 11 countries, Total Electricity Gen ranged from 673.82 to 12,351.58.  
- Lastly, at 27,840.41, Germany had the highest Total Oil Consumed and was 1,400.56% higher than Portugal, which had the lowest Total Oil Consumed at 1,855.34. Germany accounted for 24.46% of Total Oil Consumed.  Across all 11 countries, Total Oil Consumed ranged from 1,855.34 to 27,840.41

### Recommendation

- Based on the findings from the World Energy Consumption analysis, it is recommended to focus on Germany as a key player in both solar consumption and total energy generation. 
- Given Germany's significant share in GDP and its leading position in renewable energy, further investments and policies supporting sustainable energy practices in Germany could have a substantial impact on global energy trends. 
- Additionally, attention should be directed towards addressing the disparity in oil production and consumption, with consideration for diversification and reduction of dependency on fossil fuels in countries with high consumption rates.

### Limitations

- Limited Dimensionality: The dataset appears to be confined to a specific set of variables, potentially missing out on nuanced aspects that could contribute to a more comprehensive understanding of global energy dynamics.
- Overemphasis on Dominant Players: The findings heavily highlight Germany, possibly leading to an overrepresentation of its influence on global energy patterns, while nuances in the energy behavior of other countries might be overlooked.
- Potential Data Discrepancies: The accuracy and reliability of the dataset could be a limitation, as inaccuracies or gaps in the data may compromise the validity of the presented findings.
- Temporal Snapshot: The 20-year timeframe might not capture evolving trends or recent shifts in global energy consumption, limiting the dataset's relevance for predicting future patterns.
- Absence of Qualitative Context: The dataset may lack qualitative information, such as policy frameworks, technological advancements, or socio-economic factors, which are crucial for a more in-depth analysis of the drivers behind observed energy trends.

### Reference

Related datasets could be accessed from any public site like [kaggle](www.kaggle.com)

























































