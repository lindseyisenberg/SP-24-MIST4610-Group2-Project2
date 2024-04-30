# Group 2 MIST 4610 Project 2




## Team Name
21482 Group 2

## Team Members
Rohan Patel [@rohpat](https://github.com/rohpat)  <br>
Grace Okpurukre  [@graceokpurukre](https://github.com/graceokpurukre) <br>
Lindsey Isenberg [@lindseyisenberg](https://github.com/lindseyisenberg)  <br>
Catherine Repke  [@catherinerepke](https://github.com/catherinerepke) <br> 
Ore Pratt [@nathanp2020](https://github.com/nathanp2020) <br> 
## Dataset

Water Quality Data Set: https://catalog.data.gov/dataset/water-quality-data-41c5e

The data set we chose contains information about the water quality of multiple Refuge sites ran by the United States Department of the Interior, denoting important information that plays a crucial role in analyzing and helping individuals use data to make determinations based on water quality data. Using key information and analytics tools many different variables that are questioned can be determined.  The data contains information about the site or location, the date it was read, and multiple different measures. These measures include pH level, salinity, water temperature, air temperature, and water depth. The data also displays the year that the data was recorded. This information allows visualizations about the water quality throughout the years to be made. 

## Questions
1. What is the average amount of dissolved oxygen in the water for each month from the last 20 years?


2. What factor caused dissolved oxygen to change the most over the year, and when does it occur?

## Data Manipulation/Filters
Question 1: Read date (months), Years (filtered from 2000-2019), average dissolved Oxygen (mg/L) applied as a color mark. Read date indicated the date in which measuresments were taken, and year shows a range of time from 2000 to 2019.
Dissolved oxygen is placed on the graph as a mark; the scale in the bottom right hand corner denotes the meaning behing the color gradient.

Question 2:
Read date (months), Years (filtered from 2000-2019), average dissolved Oxygen (mg/L) applied as a color mark. Air and water temperature (degrees Celcius).  Read date indicated the date in which measurements were taken, and year shows a range of time from 2000 to 2019. Water and air temp are shown by side by side scatter plots, with the size of the dot denoting water temp. Trend lines are added to show correlation between variables.
## Analysis and Results

Question 1

![Screenshot (293)](https://github.com/nathanp2020/SP-24-MIST4610-Group2-Project2/assets/148779254/b58c8464-28ef-42a8-95f2-a04e7f585f1a)

This question shows how the amount of dissolved oxygen changes throughout the months on average. As shown, the dissolved oxygen tends to be much lower during the 
summer months, and reaches its lowest between June and September. 

This kind of information is important to know for private water companies or government water regulators who would like to know the trend of average dissolved water.
They can use this information in many ways to find causation and work on ways to remedy issues to meet goals, such as in this instance.  After observing this, our second question investigates this further. 



Question 2
![Screenshot (297)](https://github.com/nathanp2020/SP-24-MIST4610-Group2-Project2/assets/148779254/811bb26b-cda5-4731-97eb-b258499c323a)


In this specific issue this corporate entity is trying to figure out how average air temperature(C) has correlated with dissolved oxygen over the years. There is an apparent trend that shows through the visualization presented. 
By looking at the heat map of all the values per month for the last 20 years, we are able 
to see that dissolved oxygen tends to be lower during the summer months. This would explain the dip in our initial graph. We know from this trend that dissolved oxygen and temperature have an inverse relationship.


The above dashboard shows dissolved oxygen and water temperature (C) plotted against air temperature. The purpose of this is to show how environmental external factors can impact the dissolved oxygen levels. As temperature increases, dissolved oxygen in water decreases. We can see that in this accompanying visualization, where as the air temperatrue increases on the X-axis, the dissolved oxygen level decreases as well. We also see the water temperature increasing as the air temperature increases. This shows that air and water temperature are highly correlated and dissolved oxygen levels also has a correlation to heat. This matches our observation that there is less dissolved oxygen in summer months due to high temperatures.
DO levels below 5 mg/L are considered high stress for fish. Anything below 3 mg/L is considered too low to support fish, and below 1 is considered hypoxic with little to no signs of life.
The second accompanying visualization shows the change over the months of summer, and over the those months for a 20 year period (2000-2019). The trend lines clearly denoteate how this inverse relationship occurs. This visualization helps us better understand the maintenance requirements of these reserve pools by the federal government, as well as how the changing temperature and climate in our work impacts things such as wildlife reserves. 
