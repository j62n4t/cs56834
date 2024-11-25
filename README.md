java c
Final Projects for FIE 453 Fall 2023
October 8, 2024
Here are some suggestions for final projects. You should think of this as a source of inspiration, rather than as a prescription of what to do. Remember that projects will be judged on both execution and level of ambition. Am-bition is the creativity and intrinsic difficulty of answering the question you pose yourself. Execution is how carefully you answer your question, not just in terms of trying different models but how well your choices align with your question and clearly you document your answer.
Keep in mind that success does not mean that you find something that you can predict. If you have a sensible idea to predict something and it turns out to be unexpectedly unpredictable, then it is enough to carefully document that fact. We still learn from this.
Basic Projects       Use CRSP, Compustat, and Open Source Asset Pricing data to predict one of the following variables. (You may also think of an interesting variant on your own.)
• Predict returns.
• Predict excess returns: returns minus market returns.
• Identify which stock beat the market in a month.
• Predict which stocks are in the top decile (or some other quantile) of returns in a month. (This is easier than predicting returns, and inspires most of the variables computed on the Open Source Asset Pricing website.)
• Predicting returns is genuinely hard, so a possible alternative is to predict volatility of stock prices.
• Rather than trying to predict a stock market outcome, predict some aspect of operational performance, such as earnings per share, or rev-enue.
• Predict a financial ratio, such as market-to-book ratio, or price-earnings ratio. These measure roughly how heavily the market weighs the future value of the firm versus it’s curent value.
• Investigate some of the anomaly variables from the Open Source Asset Pricing site, or alternatively use them to explain someting else.
Keep in mind that you may need feature engineering to get good代 写Final Projects for FIE 453 Fall 2023Java
代做程序编程语言 results:
• Unlike vanilla linear or logistic regression, many methods are sensitive to how the variables are scaled. Consider the best way to scale the variables appropriately.
• The firms vary wildly in size. Is it better to use levels or ratios, or even a mix of both? What can we do to avoid dividing by zero?
• Many observations are missing, particularly in the Compustat data. How should you handle this?
One additional question that you can try to answer is how would you turn this information into an actual trading strategy.
New Data and Models       These projects use additional data that you must either assemble yourself.
• Suppose you turn your results into a portfolio strategy. We know from investment theory that the excess returns on such a strategy can be a reward for bearing risk. Use a factor model such as the Fama-French 3-factor model to evaluate the riskiness of your approach.
• The stock market is frequently taken as a barometer for the health of the US economy. Can we use macroeconomic data to predict stock returns?
• There are many alternate sources of data that people have tried to use: Twitter, Reddit, Stocktwits, satellite photos of parking lots. Can you come up with different data?
These use models we didn’t cover in class:
• The “Dissecting Characteristics Nonparametrically” paper uses a group lasso approach to mix the advantages of splines and lasso. Can you implement that approach here?
• The paper “Empirical Asset Pricing via Machine Learning”, by Gu, Kelly, and Xiu, compares a range of machine learning techniques, in-cluding deep learning models. This uses existing stock market predic-tors. Can you adapt anything from this paper?
• There’s a topic called survival analysis, which provide a class of models that have been extended for machine learning techniques. Is there a question you can answer using survival analysis?
You are welcome to look for more ideas from the literature.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
