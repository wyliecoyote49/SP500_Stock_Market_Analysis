# SP500_Stock_Market_Analysis

Introduction: -- 08.18.2022
    In this guided project, I learned how to run an analysis on the S&P500 index with aim to predict stock market performance and guide future decisions.

Outcome: -- 08.20.2022
    In an effort to reduce false positives (the algorithm predicts the stock will go up and it does not), this project uses a weight function in it's analysis to guide the algorithm's predictions for an increase only if it is at least 70% confident that the stock will go up. The result of changing the base weights of 50/50 to 70/30 yielded an 8% increase in accuracy, landing at 58% accuracy on the whole of the algorithm, as well as a large decrease in the number of predicted increases. This result equates to fewer trades and a slightly higher likeliehood in profitability. It is profitable at this point, but considerations for moving forward and potentially enhancing this alogirthm follow.

Considerations: -- 08.20.2022
    Thinking further on ways to potentially increase resulting profitability of this algorithm, we could increase the resolution by looking at hourly trading, though this increase in data can become quite expensive. We could also pivot to look at something with more data, such as crypto-currencies, due to their unlimited trading. We could also look into macroeconomic influences, such recessions, inflation, interests rates, global news, etc. We could also look at overnight exchanges (international indices which trade on different timeframes rather than the US market only).
    Another consideration for altering the code: we could decrease the step size to increase how much data we look at, but this can also get expensive. 
