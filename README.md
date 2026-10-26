# Probability-and-Statistical-Analysis
This project explores basic probability and statistical concepts using a diabetes dataset. It covers probability, independence, conditional probability, BMI distribution, variance, skewness, and Naive Bayes to analyse relationships between health and lifestyle factors.


Overview

Python is used to analyse relationships between health-related variables such as BMI, age, income, smoking habits, fruit and vegetable consumption, and diabetes status.

Dataset

The dataset contains health and lifestyle information about individuals, including:

* BMI: Body Mass Index.
* Age: Age categories of individuals.
* Income: Income categories.
* Fruits and Veggies: Regular fruit and vegetable consumption.
* Smoker: Smoking status.
* Diabetes_012: Diabetes classification (0 = No diabetes, 1 = Prediabetes, 2 = Diabetes).

What We Did

1. Probability and Independence

Calculated the probabilities of individuals consuming fruits, vegetables, and both. We also investigated whether fruit and vegetable consumption are independent events.

2. Conditional Probability

Calculated the probability of diabetes among individuals who regularly consume fruits and vegetables. We explored the difference between statistical association and causation.

3. BMI Distribution

Created a histogram to visualise BMI values and examined whether the distribution follows a normal distribution.

4. Variance and Skewness

Calculated variance and skewness for BMI across different income groups to understand differences in data spread and distribution shape.

5. Naive Bayes and Full Conditional Probability

Applied Naive Bayes to estimate conditional probabilities using BMI, age, diabetes status, and smoking habits.

We also explored full conditional probability, which uses the observed joint distribution without assuming conditional independence between features.

Key Learnings

* Understanding basic, joint, and conditional probabilities.
* Identifying independence between events.
* Understanding the difference between correlation and causation.
* Visualising and interpreting data distributions.
* Calculating variance and skewness.
* Applying Bayes’ theorem and Naive Bayes.
* Understanding the difference between Naive Bayes and full conditional probability.

Tools Used

* Python
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

Conclusion

This project demonstrates how probability and statistical methods can be applied to real-world health data. It also provides practical experience in analyzing distributions, calculating conditional probabilities, and understanding how independence assumptions influence probability estimates.
