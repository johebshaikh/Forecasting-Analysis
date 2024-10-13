# Forecasting-Analysis

## Introduction
Air pollution is a major issue of our time, affecting both climate change and public health. Harmful pollutants, particularly Particulate Matter (PM), pose serious health risks by entering the respiratory system and causing diseases such as respiratory and cardiovascular illnesses, reproductive issues, and cancer. Human activities, especially the emission of greenhouse gases like carbon dioxide, significantly contribute to climate change, making it a critical global concern.

Flowering patterns are crucial for understanding plant reproduction and pollinator activity. The timing of flowering and leaf blooming is influenced by seasonal climate variations, and flower colors may shift across seasons. The Rank-based Order similarity metric helps analyze the consistency of annual flowering and blooming patterns.

Research on mortality and flowering prediction uses time-series regression and exponential smoothing techniques. These models are applied to forecast future trends in mortality and First Flowering Dates (FFD), providing valuable insights into public health and environmental dynamics.

## Task 1
Time series analysis and forecasting of disease-specific weekly mortality in relation to temperature, pollutant size, and noxious chemical emissions levels

## Task 2
The task is to represent Time series analysis, model the FFD (first flowering day), and provide the best FFD 4-year projections for the FFD series.

## Task 3
The task is to conduct an analysis using univariate climate regressors and the best available models from the employed methodologies to provide accurate 3-year forecasts for the Rank-based Order (RBO) series. This involves performing the appropriate analysis to obtain the most reliable 3-year ahead forecasts for the RBO series

## Conclusion 
The Damped additive and Multiplicative seasonal damped models were the most effective at capturing seasonality and serial correlation in mortality data, both minimizing MASE to 0.6871. Based on these results, the Damped additive technique was chosen for accurate mortality forecasting. In the case of FFD data, the Polynomial DLM_radiation method proved to be the best fit, successfully capturing patterns and minimizing MASE to 0.5130, making it the preferred choice for forecasting. For RBO data, a univariate time series regression approach was initially applied, and after comparing models, the dynamic method was selected for further analysis. Model 6, which reduced MASE to 0.6056, was identified as the most suitable for providing accurate 3-year forecasts.
