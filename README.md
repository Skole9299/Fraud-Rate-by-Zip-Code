# US Aplications Fraud Rate by Zip Code

In this dataset we have 3 columns:

- zip code
- number of applications
- number of frauds

## Project goal:
- For each zip code, calculate the next-up hierarchical level fraud rate value.
- Create a dashboard in Tableau.

## Project details
Zip codes are organized in a way that we can expect that 90018 and 90025 should be relatively close, geographically speaking.

We will break zip code column into 5 columns, here's an example for zip code 90018

- 8
- 18
- 018
- 0018
- 90018

We will use logistic smoothing formula in order to get more reliable results.

Tableau Public link - https://public.tableau.com/app/profile/marko.uskokovic/viz/USApplicationsFraudRate/USApplicationsFraudRateAnalysis
