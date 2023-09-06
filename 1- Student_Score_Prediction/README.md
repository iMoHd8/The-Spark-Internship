# Student Score Prediction - Supervised ML

This is the 1st Task in The Internship of The Sparks Foundation in Data Science.

The task is prediction of students' scores using the Linear Regression Algorithm.The main process involves training the model on the data of student scores to create a model that can predict any student's score based on their study time in hours. The dataset contains two main columns: **Hours:** Represents the student study time in hours. and **Scores:** Represents the student's grade.

&nbsp;


> ## Project Overview

- **Regression Algorithm**: RandomForestRegressor
- **Programming Language**: Python
- **Libraries Used**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Dataset Source**: [student_scores.csv](http://bit.ly/w-data)

&nbsp;


> ## Project Structure

The project is organized as follows:

- `Student Score Prediction.ipynb`: Jupyter Notebook containing the Python code for loading the dataset, performing Decision Tree and Random Forest Regression, with Some Visualization.
- `README.md`: This file providing an overview of the project.
- `student_scores.csv`: This is The Used Student Scores Dataset.

&nbsp;


> ## Project Steps

The model follows these steps:

1. **Importing the necessary libraries:** We use libraries such as Pandas, Numpy, Sklearn, and more to work with the data and implement the Linear Regression algorithm.

2. **Exploratory Data Analysis (EDA):** This step involves exploring the data, visualizing it, and understanding its distribution. We may use techniques like creating distribution plots and regression plots to analyze the data.

3. **Initialize the model for the training process:** This includes dividing and splitting the data into training and testing sets and fitting the Linear Regression model to the training data.

4. **Starting the prediction process:** After training, we make predictions using the model.

5. **Comparing the actual label with the model-predicted label:** We assess the accuracy of the model's predictions by comparing them to the actual scores.

6. **Testing the model on new values:** We can use the trained model to predict scores for new data points.

7. **Model Evaluation:** Finally, we evaluate the performance of the model using appropriate evaluation metrics.

&nbsp;

> _This project is a part of The Sparks Foundation's Data Science Internship program._
