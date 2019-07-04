# real_estate_valuation
This repository consists of R code that applies supervised and unsupervised analysis methods for characterizing real estate valuation in New Taipei City, Taiwan.

Linear regression with transformed variables was used, and different methods of variable selection including exhaustive, forward, and backward selection as well as lasso were performed. Cross-validation was used to estimate test error, and we reach a minimum with 5 predictor variables: distance to nearest MRT station, number of convenience stores, house age, latitude, and transaction date.

Using K-means clustering, we also find that we can predict housing costs based on clustering the houses into regions based on latitude/longitude values, with the adjusted R-squared and residual standard error maximized and minimized, respectively, with 4 clusters.
