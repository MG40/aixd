Three notebooks to run
1. On-Prem
2. AWS SageMaker
3. Azure 

This tutorial explicitly shows a complete ML flow of training the XGBoost model from the SageMaker built-in model pool. You use the US Adult Census dataset, and you evaluate the performance of the trained SageMaker XGBoost model on predicting individuals' income.

SageMaker XGBoost – The XGBoost model is adapted to the SageMaker environment and preconfigured as Docker containers. SageMaker provides a suite of built-in algorithms that are prepared for using SageMaker features. To learn more about what ML algorithms are adapted to SageMaker, see Choose an Algorithm and Use Amazon SageMaker Built-in Algorithms. For the SageMaker built-in algorithm API operations, see First-Party Algorithms in the Amazon SageMaker Python SDK.

Adult Census dataset – The dataset from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). The SageMaker XGBoost model is trained using this dataset to predict if an individual makes over $50,000 a year or less.
