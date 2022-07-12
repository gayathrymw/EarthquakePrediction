## MathematicsProject-2<br />
## Earthquake Prediction using Linear Regression<br />
Earthquake Prediction is a way of predicting magnitude of earthquake based on parameters such as longitude, latitude, depth, and duration magnitude, country, depth using machine learning to give warning of potentially damaging earthquakes early enough to allow appropriate response to the disaster, enabling people to minimize loss of life and property.<br />
The steps we have taken here are:<br />
     Preparing the dataset<br />
     Building a model with Linear Regression<br />
     Visualization with Matplotlib and Seaborn<br />
With the help of Python and suitable machine learning algorithms, we can create prediction models and graph the data as we want. In this project, one of the parameters of the earthquake data as a csv file is predicted with the help of Linear Regression, an algorithm of Machine Learning.<br />
# Dataset Information<br />
Earthquake data can be taken from :<br />
https://www.kaggle.com/datasets/caganseval/earthquake <br />

Here we used Turkey's earthquake data and one of the occured earthquakes in Kocaeli in 2007 that has maximum magnitude 4.0 is guessed as 4.05 with linear regression. In order to generate training and test data, other variables like longitude, latitude, depth, and duration magnitude are also used.<br />

The parameters are:<br />
Id: order number of the earthquake<br />
Date: earthquake occurrence date<br />
Time: time of the earthquake<br />
Lat: latitude of the earthquake epicenter<br />
Long: longitude of the earthquake epicenter<br />
Country: country of the earthquake epicenter<br />
City: province of the occurred earthquake<br />
Area: region of the occurred earthquake<br />
Direction: direction of the earthquake signal<br />
Dist: district of the occurred earthquake<br />
Depth: depth of the occurred earthquake (distance from the surface)<br />
Xm: the largest of the given magnitude values<br />
Md: magnitude depending on time<br />
Richter: Richter magnitude or the local magnitude (ML)<br />
Mw: moment magnitude<br />
Ms: surface wave magnitude<br />
Mb: body wave magnitude<br />

