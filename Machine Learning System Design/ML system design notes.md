# Chapter 1
## 1.1 Introduction -
- To understand the challenges early on at a structural level:

*Problem Statement*
What's the intention of the design? What and why we want to optimize?

*Identify Metrics*
Use quantified metrics to quickly test the model, e.g. `logloss` (the `logistic loss` and binary `cross entropy loss` (Log loss) are in fact the same) and [`AUC`](https://en.wikipedia.org/wiki/Receiver_operating_characteristic) for binary class, `RMSE` and [`MAPE`](https://en.wikipedia.org/wiki/Mean_absolute_percentage_error) for forecast.


*Identify requirements*
Training requirements: feature engineering, featur selection, loss function
Inference requirements: real-time model balance high availability and low latency?

*Train and evaluate model*
feature engineering, featur selection, models

*Design high level system*
Think about system components and how data flows through them.

*Scale the design*
Understand and pinpoint the bottlenecks

## 1.2 Feature Selection and Feature Engineering