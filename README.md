## [Project 1: DashMed Package Overview](https://github.com/mattangoh/DashMed)
* A PyPi package made for medical professionals to use in medical office settings
* Combines SQLite databases with simple dashboard tools
* Users can quickly import patient data from .csv files into a database and view on user-friendly dashboards
* Includes feature to create and view blood pressure data trends on a line chart
* Inludes user control features to see who can update, insert, or change patient data records

![Example blood pressure chart](/images/bloodpressure.png)

*Figure 1: A blood pressure chart presenting the diastolic, systolic pressure and the heart rate of a patient over the course of a year.*

![Example terminal dashboard](/images/dashboard.png)

*Figure 2: A dashboard presenting the information of a patient.*

## [Project 2: Supervised Learning to Grade Quality of Milk](https://github.com/shaytran/DATA572_PROJECT.git)

* Using `sklearn` to build a Logistic Regression and Random Forest Model to predict the grade quality of milk
* Trained models to use 6 features (ie. turbidity, pH, etc) to predict the quality of milk (ie. high, medium, low).
* Prepared the dataset by encoding categorical variables, mapped ordinal categories to numerical values, and a applying a train-test split.
* Compared and contrasted performance of both models by using `matplotlib` to visualize non-linearity of the data, misclassification rates, and importance of variables.

![Misclassification box](/images/box.png)

*Figure 1: Boxplot displaying the 10 fold cv misclassification rate between the two models*

![Logistic Regression Confusion Matrix](images/lr_cm.png)

*Figure 2: Confusion matrix for logistic regression model*

![Random Forest Confusion Matrix](images/rf_cm.png)

*Figure 3: Confusion matrix for random forest model*

## [Project 3: FOOTBALL-API Wrapper](https://github.com/shaytran/footwrap.git)

* An API wrapper R package called `footwrap` that handles data from the API-FOOTBALL from RAPID_API
* Comprised of functiosn that wrangle and visualize data on numerous football statistics, including teams, players, and country
* Parsing through data and creation of clean, ready-to-work-with data frames
* Employs `ggplot2` and `gt` libraries to create visualizations and aesthetic displays of data and insights


![Example blood pressure chart](/images/func.png)
![Example terminal dashboard](/images/bar.png)

*Figure 1: Example use of the `GetBiggestVenues` function.*

## [Project 4: Canadian House Market Model & Analysis Overview](https://github.com/shaytran/housemarket_analysis.git)

* An R-based analysis project focused on the housing market
* Utilizes statistical tools like `corrplot` in R for correlation analysis
* Employs data visualization techniques using `ggplot2` to illustrate the relationships between different economic indicators
* Implementation of Random Forests and LASSO to build a model to predict average house prices in Canada in future years based on previous statistics
* Evaluation of the models based on statistical indicators like MSE

![Example blood pressure chart](/images/economicfactors_plots.png)

*Figure 1: Line plots of the economic factors from 2013 to 2021.*

![Example terminal dashboard](/images/corr.png)

*Figure 2: Correlation plot using `corrplot` to observe how the 8 economic factors are correlated to one another.*
