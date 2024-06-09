## Model Accuracy: Ratio Financial Data vs Crude Financial Data

----
<br clear="both">

<div align="center">
  <img height="300" width="100%" src="https://github.com/GodfreyElia/bankruptcy_prediction_with_rawdata/blob/main/Files/Bankruptcy_Prediction.png"  />
</div>
----

### 1. Preamble

As a financial analyst, whether analysing a potential investment opportunity or corporate bankruptcies, the question of whether to use financial ratios or crude financial data as obtained from a company's books is always paramount. Though it is almost a norm to see most financial analyses done using ratios as opposed to crude financial data, this area has not been widely researched by scholars and practionars alike. Thus, this projects sets to understand whether, if at all, the performance of predictive models is affected by the nature of data used to test and train the models.

### 2. Methodology

To find out if the type of data (ratio or crude) used to train and test machine learning models has an impact on their predictive performance, I used crude financial data to train and test 7 models. I then transformed the same data into financial ratios and I subsequently used it to train and test the same 7 machine learning models. Finally, I compared the accuracies of the models under the different treatments using data visualisation and a paired t-test.

### 3. Findings:

<br clear="both">

<div align="Left">
  <img height="60%" width="75%" src="https://github.com/GodfreyElia/Ratio-Data_V_Crude-Financaial-Data/blob/main/Diagrams/Box_Plot.png"  />
</div>
<br>

Fig 1: Box-Plot Showing a Comparison of Accuracies of Models Trained Under Ratio Data and Crude Data

<br clear="both">

<div align="Left">
  <img height="60%" width="75%" src="https://github.com/GodfreyElia/Ratio-Data_V_Crude-Financaial-Data/blob/main/Diagrams/Bar_Graph.png"  />
</div>
<br>

Fig 2: A Bar Chart Showing a Side by Side Performance of Similar Models Trained Using Different Types of Data

From figures 1 and 2, it is easy to notice that models trained under ratio financial data out perfors models that are trained using crude financial data. In our specific comple, the awrags accuracy of the ratio data trained models was just under 94% as opposed to an average of 75% by models trained under crude data. In fact, the least perforaing model in the ratio data trafined andels sent outperfores all the sodels In the crude data camp.

9999 3.2. Statistical Tests

Finally, we ask a question whether the difference in the models is statistically significant or is due to pure chance. To answer this questi confidence level. paired t-test

From the test, se can reject the mill hypothesis that ther
