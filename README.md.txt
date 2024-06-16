## PreInterviewAssessment

# Introduction to the project
This project aims to show with which indicators the candidates are accepted to the interview.

# How to open an IPYNB file.

1. Clone this repository to your local machine: git clone https://github.com/vladsargsyan/PreInterviewAssessment.git
2. Install Jupyter Notebook on your workstation. Alternatively, open the application if Jupyter Notebook is already installed
3. Double-click the Tips.ipynb file in the Jupyter application. This should open the IPYNB file in a separate tab. Running each time you will get different output as the test size is 30% of the existing data.

# Output example
As the output, you can see the classification report and confusion matrix.

	Model					Acc			Auc
0	Logistic Regression		0.908482	0.62
1	Naive Bayes				0.968750	0.86
2	KNN						0.883929	0.92

 # Used libraries
- Pandas is used to analyze data.
- Seaborn is a Python data visualization library based on matplotlib.
- OrdinalEncoder preserves the ordinal relationship between categories by assigning them ordinal integer values.
- StandardScaler is a preprocessing technique in scikit-learn used for standardizing features by removing the mean and scaling to unit variance.
- Logistic regression is a supervised machine learning algorithm used for classification tasks where the goal is to predict the probability that an instance belongs to a given class or not.
- Gaussian Naive Bayes is a type of Naive Bayes method where continuous attributes are considered and the data features follow a Gaussian distribution throughout the dataset.
- The K-Nearest Neighbors (KNN) algorithm is a supervised machine learning method employed to tackle classification and regression problems.