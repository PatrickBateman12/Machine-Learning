# OpenLab-Machine-Learning
How to collect data and train a ML model

For collecting data from OpenLab Drilling Simulator use the following 4 scripts

1. For drilling without incidents use Training Data Without Incidents
2. For drilling with influx use Influx Model
3. For drilling with loss use Loss Model
4. For Increased FlowRateIn every 90 seconds, use Increase in FlowRate on BHP

A tool for concatting all csv files that have been made and saved to one folder, use this code:

1. Script to concat all the files (In this code you can choose whether to proceed with only int64 & float64 or not)

For cleaning and splitting the data into three different methods, use the following 3 scripts:

1. Split 1 (600 timesteps with random sampling)
2. Split 2 (600 timesteps sequentially)
3. Split 3 (Split each unique simulation ID - 420/60/120)

NB! The desired splits have to be ran before using the desired Machine Learning Split (RF, XGG, ADA, LSTM and Sensitivity Analysis)

For Sensitivity Analysis, you have to go run Split 2 first, then you can use the following script:

1. Sensitivity Analysis and RFE

For Machine Learning using RF, XGB and ADA, use the following 3 scripts:

1. Supervised Split 1
2. Supervised Split 2
3. Supervised Split 3

For Machine Learning using LSTM, use the following 2 scripts and if you want to use my trained model you can also download the saved trained model .h5 if you want to use that on the validation and test:

1. LSTM Split2 (LSTM Train Split 2.h5 - if needed)
2. LSTM Split3 (LSTM Train Split 3.h5 - if needed)

