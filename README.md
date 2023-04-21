LINEAR REGRESSION:

Linear regression is a statistical method for modeling relationships between a dependent variable with a given set of independent variables.
Simple linear regression is an approach for predicting a response using a single feature.
In order to provide a basic understanding of linear regression, we start with the most basic version of linear regression, i.e. Simple linear regression.

REGRESSION-PREDICTION-OF-SOLAR:

I'm predict Weather  Dataset using Simple Linear Regression:
START: I get dependent variable is Precipitation columns and independent variable is Wind columns. 
Then unwanted coulums are deleted using DROP key.
locate and reshape the values of X and Y.
Then using the MatPlotLib to visible a Scatter plot of X,Y.
split the values of x and y using train & test methods. 
Thus the simple linear regression was implemented. 

RESULT:
 
 using sklearn find the mean squard error and mean absolute error. 
[mean_squared_error(y_test,y_predict)=1.8446748632743275] [mean_absolute_error(y_test,y_predict)=1.061364374698876]. 

LOOKER STUDIO:
I'm also predict the same data set in looker studio Using table to visible a colums of Date,Temp_min,Temp_max,wind,weather,
i find relationship between weather and count using Bar chart and Pie chart,
i find relatinship between Date and Wind by Weather using area chart,
and i find Relationship between Date and Precipitaion using line chart.
