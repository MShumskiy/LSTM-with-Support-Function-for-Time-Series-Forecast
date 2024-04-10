# LSTM-with-Support-Function-for-Time-Series-Forecast

## 0. Introduction and Motivation

The problem of time series forecasting is a recurrent topic in today's world, with applications spanning across various industries. In this work, an alternative method is presented by combining LSTM RNN and Support Function.  
The objective of this notebook is to provide an open moethod that can be appliad to a production ready code, therefore its structure favours flow of logic rather than code optimization for production.

## 1. Objective

The objective of this work is to provide a method for time series forecasting based on LSTM RNN with Support Function.

## 2. Setting

This method will be applicable to any setting similar to the one described below:

- A time series with trend, seasonality, and at least 2 full period iterations;
- The objective is to forecast the future behavior of the time series;
- There is a possibility to extract a support function.

## 3. Method

The method consists of the following steps:

1. Levels Determination;
2. Support Function Extraction;
3. LSTM.
