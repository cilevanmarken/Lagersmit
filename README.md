# Lagersmit
Code for the Lagersmit Master Challenge. Group: Learn and Deciden


The Lagersmit Supreme Ventus sealing system prevents ships from leaking oil. When a vessel is leaking more than a specified limit, the ship should go to a dry dock for maintenance. It is therefore useful to predict if and when the leakage will surpass this limit. Using various measurements from the Supreme Ventus sealing system, a prediction was made using a Long Short-Term Memory (LSTM) Neural Network. The model, after training on coastal data provided by Lagersmit, was able to make a rough prediction for a week based on a week of historical data. However, because of restrictions in data, the model was not good enough to determine if a ship had to go to a dry dock for maintenance or not. To make useful predictions for the future, an advisory report has been composed. This advisory report contains suggestions on improving the current gathering of data and on expanding the current features with for instance UCT time and GPS location. 

# Files
Clean_data - pre-processing of data

Display_data - making visualisations of data

Make_graphs - making graphs of resulting predictions using a loaded model from folder 'Model'

Train_model - training the model on pre-processed data

Model - the model, can be loaded for use with 'keras.models.load_model(path)'

