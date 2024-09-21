# Lottery_Prediction
Simple LSTM-based lottery forecast deep learning model.

# Dependancy

* tensorflow >= 2.0
* keras
* sklearn
* numpy 
* pandas




# Running

run ``main.py`` script

or in your prompt, type

``python main.py --data_dir 'dataset/lottery_history.csv' --mode 'eval_model' --trial 5 --training_lengt 0.90 ``  

dataset version is on the date: [26.08.2023]


***Arguments:***

training_length : there are ~980 lottery cases in total. you can decide to what extent to use as for training length.
(e.g. 0.5 training_lengh uses 485 lottery cases are used for training and infer 486 th as a test set.)

