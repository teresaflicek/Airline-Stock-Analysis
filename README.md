# project3

## Background
<h3> Everybody wants to be ahead of stocks.. with Machine Learning, this is now (somewhat) possible! </h3>
  
  In our final project, we decided to analyze stock data related to the top 6 flight companies to see where their stock may be in 65 days. 
  
  The process started in Project 2 where flight company stock data was cleaned and filtered. You can find this process [here](https://github.com/pmhu4242/Project_2/tree/main/Stock%20Market%20vs%20Covid). Very basically, this involved changing column names, merging data sets and other minor fixes.
  
  We then used Plotly to visualize the current data:
![UAL_close _price](AirlineStockAnalysis/images/originalcloseUAL.png)
![DAL _price](AirlineStockAnalysis/images/originalcloseDAL.png)
  
  <h3> Part 2: Machine Learning and Predicting </h3>
  
  We then used machine learning to predict the outcome of the stock price in 65 days. The process involved training our models (we used both a linear regression and a decision tree model). Our outcomes ended with a test score slightly above 50%. While ideal in the sense that the predicitions were better than a coin toss, we wanted a model that could predict with more certainty. In retrospect, we should've used a smaller chunk of data to predict so as to eliminate any major discrepancies that may have occurred with a larger data set. As well, this would help keep the predictions more up-to-date.
  
  Here is an example of a **somewhat** realistic predicition:
  
  ![UAL_close _price](AirlineStockAnalysis/images/decisiontreeDAL.png)
  




[Link to Dashboard!](https://teresaflicek.github.io/project3/AirlineStockAnalysis/)
