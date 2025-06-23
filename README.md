# Corporate Credit Rating Prediction System

## Project Description

This project aims to predict the **Corporate Credit Rating**, which represents an independent agency's opinion on a company's ability to meet its financial obligations. Using **supervised learning** and **probabilistic reasoning** techniques, the system automates corporate risk assessment, classifying companies based on their financial soundness.

The project uses **Machine Learning** models such as Decision Tree, RandomForest, XGBoost, and LightGBM to predict the rating, and includes a **Bayesian network** to make probabilistic inferences on the data.

## Project Structure

1.  **Data Preprocessing**
    -   Cleaning and preparing the dataset using techniques like normalization and one-hot encoding.
    -   Reducing the rating classes from 22 to 4 main categories representing minimum-low, medium, medium-high, and high-default risk.

2.  **Supervised Learning**
    -   Use of models such as Decision Tree, RandomForest, XGBoost, and LightGBM.
    -   Testing various class rebalancing techniques, such as SMOTE and ADASYN.

3.  **Bayesian Network**
    -   Creation of a Bayesian network to handle cases of missing data and generate new predictions based on probabilistic evidence.

## Results

The results show that the **SMOTE**-based approach yielded the best overall performance, particularly with the **RandomForest** and **XGBoost** models. The metrics used for evaluation include Balanced Accuracy, Cohen's Kappa, and Geometric Mean.

## Future Developments

-   Increase the amount of data to improve prediction accuracy.
-   Further explore the use of neural networks for classification.
-   Integrate additional variables for a more comprehensive and accurate analysis.
