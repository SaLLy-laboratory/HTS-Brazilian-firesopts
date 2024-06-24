# Hierarchical time series forecasting of fire spots in Brazil: A comprehensive approach: Codes and Datasets

Directory created to share the main files and the codes used in the article "Hierarchical time series forecasting of fire spots in Brazil: A comprehensive approach" published in the journal "Stats".

Abstract - This study compares reconciliation techniques and base forecast methods to forecast a hierarchical time series of the number of fire spots in Brazil between 2011 and 2022. A three-level hierarchical time series was considered, comprising fire spots in Brazil, disaggregated by biome, and further disaggregated by the municipality. The autoregressive integrated moving average (ARIMA), the exponential smoothing (ETS), and the Prophet models were tested for baseline forecasts, and nine reconciliation approaches, including top-down, bottom-up, middle-out, and optimal combination methods, were considered to ensure coherence in the forecasts. Due to the need for transformation to ensure positive forecasts, two data transformations were considered: the logarithm of the number of fire spots plus one and the square root of the number of fire spots plus 0.5. To assess forecast accuracy, the data were split into training data for estimating model parameters and test data for evaluating forecast accuracy. The results show that the ARIMA model with the logarithmic transformation provides overall better forecast accuracy. The BU, MinT(s), and WLS(v) yielded the best results among the reconciliation techniques.

## Files

### Data_Forespots.csv

The data table "Data_Forespots.csv" includes the monthly data, between January 2011 and December 2022, for the total number of fire spots per Brazilian municipality, biome, state, and region.
