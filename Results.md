![image](https://github.com/KajaMarinsek/2024_AppliedDataScience/blob/main/Data%20Modeling%20Project%20-%20Kickstarter/images/OrangeTinyIcon.png)

 * To gain insight into Kickstarter data that I found in the [Orange](https://orangedatamining.com/) 
and where I ran the same test split to see the model performance scores:


![image](https://github.com/KajaMarinsek/2024_AppliedDataScience/blob/main/Data%20Modeling%20Project%20-%20Kickstarter/images/AverageScoresKickstarter.png)

![image](https://github.com/KajaMarinsek/2024_AppliedDataScience/blob/main/Data%20Modeling%20Project%20-%20Kickstarter/images/OrangeTinyIcon.png)
Yes Scores ![image](https://github.com/KajaMarinsek/2024_AppliedDataScience/blob/main/Data%20Modeling%20Project%20-%20Kickstarter/images/YESscoresKickstarter.png)

![image](https://github.com/KajaMarinsek/2024_AppliedDataScience/blob/main/Data%20Modeling%20Project%20-%20Kickstarter/images/OrangeTinyIcon.png)
No Scores  ![image](https://github.com/KajaMarinsek/2024_AppliedDataScience/blob/main/Data%20Modeling%20Project%20-%20Kickstarter/images/NOscoresKickstarter.png)



### After I ran my two .ipynb files to gain Scikit-learn and Pycaret results of classification of same Kickstarter data:
![image](https://github.com/KajaMarinsek/2024_AppliedDataScience/blob/main/Data%20Modeling%20Project%20-%20Kickstarter/images/Screenshot%202024-04-17%20003034.png)

 __Accuracy:__ It measures the overall correctness of the model across all classes.
In my case, the accuracy is approximately 0.8112. This means that roughly 81.12% of the predictions made by the model were correct.
Comparing it to Orange score of 0.826, my model did pretty good as well.

__Precision:__ Precision is a measure of the correctness achieved in positive predictions made by the model. It's calculated as the ratio of true positives to the sum of true positives and false positives. In my case, the precision is approximately 0.7524. This means that when the model predicted a positive outcome, it was correct about 75.24% of the time. This score compared to the precision in Orange of 0.844 makes mine 10% less precise.

__Recall:__ Recall, also known as sensitivity, measures the completeness of the model. It calculates the ratio of true positives to the sum of true positives and false negatives. In my case, the recall is approximately 0.8144. This means that out of all the actual positive instances, the model correctly identified about 81.44% of them. In comparison to Orange positive recall of 0.757, mine did cca 5% better.


![image](https://github.com/KajaMarinsek/2024_AppliedDataScience/blob/main/Data%20Modeling%20Project%20-%20Kickstarter/images/OrangeTinyIcon.png) 
[Orange Report](https://github.com/KajaMarinsek/Mac/blob/main/OrangeKckstarterReport.pdf)
