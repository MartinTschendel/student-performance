# student-performance
This data approach student achievement in secondary education of two Portuguese schools. The data attributes include student grades, demographic, social and school related features) and it was collected by using school reports and questionnaires. Two datasets are provided regarding the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por). In [Cortez and Silva, 2008], the two datasets were modeled under binary/five-level classification and regression tasks. Important note: the target attribute G3 has a strong correlation with attributes G2 and G1. This occurs because G3 is the final year grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades. It is more difficult to predict G3 without G2 and G1, but such prediction is much more useful (see paper source for more details). 
<br>
<b>Source:</b> P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.<br>
<b>Web-Link:</b> http://archive.ics.uci.edu/ml/datasets/Student+Performance

The dataset contains a high ratio of categorical variables/features. Overview on different datatypes:<br>
https://www.dummies.com/education/math/statistics/types-of-statistical-data-numerical-categorical-and-ordinal/

* writing a linear regression model to predict the performance of students based on socio-economic features
* 2020-07-29: started to select the first numerical and categorical features to training set and completed one-hot encoding accordingly
* 2020-07-30：included more feature variable, that led to a very high rmse
* 2020-07-30: after regularization, the rmse decreased to 2,86 (based on training set)
* 2020-07-31: added all features and checked the performance of the model on the validation set
* 2020-07-31: also checked the performance of the model on the test set
* 2020-07-31: the rmse on the test set is 1.189 and the rmse on the validation set is 0.807 
* 2020-08-01: the notebook also contains the function to adjust the value of specific features and see how the final performance of the student would change
