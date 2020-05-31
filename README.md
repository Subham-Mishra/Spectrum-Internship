# Spectrum

This project was made as a part of **Spectrum Club Internship in our college**.
In this project, We were provided with a data-set of students with their grades and other attributes associated with the students, 
like their age,gender,address,freetime,studytime and many others.
At the initial stage, we did some data cleaning,preprocessing and visualisation using python libraries like **NumPy,Pandas,Matplotlib,Seaborn**.

Our Job was to make a **Machine Learning model that could predict the students marks** upto an acceptable accuracy by discarding the factors which don't play a vital role in the grades received.

As our Machine Learning Model only understandes numerical values, so we first converted all columns with binary data into 
numerical categories using **Label Encoding**. Then we used a Regression Model to predict the student marks using all attributes.
Finally in order to enhance the accuracy of our model, we checked how each attribute in the data affected the student Grades 
and tried to discard all irrelevant columns and predict the marks using only the most vital factors using **Backward elimination**.

As a future scope to this project,we can use other ML models like Decision tree, Support vector machines and Random Forests
to augment the accuracy of this model. We can even add a UI to this model by dumping the model attributes into a pickle file 
and finally deploying the end-to-end project using flask REST-api to the cloud.
