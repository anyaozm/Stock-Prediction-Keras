# Stock Predictions using Keras
Stock Market Predictions Keras for CSV files 

I used MatPlotLib to plot out the forecasts and compare them to the real values
The predictions are for the X_test split value which is in the past
Future predictions can be also made with the model
This model looks solely at patterns and uses a regression model with squared error

The model can be improved with 
-More training 
-Bigger datasets

You can swap any other singular stock
A good site to find more stock data -- https://finance.yahoo.com/
From yahoo you can adjust the time frame and dividens as well

if you don't have it already you will have to pip install pandas, keras, matplotlib, sklearn and the other libraries used\

An alternative to the Forecast method could be to use an SVM model overfitting could be a concern for SVM

# Dependencies

- [ ] Numpy
- [ ] Matplotlib
- [ ] Scikit Learn
- [ ] Keras
- [ ] Tensorflow
- [ ] Math
- [ ] Pandas

## STEPS
- [x] Import dependencies
- [x] Load Training Features Data
- [x] Turn data into a pandas data frame and Display
- [x] Replace the strings in thal column with corresponding numbers
- [x] Turn features into numpy arrays  
- [x] Check shape
- [x] Split the model 
- [x] Build the Model
- [x] Compile
- [x] Fit and train
- [x] Let's Evaluate Our Model with the loss function and accuracy
