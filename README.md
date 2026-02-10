# Business-Projects
**A collection of MSc Analytics and Management courseworks and personal business research projects**

## Online Advertising
This coursework looked at an online adversising problem from the perspective of the advertiser. 

I used historical data to optimise (with Gurobi) the campaign, constrained by budget and keyword range, to attract new customers and drive sales. Given these constraints, the optimised model recommended a strategy that would not effectively meet the business goals; there was a clear tradeoff between diversity of keyowords to reach an array of target segments, and click-maximisation. 

Given the high costs per click and low average-revenue per click, I recommended reduced spending on keywords until revenue per click increases. See the executive report for a non-technical summary.

## London House Prices Data
This reports the development of a data-driven estimation engine to support residential property investment decisions in the London housing market. Using transaction, energy performance, and transport accessibility data, I train and compare multiple supervised learning models to predict property sale prices and to identify a portfolio of 200 properties with the highest expected investment returns.

The modelling pipeline combines rigorous data cleaning, exploratory analysis, feature selection, algorithmic tuning and statistical metrics on both training and validation sets to assess generalisation performance.

I compute expected profit margins by comparing predicted prices with asking prices, and construct the investment portfolio by applying conservative risk controls: excluding extreme predictions, enforcing minimum profit thresholds, and selecting the top-ranked opportunities by expected return.
Among the models tested, a tuned Gradient Boosting model provides the most reliable balance between predictive accuracy, robustness, and portfolio performance. Under the stated assumptions and filtering criteria, the selected portfolio yields a high expected average profit margin on the validation data: ≈73%. This estimate should be interpreted as a model-based expectation rather than a guaranteed outcome, and is sensitive to threshold choices and market conditions.

Please see the technical report for greater detail.

