## Busy devs' guide to timeseries forecasting

### stationarity
After data is put in a proper model we plot it with x-axis being the time/date and y axis being the regressed value
If the statistical properties of the data changes over time i.e. there are trends in the data (increaing over time or decreasing) like having weird 2020 covid spikes then we need to normalize the data before using the model to predict

### Evaluation
Usually a subset of the dataset is left for evaluation, for example if the data set is for days/ weeks of 2019 and 2020 then we leave last 3 months of 2020 as testing data and the rest being the training data.

### handeling missing values/days