# Electricity Data Analysis Project

## 1. About
Hi, I'm Tiago. I hold a Master's degree in Mechanical Engineering and I am currently a researcher dedicated to applying Machine Learning techniques to the renewable energy sector.
This is my first data analysis project, which I have worked on in my free time (not related to my professional work). I hope you find this project informative and valuable.
For any issues, suggestions, comments, or questions, please contact me.

## 2. Project Overview
This project analyzes global electricity data, focusing on various metrics such as electricity generation, net imports and emissions. The data is sourced from multiple reputable organizations and compiled to provide a comprehensive view of the electricity landscape across different countries and regions.

## 3. Dataset
### Source
The dataset used in this project is the "Yearly Electricity" dataset provided by EMBER. This dataset contains information on electricity generation, net imports, demand, installed capacity, and emissions across various countries and regions.

### Access
The dataset is publicly available and can be accessed at the following link:
[EMBER Yearly Electricity Data](https://ember-climate.org/data-catalogue/yearly-electricity-data/)


## 4. Methodology

This project utilizes 10 years of data (2012-2022) and focuses exclusively on electricity data related to generation, imports, and demand. Installed capacity data was excluded due to the presence of null values.

The work is divided into two main parts:

1. **Electricity/Emissions Generation**:
    - Analyze how electricity and emissions are distributed by country and continent.
    - Identify which fuel types are most responsible for electricity and emissions generation.
    - Examine year-over-year differences in electricity and emissions generation by fuel type.
![image](https://github.com/user-attachments/assets/1bdd6077-8d79-4439-9790-32370b2d8a30)
2. **Rankings**:
    - Rank countries based on electricity and emissions generation for each fuel type.
![rankings](https://github.com/user-attachments/assets/9afc8630-7b67-4896-9e2c-4af4005d995b)

### Datasets
The core datasets cover the following subjects:
- **Electricity Generation (TWh)**: By fuel type and aggregated.
- **Electricity Net Imports (TWh)**: Total net imports.
- **Electricity Demand (TWh)**: Calculated as the sum of power production and net imports.
- **Emissions from Electricity Generation (Mt CO2e)**: Calculated using IPCC emissions factors.

### Fuel Types
The data is categorized into the following generation types:
- Bioenergy
- Coal
- Gas
- Hydro
- Nuclear
- Other Fossil (generation from oil and petroleum products, as well as manufactured gases and waste)
- Other Renewables (geothermal, tidal and wave generation)
- Solar
- Wind

## Key Points
- **Accuracy and Reliability**: Data is assembled using the best available sources and methods to ensure accuracy.
- **Bioenergy**: Included in renewable energy sources, but with noted sustainability caveats.
- **Regional and World Estimates**: Where data is not available for all countries, estimates are made based on regional trends.

## 5. Project Structure
- 'data/': Contains raw csv data file
- 'visualizations/': Power BI Desktop project file

### How to Use
- Clone the repository.
- Open the Power BI file in the `visualizations` folder with Power BI Desktop.

## 6. Benefits of Doing This Project

### Personal Learning and Growth
As this is my first data analysis project, it significantly enhanced my understanding in Power Bi software.
The hands-on experience allowed me to explore various features and functionalities, helping me become more proeficient in data visualization and analysis.

### Insights Gained
This project provided valuable insights into global electricity generation and usage. Some curiosities that I found:
- I discovered that Albania meets all electricity demand through hydro generation;
- Brazil stands out as the third-largest producer of electricity from renewable sources;
- Asia's energy production for electricity is substantial accounting for approximately 56% of the world's total electricity production.
