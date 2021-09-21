# PredictApparentTemperature
Given dataset of Weather in Szeged 2006-2016. We trained model using Linear Regression algorithm.
Here we trained our model using Apparent Temperature. Because in Temperature column and in Apparent temperature according to humidity there was same graph. That's why there was no need to find the best. We prepared dataset to train by splitting it to train and test sets(train - 80%, test - 20%). We used Linear Regression algorithm to train our model. Also we added random_state to 1 in code to make dataset random for better training. 

After training its coefficients and etc. was:

Coefficients: [-32.96509622]

Mean squared error: 72.96

Coefficient of determination: 0.36.

Also its score was 0.36309158378316886.

For example we predicted 5 values. Here is it: 

[5.74679035 6.73574324 5.74679035 7.72469613 7.72469613]

[7.38888889 7.22777778 9.37777778 5.94444444 6.97777778]

Here are graph of Temperature and Apparent Temperature according to Humidity:

![Temp](https://user-images.githubusercontent.com/69037042/134175571-263a7bdf-5bb9-4b11-a7bc-0b4cfa1800b3.png) 
![AppTemp](https://user-images.githubusercontent.com/69037042/134175651-58262347-caa5-41e9-993d-4a21b0cfb0ea.png)

Here is model's graph:

![ModelPred](https://user-images.githubusercontent.com/69037042/134175837-c77b071a-480b-4f1b-91df-516a44bc72a9.png)
