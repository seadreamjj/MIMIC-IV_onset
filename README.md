# MIMIC-IV_onset
Use the MIMIC dataset to develop a pipeline/model to detect and differentiate the onset of any kind of acute event. These could be circulatory shocks, heart attacks, pheumothorax etc. The choice of acute event is entirely upto you. Your approach should be to first develop a model to predict a static onset, and then to extend that further to predict ahead of time. For example, the baseline model should predict WHEN the event starts, and a dynamic model should predict the event AHEAD of time (time windows of 1,2,3,4 hours). 


----The order for static prediction of sepsis
To run the file, begin with reading data from diagnosis of sepsis, lab_data_for_sepsis, chartevents_preprocessing, sepsis_other_data, and get the 4 csv file. 
Then go to Sepsis Static Onset Prediction for data cleaning and model construction. (The backward elimination method for feature selection is also avaiable in the file: backward_elimination.ipynb)
