# UCB-AI-ML-PA-III

Practical Assignment III: Comparing Classifiers 

<img width="523" alt="Screen Shot 2024-01-23 at 2 38 41 PM" src="https://github.com/mzacomp/UCB-AI-ML-PA-III/assets/146776815/76be3610-2aeb-414c-869d-d4481dd1d6d2">


The data is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns. Data can be found from the 
UCI Machine Learning Repository. The goal of this assignment compare the performance of certain classifiers, 
 Logistic Regression,  K-Nearest Neighbor, Decision Trees, and Support Vector Machines. 

Business Understanding: 

 The business goal is to find a model that can explain success of a contact, and results in the client subscripition to the deposit. 
 This model can increase campaign efficiency by identifying the main characteristics that affect success, helping in a better management of the available resources (e.g. human effort, phone calls, time)
 and selection of a high quality and affordable set of potential buying customers.

Data: 
 
<img width="530" alt="Screen Shot 2024-01-23 at 2 26 26 PM" src="https://github.com/mzacomp/UCB-AI-ML-PA-III/assets/146776815/61e080e9-707e-4eb3-b8db-f5ce12429c64">



Univariate and multivariate analysis were performed for Exploratory Data Analysis. The following hypothesis was formulated from this: 
Profession, marital status, loan, previous campaign outcomes, and age are the most significant contributors to a successful campagign result of client subscription of the deposit.

The features that were utilized were: 'age', 'job','marital','education','default','housing','loan', 'y' (target outcome). 

After performing feature engineering without hyperparameter optimization, these were the following results of the Logistic Regression, KNN, Decision Tree, and SVM models. 



<img width="537" alt="Screen Shot 2024-01-23 at 2 30 33 PM" src="https://github.com/mzacomp/UCB-AI-ML-PA-III/assets/146776815/10f23c82-224e-4aa8-9891-7ae3af494bbd">


After performing additional feature engineering, hyperparamter optimization, and supplemental evaluation measures on the models, these are the results as follows: 
<img width="881" alt="Screen Shot 2024-01-23 at 2 30 48 PM" src="https://github.com/mzacomp/UCB-AI-ML-PA-III/assets/146776815/85806d8f-e00f-49be-86b6-5b9c869a597b">


Logisitc Regression was found to be the most effective model in both analyses. 

Confusion Matrices were performed to depict evaluation measures: 

![cm ](https://github.com/mzacomp/UCB-AI-ML-PA-III/assets/146776815/3033a5e8-99e9-4ef2-98c6-05cbadd8b477)


For the concluding findings and deloyment, feature importance analysis was performed to determine the most important features. 

![fm a](https://github.com/mzacomp/UCB-AI-ML-PA-III/assets/146776815/86c75ac0-10dd-4e67-827e-2325c55137ea)

'poutcome' was the most important feature, demonstrating that previous campaign outcomes influence clients. Profession,education, and age were other important features. 
Marital status loan were not important features. 



![pco](https://github.com/mzacomp/UCB-AI-ML-PA-III/assets/146776815/be45e1ec-85d3-436f-b983-dab14c1c3e3d)

![prof](https://github.com/mzacomp/UCB-AI-ML-PA-III/assets/146776815/b49eff3a-3e7d-4513-87bf-0430daeb1a5d)

 The overall recommendations for the marketing campaign are: 
1. Focus on previous marketing campaigns that were successful and retarget those clients with new marketing campaigns, since there is a precedent of success with those clients. 
2. Reflect on previous successful marketing campaigns and analyze their advantages and disadvantages, then improve areas of weakness.
3. Tailor and target market campaigns to those clients with the professional statuses of student, retired, and unemployed. 


