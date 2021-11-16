# Ryan Hass DS Portfolio

I am currently pursuing a Master's degree in [Data Science](https://datasciencedegree.wisconsin.edu/) from the University of Wisconsin - Green Bay. I will earn my Graduate Certificate in December of 2021 and anticpate to graduate with my M.S. in May of 2023.

I have completed (or am currently enrolled in) the following coursework: DS700 - Foundations of Data Science, DS705 - Statistical Methods, DS710 - Programming for Data Science, DS715 - Data Warehousing, DS735 - Communicating about Data, DS740 - Data Mining and Machine Learning, DS780 - Data Science and Strategic Decision Making.

I have yet to complete the following: DS730 - Big Data: High-Performance Computing, DS745 - Visualization and Unstructured Data Analysis, DS760 - Ethics of Data Science, DS775 - Prescriptive Analytics, and DS785 - Capstone.

Below I have highlighted some relevant project work from both my academic and professional experiences.

# [Project 1: Loan Default Prediction](https://github.com/hassrm08/Loan_Predict)

The final project for DS 705 - Statistical Methods included the observation, cleaning, and analysis of loan data to predict the likelihood that a potential borrower would default on their loan.

Data was taken from 50,000 loans using 30 variables.

The methods of analysis include a logistic regression model that was derived from the most relevant variables within the given data set including income, employment status, interest rate, salary, loan term, and overall applicant grade.

![](images/Loan%20Default%20Profit%20Threshold.png)

# [Project 2: Music Genre Popularity](https://github.com/hassrm08/Genre_Twitter_Analysis)

The final project for DS 710 - Programming for Data Science included an open ended analysis fo Twitter data using the Twitter API.

I chose to evaluate the popularity of musical genres based on their perceived popularity on Twitter. Popularity is determined in two ways. First, by overall tweet count then by the number of exclamation marks used within those tweets.

Tweets were collected using the REST API through Python. The program grabbed (up to 5000) tweets that were categorized into genres.

Two methods were used (in R Studio) in order to evaluate the relationship between tweet count and exclamation mark count by genre. First, I evaluated the potential for a linear relationship between both variables. The variables were plotted against one another in a scatterplot (Figure 3), and a summary of the linear model was created. Secondly, the variables (Tweet Count & Exclamation Count) were compared in a Chi Squared Test of Independence.

![](images/Exclaims%20by%20Tweet.png)

# [Project 3: Double Cross Validation](https://github.com/hassrm08/Double_CV)

The Double Cross Validation project is the Midterm project for DS740 - Data Mining and Machine Learning.

The goal of this project was to evaluate means of predicting the retail price of vehicles based on the predictors variables provided.


Additionally, model selection and assessment was done to determine the overall accuracy of the model as well as the model selction process using double cross validation techniques.

The analysis was done using the 'caret' package in R.

# [Project 4: Paper Quality Testing Gage Comparison](https://github.com/hassrm08/GBP_Data_Analysis)

The purpose of this study is to compare the reproducibility and repeatability of two testing methods using Gage R&R. The test methods being compared are Concora and S-Test.  Both tests measure sheet strength in the machine direction (MD).  Because the test methods measure strength differently, Gage R&R is used to compare a common measurement.

![](images/Gage%20Report.gif)
