# MLB Baseball Analytics with Machine Learning

In this project, we are going to use machine learning models to predict the number of games that a Major-League Baseball team won that season based on the team's stats and other variables for the season.

### Data

The data for the 2016 MLB season is already compiled by Sean Lahman on his [website.](http://www.seanlahman.com/baseball-archive/statistics/)

Then the data was transformed into an SQLite database [here.](https://github.com/jknecht/baseball-archive-sqlite)

### Technologies/Tools Needed

### Predictive Model
- In the first notebook, "1_machine_learning_with_baseball_stats.pynb", we are importing data from an SQLite database, clearning and preprocessing data, conducting exploratory data analysis (EDA) and inspecting visually using plots, and engineering several new features. We used K-Means clustering to feature engineer new features. And the predictive model was developed using Linear Regression and Tree-based models.
	- Technologies/Methodologies Used: Python, Scikit-Learn Numpy, Pandas, Matplotlib, Seaborn, SQLite, Jupyter Notebooks, K-Means Clustering, Silhouette Score, StandardScaler, Pipelines, GridSearchCV, ElasticNet, Ridge, Lasso, RandomForest Regressor