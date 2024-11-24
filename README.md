### A TCN model  to predict  the solar cycle

Welcome to star this repository! 

Here we provide procedures for deep learning TCN model to predict the solar activity cycle, one is with a multi-step model and the other is with a single-step model.

- the one-step pattern:  the m steps historical data are 136 input to the model, and predict n steps future data
- the multi-step pattern: The m steps historical data are input to predict one 146 future value. 

### Data

The data we used are the 13-month smoothed monthly total sunspot number data from WDC-SILSO, Royal Observatory of Belgium, Brussels. The data timespan is 218 from 1749 January to 2023 September.

## Software Requirements

The following dependency packages are required for the current codebase.

python == 3.7

PyTorch == 2.0 

darts == 0.29

## Download project and install

After install the dependency packages, you can download the jupyter notebooks and run them in the codebase.