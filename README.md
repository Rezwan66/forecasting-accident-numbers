# forecasting-accident-statistics
Developed a prediction model to forecast the number of accidents on a certain future date.

## Mission 1: Creating a AI Model
The dataset displays the number of accidents for specific categories per month. The first 5 columns are taken into consideration:
- Category
- Accident-type
- Year
- Month
- Value
  
![Historical Accidents per Category](https://github.com/Rezwan66/forecasting-accident-statistics/assets/63563859/3fc9e2ef-e338-4141-bac5-c5c69abb6799)*Historical Accidents per Category*

We visualized historically the number of accidents per category (column1). We create an application that forecasts the values for:
* Category: 'Alkoholunfälle'
* Type: 'insgesamt
* Year: '2021'
* Month: '01'

![Actual Data vs Forecast](https://github.com/Rezwan66/forecasting-accident-statistics/assets/63563859/32781291-6910-44e7-9e2f-c9944efc1a04)
*Actual Data vs Forecast*

We have also computed the error between the prediction values and the actual numbers (ground truth data).

## Mission 2: Publishing source code & Deploy
- Published source code to GitHub
- To deploy the model to a cloud service (TODO)

## Mission 3: Sending URL of the work

Make a POST request to the following URL.

https://dps-challenge.netlify.app/.netlify/functions/api/challenge
