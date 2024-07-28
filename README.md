# Logistic Regression Ad Click Prediction

This project aims to predict whether an internet user will click on an advertisement based on various features using logistic regression.

## Dataset
The dataset contains the following features:
- **Daily Time Spent on Site**: Consumer time on site in minutes
- **Age**: Customer age in years
- **Area Income**: Average income of the geographical area of the consumer
- **Daily Internet Usage**: Average minutes a day the consumer is on the internet
- **Ad Topic Line**: Headline of the advertisement
- **City**: City of the consumer
- **Male**: Whether the consumer is male
- **Country**: Country of the consumer
- **Timestamp**: Time at which the consumer clicked on the ad or closed the window
- **Clicked on Ad**: 0 or 1 indicating whether the ad was clicked

## Steps
1. **Import Libraries**: Import necessary libraries such as numpy, pandas, seaborn, and matplotlib.
2. **Load Data**: Read the `advertising.csv` file into a DataFrame.
3. **Exploratory Data Analysis**: Use seaborn to create visualizations like histograms, jointplots, and pairplots.
4. **Train-Test Split**: Split the data into training and testing sets.
5. **Train Model**: Train a logistic regression model on the training set.
6. **Evaluate Model**: Predict values for the testing data and create a classification report.

## Results
The logistic regression model achieved an accuracy of 97% on the test set.

## Requirements
- Python 3.x
- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

## License
This project is licensed under the MIT License.
