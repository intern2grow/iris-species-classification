# Machine Learning Task: Iris Species Classification

This task has been prepared for the Machine Learning Engineer Virtual Internship Program in Intern2Grow.

## Objective

Your task is to build a machine learning model that can classify the species of iris flowers based on their features.

## Dataset

You are provided with a dataset in CSV format with the following columns:

- Sepal_Length: The length of the sepal.
- Sepal_Width: The width of the sepal.
- Petal_Length: The length of the petal.
- Petal_Width: The width of the petal.
- Class: The species of the iris (e.g., setosa, versicolor, virginica).

## Task Breakdown

1. **Data Preparation**: Load the dataset from the CSV file. Perform any necessary data cleaning and preprocessing tasks, such as dealing with missing values, outliers, or encoding categorical variables.

2. **Exploratory Data Analysis (EDA)**: Analyze the dataset to gain insights about the distribution of variables, correlation between features, etc. This may involve creating visualizations such as scatter plots, histograms, or box plots.

3. **Feature Selection**: Decide which features from the dataset you will use to train your model. The goal is to predict the class of the iris, so this is your target variable.

4. **Model Selection**: Choose an appropriate machine learning algorithm for this classification task. Justify your choice.

5. **Model Training**: Split the dataset into a training set and a test set. Use the training set to train your model.

6. **Model Evaluation**: Use the test set to evaluate the performance of your model. You may use appropriate metrics for classification tasks such as accuracy, precision, recall, or F1-score.

7. **Prediction**: Finally, use your trained model to predict the class of a new iris flower given its features.

## Deliverable

Submit a report detailing your approach, methodology, and results. Your report should include:

- An explanation of your data cleaning and preprocessing steps.
- The features you selected and your rationale behind this selection.
- The machine learning algorithm you chose and why you chose it.
- The results of your model evaluation, including the metrics you used.
- A discussion of any challenges you faced and how you overcame them.

Also, submit your code files along with your report. Your code should be well-commented and easy to understand.

## Tips

- Pay attention to the distribution of the classes. If the classes are imbalanced, you may need to use techniques such as resampling or choose a model that can handle imbalanced classes.
- Consider using regularization to prevent overfitting if necessary.
- Remember to standardize or normalize your features if you're using a model that's sensitive to the scale of the features, such as k-nearest neighbors or support vector machines.
