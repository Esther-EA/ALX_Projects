# Maji Ndogo Water Services

## Project Overview

This data analysis aims to provide insights into the progress of the water services of a fictitious country, Maji Ndogo, over the past year. By analyzing various aspects of the water quality data, we seek to identify the problems each water source and the community faces and also the effectiveness of the employees in charge. To make data-driven recommendations and gain deep understanding of the performance we harnessed the power of SQL functions to clean, aggregate data and unravel the scale of the problem to form some actionable insights.
## Data Sources

### Maji Ndogo water source
 
The primary dataset used for this analysis is the ["md_water_services"](https://https://drive.google.com/file/d/1nXeoG9nnSs4oiVvft3K9VFUfRiYzvTJF/view?usp=sharing) data, containing detailed information about each water source, employee performance and water quality.
Tools

•	Sql server - Data Analysis
## Data Cleaning/Preparation

In the initial preparation phase, we performed the following tasks:

1.	Data loading and inspection.

•	Replaced, add and updated dataset.

•	Ensured there were no vacant values in the columns.
    
2.	Handling missing values.

3.	count all rows to identify missing values and solved by filter and splitting columns

4.	Data cleaning and formatting.

•	Added new columns such as employee email annual rates of exchange by area and region, and rounded national population.

Data Analysis
Data analysis involved exploring the md_water_services data to answer key questions, such as:

•	What type of water sources need to be improved and where?

•	Who are we doing this for and where are they?

•	What do we need to do, and where do we need to do it?

•	What will this cost?

•	How far is the project?

## Results/Findings

Based on the analysis, we recommend the following actions:

•	If communities are using rivers, trucks can be dispatched to those regions to provide water temporarily while crews are sent to drill for wells, providing a more permanent solution. 

•	communities using wells can install filters to purify the water. For wells with biological contamination, UV filters that kill microorganisms, and for *polluted wells*, we can install reverse osmosis filters. In the long term, we need to figure out why these sources are polluted.

•	For shared taps, in the short term, we can send additional water tankers to the busiest taps, on the busiest days. We can use the queue time pivot table we made to send tankers at the busiest times. Meanwhile, we can start the work on installing extra taps where they are needed. According to UN standards, the maximum acceptable wait time for water is 30 minutes. With this in mind, our aim is to install taps to get queue times below 30 min. 

•	Shared taps with short queue times (< 30 min) represent a logistical challenge to further reduce waiting times. The most effective solution, installing taps in homes, is resource-intensive and better suited as a long-term goal. 

•	Addressing broken infrastructure offers a significant impact even with just a single intervention. It is expensive to fix, but so many people can benefit from repairing one facility. For example, fixing a reservoir or pipe that multiple taps are connected to. We will have to find the commonly affected areas to see where the problem actually is.




