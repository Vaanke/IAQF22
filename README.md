# IAQF22
# Data
Notes: 
In Fixincome, the data index is defferent from others!!
FrameWork
Jan 28
Blue text: low priority
Black text: high priority

Data
Google sheet
IAQF helper sheets
day-freq indicators
Five groups:
- Equity Market
- Fix Income
- Macro
- commodity
- trading factors (optional)
the rule of thumb is to get as much as day-freq data as possible, and indicators should make sense.

HMM model
- use HMM on RS3000 and derived features

Feature Extraction


Cluster and classification model
Cluster
- K-means method for clustering
- *Hierarchical clustering
Dimensional reduction
- Kalman filter
- PCA
Classification method
- Random forest, Gradient Boosting, LDA, Logistic Reg, K-means, NN, SVM
- remember when training, do train Xt with Yt+1, because we wanna to predict

Backtesting
Tail-hedging
The tail-hedging strategy is designed for investors that seek long exposure to a given asset while being hedged against crisis periods. The strategy holds a long position during regime 1 and switches to a short position during regime 2; it is designed for assets with positive expected returns during regime 1 and negative expected returns in regime 2.   
Tactical Allocation
The strategy rotates between two different portfolios. The active portfolio at a given point in time is dependent on the detected regime. **Throughout regime 1, the strategy maintains a traditional 60/40 portfolio consisting of the S&P 500 and U.S. treasury bonds. During regime 2, the strategy switches to a portfolio of short positions on the S&P 500 and crude oil, and long positions in gold and U.S. treasury bonds**, each allocated 25% of the total portfolio weight.
