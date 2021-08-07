# Fraud Rate by Zip Code

In this dataset we have 3 columns:

- zip code
- number of applications
- number of frauds

## Project goal:
For each zip code, calculate the next-up hierarchical level fraud rate value.
We know that zip codes are organized in a way that we can expect that 90018 and 90025 should be relatively close, geographically speaking.


We will use logistic smoothing formula in order to get more reliable results.
