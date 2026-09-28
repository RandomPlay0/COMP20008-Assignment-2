COMP20008 Elements of Data Processing - Assignment 2
Project Title: Predicting Squirrel Interaction Patterns via Environmental and behavioural Factors
Dataset: 2018 Central Park Squirrel Census

============================================================================
1. TEAM INFORMATION
============================================================================
Members:
- Yuxiang Sun (Student ID: 1677061)
- Jordan Davies (Student ID: 1616823)
- Navya Patet (Student ID: 1604170)


============================================================================
2. PROJECT OVERVIEW
============================================================================
This project analyzes the interaction patterns of squirrels in New York's 
Central Park. Specifically, we investigate how environmental features and 
behavioural featuresinfluence whether a squirrel approaches or 
flees from humans.

We employed a supervised learning pipeline to classify squirrel responses 
and utilized Feature Importance analysis to derive actionable insights for 
urban wildlife management.

============================================================================
3. FILE STRUCTURE
============================================================================
- Squirrel_A2_Analysis.ipynb : The primary Jupyter Notebook containing 
                               preprocessing, EDA, and modeling.
- a1-datasets               : Directory containing the integrated CSV files.
- README.txt                 : This documentation file.

============================================================================
4. IMPLEMENTATION DETAILS
============================================================================
Preprocessing:
 1. Integration of squirrel observation data with hectare-level environmental data.
 2. Handling of missing values via categorical imputation.
 3. Boolean encoding of behavioral traits (e.g., Kuks, Quaas, Moans).
 4. Standardization of continuous variables to ensure distance-metric integrity.

Models Comparison:
 1. Random Forest (Selected for high accuracy and deep interpretability).
 2. Decision Tree (Used for baseline logical flow analysis).
 3. K-Nearest Neighbors (KNN) (Used to evaluate behavioral proximity).

============================================================================
5. DEPENDENCIES & ENVIRONMENT
============================================================================
The following Python 3 libraries are required:
- pandas
- numpy
- scikit-learn(sklearn)
- matplotlib
- seaborn

Recommended Environment: Jupyter Lab (This assignment was built on python 3.10)
============================================================================
6. HOW TO RUN
============================================================================
1. Ensure all dependencies listed above are installed.
2. Place 'a1-datasets.zip' into your downloads folder. The code will extract it
3. Open 'Squirrel_A2_Analysis.ipynb' in a Jupyter environment.
4. Enter your username in first cell where it says username = '' (This should be in the file path from the downloaded zip)
4. Execute cells sequentially. The final sections will output the performance 
   metrics 

============================================================================
7. ACKNOWLEDGMENTS
============================================================================
Dataset provided by the 2018 Central Park Squirrel Census.
University of Melbourne, COMP20008 Semester 1 2026.
