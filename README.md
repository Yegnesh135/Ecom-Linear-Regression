# Ecom-Linear-Regression
Empowering Ecom with the insights through Linear Regression.

This is a real kind of problem usually companies wish to get solved. Rather learning how to developing models and using them for prediction it is crucial to learn how to answer the business questions with the data provided upon employing the models. 

In this problem a Ecom company have a online clothing company which does its business on an app and also on a website. The company also have a brick and motor store where it provide sessions with personal stylist helping the customers to choose over a wide variety of options. Now this company wants to improve it services with aim of minimum efforts and maximum effect. Thus it wants to choose one of app and website to improve on so as to improve the sales.

I obtained the data in a very raw form. As it is limited and redundant data, I used excel and its best available formulas for possible cleaning and made ready for pandas. Once the data made available to python using pandas framework, the statistical operation begins. 

It get started with usual statistical evaluations such as description, info and shape. Then to find the correlation matric to show how each other columns are related to each other. Further I made use of both matplotlib and seaborn for the visualization and personaly tasted the hardships and simplisity of using one over the other at the place of requirement.

Then finally reached on importing the scikit learning using sklearn command. Then the very first step is to split the data into training data and testing data with random_state be '101' to keep the split data fixed all the time.

Then it goes the routine way of calling linear regression and fit the data on it. Then do the predictions and see the performance by obtaining residual sum of squares such as MAE (Mean Absolute Error), MSE (Mean Squared Error), RMSE (Root Mean Squared Error). I got some good outcomes which indicates a good model performance. But it doen't end here.

Now its time to look at the coefficients or the weights obtained to find the column that have greated effect on its unit change upon the target. On obtaining the coefficients, it is observed that Time on App is having greater weight on the Yearly Amount Spent by the customer. Thus improving the App will improve the business compared to the other ones.
