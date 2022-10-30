# Exploratory Data Analysis

By studying the data distribution of the 5 datasets via box and whisker plots, some anomalies were found in Switzerland, VA and Hungarian datasets.


<img width="848" alt="Screen Shot 2022-10-29 at 8 09 03 PM" src="https://user-images.githubusercontent.com/61631006/198860837-640184f1-86e1-4f89-8785-12b758fb76a6.png">

The box and whisker plots above reveal the following analomies
+ The **Switzerland** and **VA** datasets had either missing or 0 values for cholesterol 
+ The **Hungarian** dataset also has an abnormal distribution of values for restingECG compared to the other datasets

## Final Dataset 
Given these findings, this research study used the **Cleveland**, **Statlog**, and **cleaned VA** datasets only since their data distribution is consistent and has comparable ranges for minimum, lower quartile, median, upper quartile and maximum values. The box plots showing distributions for all attributes in these datasets, is shon below. 

<img width="888" alt="Screen Shot 2022-10-29 at 8 10 02 PM" src="https://user-images.githubusercontent.com/61631006/198860839-50647500-099d-4c35-9ebd-5f1e28fa553b.png">
