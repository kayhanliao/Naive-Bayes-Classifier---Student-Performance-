# Naive-Bayes-Classifier---Student-Performance-

Predicting Passing and Failing Students using a self made Naive Bayes Classifier. This was an assignment for one of my applied machine learning classes which I thoroughly enjoyed. As an extra component I compared the performance and accuracy to the built in classifier made by scikit-learn. 
The student data is from UCI's Machine Learning Repository and can be found here: https://archive.ics.uci.edu/ml/datasets/Student+Performance

The following two screenshots are comparing the scores of the model I made and scikit-learns model. Both classifiers are binary and I divided the students into groups that scored higher than 12 and ones that scored less than that. I dropped the metrics ['absences','G1','G2'] as they were not relevant. 


![Screen Shot 2021-05-30 at 15 40 16](https://user-images.githubusercontent.com/42952515/120104490-565d3380-c15d-11eb-86eb-50205da9c7a9.png)
![Screen Shot 2021-05-30 at 15 40 23](https://user-images.githubusercontent.com/42952515/120104501-64ab4f80-c15d-11eb-9048-f93aafcf266f.png)


The third screenshot is of the multinomial model I created. 
![Screen Shot 2021-05-30 at 15 40 29](https://user-images.githubusercontent.com/42952515/120104496-5d844180-c15d-11eb-89a8-8c34436eea23.png)
