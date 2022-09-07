# Absenteeism_at_work
The project will address Absenteeism at a company during work time. It will work on predicting Absenteeism from work, whether or not an employee will be absent for a specific number of hours on a work day. It will explore whether a person presenting certain characteristics is expected to be away from work at some point in time or not.
-----------------------------------------------------------------------------------------------------------
1] Data_preprocessing_absenteeism notebook does preprocessing of the dataset 'Absenteeism_data.csv' and generates new preprocessed dataset 'Absenteeism_preprocessed.csv'
2] ML_topredict_absenteeism notebook contain code to train logistic regression model on the 'Absenteeism_preprocessed.csv'.
3] absenteeism_module python file is a module that contains the code for data preprocessing and logistic regression model code that can be applied on new test data.
4] Absenteeism_Integration notebook tests the absenteeism_module python file on new test data of 'Absenteeisn_new_data.csv'. The predicated output for the new test data is stored in MySql.
5] Dataset results are also visualized in Tableau 
Hint- Make sure absenteeism_module is a python file and in the same folder, else project wont work
