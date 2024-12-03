# Predicting Fares Neural Network Model

This project focuses on developing and optimizing a neural network to predict ride fares based on NYC rideshare data. Below are the details of the implementation, dataset, model, and results.
You can learn more about our model training and evaluation through our report [writeup.pdf](https://github.com/anshisinghh/rideshare-fare-prediction/blob/main/writeup.pdf).

## Project Structure

- [hyperparameter_tuning.ipynb](https://github.com/anshisinghh/rideshare-fare-prediction/blob/main/hyperparameter_tuning.ipynb): Runs the model with hyperparameter tuning using grid search.
- [neural_model_1.ipynb](https://github.com/anshisinghh/rideshare-fare-prediction/blob/main/neural_model_1.ipynb): Runs the model without feature selection.
- [neural_model_2.ipynb](https://github.com/anshisinghh/rideshare-fare-prediction/blob/main/neural_model_2.ipynb): Runs the model without feature selection.
- [neural_model_final.ipynb](https://github.com/anshisinghh/rideshare-fare-prediction/blob/main/neural_model_final.ipynb): Runs the model with feature selection.

## Dataset

For this assignment, we chose to predict ride fares using features from rideshare datasets due to their quantifiable insights and practical applications. 

### Dataset Source
We used the **NYC Taxi and Limousine Commission (TLC)** trip record data, specifically the **High Volume For-Hire Vehicle (FHV)** trip data from January and February 2022. The dataset comprises around 30 million rows, with each representing a unique trip.

The dataset is publicly available on the [NYC TLC website](https://www.nyc.gov/assets/tlc/downloads/pdf/2022_summary_data.pdf).
