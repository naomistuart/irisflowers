# irisflowers
This project uses the classic iris dataset - considered the "Hello World" of machine learning - to build a simple machine learning pipeline. The goal is to classify the flowers into one of three iris species, based on the length and width of their petals and sepals.

Using the python library [scikit-learn](https://scikit-learn.org/stable/index.html), multiple machine learning algorithms are evaluated, with the best-performing one selected.

The Jupyter Notebook includes interactive sliders, where users can input flower measurements and watch as a prediction is made, classifying the flower into an iris species.

## Data
[Iris Data Set](https://archive.ics.uci.edu/ml/datasets/iris) from the UCI Machine Learning Repository.

This dataset contains three classes of 50 instances each, where each class refers to a type of iris plant. There are four attributes for each instance: sepal length, sepal width, petal length and petal width.

## Machine learning steps
1. Load dataset
2. Preview dataset (summary statistics etc.)
3. Perform exploratory data analysis & visualisation
4. Split data into training and test sets
5. Evaluate multiple machine learning algorithms on the training set, using cross validation
6. Choose the best performing algorithm and test using the test set
7. Make prediction from user-inputted data

## Built with
- [Jupyter Notebook](https://jupyter.org/) to run python code and display results
- [scikit-learn](https://scikit-learn.org/stable/index.html) python library for machine learning tools
- [matplotlib](https://matplotlib.org/) and [seaborn](https://seaborn.pydata.org/)python libraries for plotting and data visualisation
- [ipywidgets](https://ipywidgets.readthedocs.io/en/stable/index.html) for interactive sliders embedded in Jupyter Notebook 

## References
- [https://machinelearningmastery.com/machine-learning-in-python-step-by-step/](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)
- [https://scikit-learn.org/stable/tutorial/basic/tutorial.html](https://scikit-learn.org/stable/tutorial/basic/tutorial.html)
- [https://scikit-learn.org/stable/modules/cross_validation.html](https://scikit-learn.org/stable/modules/cross_validation.html)