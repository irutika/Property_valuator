# Property_valuator
![image](https://github.com/irutika/Property_valuator/assets/106487590/ba3cb622-9773-4f80-9953-a6db62329e8f)

This project walks me through the step-by-step process of building a property price estimator website.

First, I built a model using scikit-learn (scikit-learn) and linear regression. The model was trained on a Bangalore home prices dataset obtained from Kaggle.com.
Then, I created a Python Flask server that utilizes the saved model to handle HTTP requests.

Finally, I developed an interface using HTML, CSS, and JavaScript. This interface allows users to enter details like home square footage, number of bedrooms, etc. It then calls the Python Flask server to retrieve the predicted price.

During model building, I covered essential concepts like:

Data loading and cleaning
Outlier detection and removal
Feature engineering
Dimensionality reduction
GridSearchCV for hyperparameter tuning
K-fold cross-validation

The project utilizes the following technologies and tools:

Programming Language: Python
Data Manipulation: NumPy and Pandas
Data Visualization: Matplotlib
Machine Learning: scikit-learn
Development Environments: Jupyter Notebook, Visual Studio Code, or PyCharm
Web Framework: Flask
Front-end Development: HTML, CSS, JavaScript


