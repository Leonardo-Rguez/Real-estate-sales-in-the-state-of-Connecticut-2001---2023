# Real-estate-sales-in-the-state-of-Connecticut-2001---2023
The objective is to examine real estate sales in an attempt to understand the data pattern during the analyzed period

## About datasets

The datasets used refer to real estate sales with a sales price of $2,000 or more that take place between October 1 and September 30 of each year in the state of Connecticut: Real Estate Sales 2001-2023 GL, https://data.ct.gov/Housing-and-Development/Real-Estate-Sales-2001-2023-GL/5mzw-sjtu/about_data.

## The dataset

The dataset information was collected on April 8, 2026, the update March 19, 2026.
The range for the sales ratio has been established between 0.7 and 1.1. The lower limit is set in accordance with ratio testing standards (https://eregulations.ct.gov/eRegsPortal/Browse/RCSA/Title_12Subtitle_12-62iSection_12-62i-3/), while the upper limit is arbitrary. Both limits include values raging between 70 and 110 percent of the sale amount.

## Used tools

■ Power BI Desktop

■ Power Query

■ DAX

■ Fuente de datos (Excel/CSV)


## Data visualization

The objective is to examine real estate sales in an attempt to understand the data pattern during the analyzed period. The following reports are included:

I.	Overview
II.	Trends
III.	Analysis by Town
IV.	Growth
V.	Property Type

## Insight

### I.	Overview

<img width="794" height="448" alt="Overview" src="https://github.com/user-attachments/assets/5106de37-b8ec-47f0-8758-655ee877f206" />



All sales greater than or equal to $2000.00 in the 169 cities in the database are shown, can be observed:

1.	Total real estate sales: 1,139,582
2.	Median global price: $238,000
3.	Total sales amount: $468620316775
4.	Median global sales ratio: 0.6067
5.	Distribution by property type, 91.88% is distributed among the following properties: (does not include those without a classification = 380443):


    ■ Single family: 401502 (52.89%).
  
    ■ Residential: 190628 (25.11%).
  
    ■ Condo: 105402 (13.88%).


6.	The sales ratio ranges are shown :

     ■ Underassessed (<= 0.6999): 759200 (66.6%)
     
     ■ Acceptable (0.70 – 1.10): 267460 (23.5%)
       
     ■ Soverassessed (1.1001 – 2.0001): 71890 (6.3%)
     
     ■ Extreme outliers (2.0002-6343.0567): 41032 (3.6%)


### II.	Trends


<img width="802" height="450" alt="image" src="https://github.com/user-attachments/assets/84f9e8cb-9592-4e98-97c7-917c87930307" />


1.	Median price vs. fiscal year chart: the sales ratio value, falls between >= 0.7 and <= 1.1:

■ A peak is recorded in 2006, when the median price reached $290,000. This coincides with the US housing bubble, which affected more than half of the states. Housing prices peaked in early 2006 ( https://es.wikipedia.org/wiki/Burbuja_inmobiliaria_de_los_Estados_Unidos ). The same source indicates that new lows were reached in 2012. In this dataset, the lowest price appears in 2015, perhaps due to: (1) the use the median in the calculation, (2) limiting the sales ratio to a specific range, or (3) that fact the price behaved differently in that state.

■ Starting in 2017, the median price continued to rise until the last year of the dataset.

2.	Graph of total sales amount and median sales ratio vs. fiscal year. The sales ratio value is between >= 0.7 and <= 1.1.

■	Years 2009 – 2016. The median of sales ratio is between 0.7580 – 0.7133

■ The minimum value of median sales ratio in 2016 = 0.7133.

■	The maximum value of median sales ratio in the year 2011 = 0.8546.

■	The minimum value of total sales amount in 2009 = $10.666M.

■	The maximum value of total sales amount in 2015 = $19.896M.


3.	Chart of total sales amount and total real estate sales vs. fiscal year, no filter applied:

■	Both curves have a similar pattern, although two points should be noted: (1) Year 2004, the year with the highest number of sales made (83433) but it is not the peak of the highest total amount ($32.00bn) (2) Year 2020, the year with the highest peak of the total amount ($40.3bn).

### III.	Analysis by town

<img width="801" height="453" alt="image" src="https://github.com/user-attachments/assets/16f89469-50b1-475e-b983-acceeb2ae56e" />


It does not include the analysis by property type.

■	Top 10 by sales amount:

• Greenwich. Highest total sales amount: $41.00bn (19267 total real estate sales).

• Bridgeport. Highest number of real estate sales: 39639 ($9 billion).

The data indicates a lower median price in Bridgeport and the real estate market is more active.

■	Bottom 10 of sales amount:

•Franklin. Highest total sales amount: $164 million (645 total real estate sales).

•	Sprague. Highest number of real estate sales: 875 ($161 MM). 

•	Union. Lowest number of real estate sales: 294 ($59MM).

The real estate market is less active in Union.

### IV.	Year-over-Year Growth

The most significant periods:

■	Years 2005–2008: Slower growth. Growth in real estate sales was negative (ranging between -26.45% and -8.06%). Growth sale amount positive is only one year (3.4%); in the other years, the decline hovered around 30%.

■	Year 2016. Moderate growth in the real estate sector (6.69%) and strong growth in sales volume (56.6%).

■	Year 2020. The highest peak in sales growth (62.6%).


### V.	Property Type

All median prices for Sales ratio are between 0.7 – 1.1.

■	Single Family. The highest median price between 2006 and 2019 ($239900).

■	Apartments. The highest median price between 2020 and 2023 ($300000).

■	Three Family. The lower median price between 2006 and 2019 ($156125).



