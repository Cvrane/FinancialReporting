# Financial Reporting

 `A detailed report to clearly show the financial analysis and business operation of XYZ Capital and to forecast their gross billings in the Quarter 4 of 2013.`
 
## Introduction: 

` This project focuses on forecasting financial and economic time series. Stock market prices are highly unpredictable and volatile. However, I decided to not go all the way believing that there is no hope for a machine learning model to train the time-series data. Considering the seasonal nature of the data, I could at least model the data, so that the predictions that I made correlate with the actual behavior of the data.
For making predictions I used the following methods to draw conclusions: `

### 1. Summary Data Analysis

` To analyze this Financial dataset, I examined it's relation to time series data. Time series analysis uses machine learning in predicting the scope of what is to appear in the coming time. More importantly, the purpose is to obtain perspectives and inferences by training our models on the basis of what has already occurred in the past. In simple words, I utilized the time series analysis in accordance to the seasonal behaviors and trends of the data from the past to predict the future. `

### 2. Development Trend Analysis
 
  Machine learning models on time-series forecasting that I used:
  
  * Holt-Winters Model 
  * SARIMA Model 
  
<h3 align="left">
  <img src="images/holt.png" width="700">
  <br>
  <em>Estimated trend using Holt-Winters model </em>
</h3>

<h3 align="left">
  <img src="images/sarima.png" width="700">
 <br>
  <em>Estimated trend using SARIMA model </em>
</h3>

### 3. Data Comparison Analysis

` I estimated the final Gross Billings for the Quarter-4 2013 and made a comparison to all the previous quarters. In order to make a Buy/Sell decision for a time series model, I recognized the need to perform a statistical correlation analysis on the model. This would later be done by using the Quarter on Quarter (QoQ) Analysis.`

<h3 align="left">
  <img src="images/plotgb.png" width="500">
 <br>
  <em> A solid comparison of all gross billings data </em>
</h3>


### 4. Progress Analysis

`The Quarter on Quarter (QoQ) Analysis technique for gross billingsis the main method used to draw conclusions over stock recommendation.
QoQ was be calculated by:`

<a href="https://www.codecogs.com/eqnedit.php?latex=QoQ_%&space;=\frac{&space;Gross\,Billings&space;\left&space;\{&space;Q4_{2013}&space;-&space;Q4_{2012}&space;\right\}&space;}{Q4_{2012}}&space;\times&space;100" target="_blank"><img src="https://latex.codecogs.com/gif.latex?QoQ_%&space;=\frac{&space;Gross\,Billings&space;\left&space;\{&space;Q4_{2013}&space;-&space;Q4_{2012}&space;\right\}&space;}{Q4_{2012}}&space;\times&space;100" title="QoQ_% =\frac{ Gross\,Billings \left \{ Q4_{2013} - Q4_{2012} \right\} }{Q4_{2012}} \times 100" /></a>

<h3 align="left">
  <img src="images/growth.png" width="700">
 <br>
  <em> QoQ growth rate plot </em>
</h3>
 
### 5. Final Remarks
 `We will make an estimation for Q1 2014 as well using a Simple Exponential Model (using Excel).
     The R-squared value verifies the accuracy of this model.`
     
<h3 align="center">
  <img src="images/q414gb.png" width="700">
</h3>   
     
   
     From XYZ Capital's 2012 annual report, we inferred some characteristics from their business and risk factors:
     
     1) Their financial results will be adversely affected if they are unable to execute on their marketing
     strategy.
     2) If they fail to retain their existing customers or acquire new customers, their revenue and business will
     be harmed.
     2) They may incur losses in the future as they expand their business.
     
     This might give valid reasons for an overall negative growth rate in Q4 2013 Gross billings.
     
     The growth rate from our Q4 2013 Estimation may be bad but when we look beyond the earnings, we will see that
     the new deals that were estimated continue to grow in almost all the months after October 2013. 
     Thus, with XYZ Capital's business fundamentals remaining solid, we expect their stock to rebound soon as the
     company adjusts to perform better in the next quarter as observed from the Q4 2014 estimation. 
  
### Conclusion : 

Our recommendation is to  **Buy** XYZ's stock. 

