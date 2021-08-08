# HumanBehaviorModeling
Modeling Human Behaviour from Smartphone data - Keras and Tensorflow
The file titled "MLProject1" contains the code.

Description of Dataset
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

Program Description
#load_file
Use the read_csv() Pandas function to load a single data file and specify that the file has no header and to separate columns using white space.

#load_group
Calls the load_file function multiple times and combines the data files into a single group.

#load_dataset_group
Loads all input and output data for a single group. It can be called for either the train or test group.

#load_dataset
Loads all input and output data for a given folder. Returns train and test X and y elements ready for fitting and evaluating the defined models.

#evaluate_model
Takes the train and test dataset, fits a model on the training dataset, evaluates it on the test dataset, and returns an estimate of the model’s performance. Uses Long short-term memory network model (LSTM) - Keras deep learning library.

#summarize_results
Repeats the evaluation of the model multiple times, then summarizes the performance of the model across each of those runs. 

#run_experiment
Loads the test and train data, repeats the evaluation based on the user's preference, gathers and summarizes the result.


#ADDITIONAL NOTES
For the prefix variable in the code, change the file path appropriately.
