# Route Optimizer for Swiss Online Supermarket Delivery
1	Introduction an Aim of the study
The aim is to quantify potential improvements with state-of the art route optimization based on the last mile delivery on a practical case. The optimization of the travel routes for a delivery vehicle is a two-component problem. First, a machine learning model trains on the data to predict the two respective round trip timeseries. The training is based on weather data, traffic data and historical structures (seasonalities, non-normal distribution and probabilities). Second, these predictions are fed into the open source algorithm which decides the most time efficient visit order for a given set of customers. By using Amazon’s Web Service (AWS), the following model is applied:

https://github.com/vlazovskiy/route-optimizer-machine-learning
