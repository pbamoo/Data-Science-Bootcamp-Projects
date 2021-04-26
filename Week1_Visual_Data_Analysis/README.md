# Week 1/12 The Gapminder Project
   
### Background problem / Goal:
The challenge of this project was to analyze and visualize statistics from the [Gapminder datasets](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/tree/main/Week1_Visual_Data_Analysis/Data) and create an animated scatterplot like the one by [Hans Rosling](https://www.youtube.com/watch?v=jbkSRLYSojo) to illustrate the correlation between life expectancy and fertility of the world’s countries from 1960 to 2015.

### Tools/Libraries Used: 
Python, Pandas, Matplotlib, Seaborn, Imageio, Plotly 

### Workflow:
1. Data Acquisition: 
The [datasets(3)](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/tree/main/Week1_Visual_Data_Analysis/Data) were obtained from http://www.gapminder.org/data website. 

2. Preprocessing:
In order to understand and prepare the data for analysis, some data inspection and preprocessing was done which can be found [here](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Code/1_utils.ipynb) and eventually written into [functions](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Code/utils.ipynb) for easabiliy in coding and scripting.

3. Exploratory Data Analysis(EDA):
A glimpse of data and its context, as well as insights captured using descriptive statistics and visualization techniques can be found [here.](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Code/3_EDA.ipynb)

4. [Result & Outlook:]
   * The main goal for the project, which was to reproduce the Hans Rosling animation scatterplot was [achieved.](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/tree/main/Week1_Visual_Data_Analysis/Images) 
   * From the [EDA](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Code/3_EDA.ipynb), the population and life_expectancy shows an incremental trend while fertility rate is on the decline generally while life_expectancy seems to show a strong negative correlation to fertility_rate with the rest metrics showing very weak to almost no correlation at all to each other.
   * To understand and clearly explain the factors at play, bigger (and more difficult) datasets with additional metrics like GDP Per Capita, Literacy Rate, Employment Rate, Regions, etc. needs to be incorporate into the data analysis project to get more insights to questions like:
      - Which region of the world has been changing relatively quickly compared to others in terms of GDP, life expectancy, and other indices?
      - How have income, population, child mortality, and children born per woman decide the life expectancy of a certain country?
