# Traffic Accident Severity Prediction using Artificial Neural Network

## Introduction

This project aims to predict the severity of traffic accidents using an Artificial Neural Network (ANN). The dataset used in this project covers traffic accidents across 49 states of the USA, collected from February 2016 to March 2023 through various APIs that broadcast traffic incident data.

## What is an Artificial Neural Network (ANN)?

An Artificial Neural Network (ANN) is a computational model inspired by the structure and functioning of the human brain's neural networks. It consists of interconnected nodes called neurons organized into layers. These layers typically include:
- An input layer
- One or more hidden layers
- An output layer

ANNs have been widely used in various fields, including machine learning, pattern recognition, computer vision, and natural language processing.

## Dataset Overview

- **Source**: The dataset encompasses US accidents from 2016 to 2023 and can be obtained from Kaggle.
- **Attributes**: The dataset includes attributes such as location (latitude and longitude), time of accident, weather conditions, road conditions, severity of accidents, and possibly contributing factors like visibility and traffic congestion.

### Features in the Dataset
- Severity
- Start_Latitude
- Start_Longitude
- City
- Temperature(F)
- Humidity(%)
- Pressure(Pa)
- Visibility(mi)
- Wind_Direction
- Wind_Speed(mph)
- Precipitation(in)
- Weather_Condition
- Amenity
- Bump
- Crossing
- Give_Way
- Junction
- No_Exit
- Railway
- Roundabout
- Station
- Stop
- Traffic_Calming
- Traffic_Signal
- Civil_Twilight
- Year
- Month
- Weekday
- Day

## Methodology

We utilized a Multilayer Perceptron (MLP) classifier, which is an ANN with three layers:

1. **Input Layer**: Contains 30 neurons, corresponding to the number of features in the dataset.
2. **First Hidden Layer**: Contains 16 neurons.
3. **Second Hidden Layer**: Contains 8 neurons.
4. **Output Layer**: Contains 1 neuron.

The main activation function used is ReLU (Rectified Linear Unit), and the final neuron activation function is Limited-memory BFGS (L-BFGS or LM-BFGS), a popular optimization algorithm in the family of quasi-Newton methods.

## Results and Discussion

### Metrics on Train and Test Datasets

- **Precision**: Number of true positives divided by the sum of true positives and false positives.
- **Recall**: Ratio between the number of positive samples correctly classified as positive to the total number of positive samples.
- **F1 Score**: Measure of a model’s accuracy, used to evaluate binary classification systems.
- **Support**: Refers to the connections and interactions between units (neurons) within the network.

### Histograms

- Visualization of the distribution of various features and target variables.

## Conclusions

1. **Dataset Overview**: 
   - The dataset includes various attributes like location, time of accident, weather conditions, and more.
2. **Importance and Utility**:
   - **Understanding Accident Trends**: Reveals trends in accident frequency, seasonal variations, and notable spikes.
   - **Identifying High-Risk Areas**: Helps in identifying regions with high accident frequency.
   - **Examining Contributing Factors**: Provides insights into factors contributing to accidents.
3. **Potential Applications**:
   - **Predictive Modeling**: Helps in forecasting accident occurrence and severity.
   - **Safety Interventions**: Guides the implementation of safety interventions.
   - **Policy Decision Support**: Informs decisions related to transportation infrastructure investments.

## Acknowledgments

Thank you for exploring this project. The dataset and methodologies applied in this project offer significant insights into road safety dynamics and pave the way for improved safety measures and policies.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
