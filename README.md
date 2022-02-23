# Data_Exploration_Project

The data exploration project is the machine learning project in the same-named lecture in the fourth semester.

The used data can be found [here](https://www.kaggle.com/unsdsn/world-happiness) on Kaggle. In this project the data of the year 2019 is used.</br>
Based on the feature “*Country or region*”, “*Overall rank*”,” *GDP per capita*”, “*Social support*”, “*Healthy life expectancy*”, “*Freedom to make life choices*”, “*Generosity*” und “*Perceptions of corruption*” the target feature "*Score*" will be predicted.

The model will be trained in [this](./trainModel.ipynb) notebook. With **MLFolw** the hyperparemeter of the model will be tuned. This way the best fitting model can be imported in [this](./demo.ipynb) notebook, where the model will be demonstated.

The Elastic-Net model will be trained using the training data, which contains ~67% of the data (105 records) and be evaluated using the validation data, which contains ~22% of the data (35 records). To meassure the errors of the model the metrics *mean squared error*, *mean absolute error* and *mean absolute percentage error* are used.

Later on in the second notebook the best Elastic-Net model will be demonstared using the testing data, which contains ~10% of the data (16 records).

The results can be seen [here](./trainModel.ipynb).
