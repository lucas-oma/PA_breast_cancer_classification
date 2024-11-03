#  CSCI-GA 3033-061 PREDICTIVE ANALYTICS

> Lucas Martinez (lom2017@nyu.edu)

## HW3: Feature Selection and Data Classification Assignment (Fall 2024)

### Objective
The primary objective of this task is to apply data mining techniques to the Surveillance, Epidemiology, and End Results (SEER) Public-Use Data to predict the survivability rate of breast cancer patients. This involves developing a predictive model that can accurately classify patients into survivability outcomes based on a set of features derived from the SEER database.

### Key Tasks
1. **Data Preprocessing**
   - Handle missing values, detect outliers, and apply standardization/normalization.
   - Use dimensionality reduction if necessary.
2. **Modeling**
   - Apply feature selection and feature ranking techniques.
   - Train and benchmark the following algorithms:
     - K-Nearest Neighbors (KNN) – implemented from scratch
     - Naive Bayes
     - C4.5 Decision Tree
     - Random Forest
     - Gradient Boosting
     - MLP Neural Network
   - Summarize the pros, cons, and main hyperparameters for each algorithm.
3. **Hyperparameter Tuning**
   - Perform hyperparameter search on Gradient Boosting and MLP Neural Network using Random Search.
   - Display the best-performing hyperparameters and results.
4. **Results and Analysis**
   - Present results in a table format.
   - Identify the most important features used in classification (if the model allows it).

### Project Structure
- `Breast_Cancer_dataset.csv`: Contains the data used for training and testing.
- `feature_selection_and_classification.ipynb`: Jupyter Notebook detailing the step-by-step implementation.
- `report.pdf`: A comprehensive report outlining the approach, results, and conclusions.
- `requirements.txt`: Requirements for the python environment.
- `README.md`: Overview of the project.
