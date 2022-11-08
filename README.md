# Final Project: pCO2 
## Machine Learning for Environmental Engineering
Completed by Julia Simpson, with assistance from Val Bennington and Amanda Fay

Fall 2022



### <span style="color:blue">*Goal:*</span>
#### *Predict pCO2 using sea surface salinity (SSS), sea surface temperature (SST), chorophyll-a, and mixed layer depth (MLD). Use SOCAT observations as the "true" set of values for training.* 

### <span style="color:blue">*Methods:*</span> 
#### *Utilize and compare the following machine learning algorithms:*
- Random forest (RF); 
- eXtreme Gradient Boosting (XGB); and
- Neural network (NN).

*Note: Depending on time, will potentially explore an additional method from the following list: support vector regression (SVR), long short-term memory (LSTM) network, or an ensemble of RF, NN, and XGB.)*
- *if use SVR: look at Gregor 2019 for description*
- *if LSTM: note that this may not work well if the data is not sequential enough*

### <span style="color:blue">*Using Machine Learning Results:*</span> 
#### *Following the training and testing of each of the above machine learning algorithms, I will compare the models and particularly examine the results of the most promising method.*
- Compare approaches
- Possible to apply algorithm globally for reasonable-looking pCO2 predictions? Or without input model, limited to prediction where have SOCAT observations?
- Examine feature importance 



