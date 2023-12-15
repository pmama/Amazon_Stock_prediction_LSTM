# Amazon_Stock_prediction_LSTM

📊 Data Preparation:
To lay the foundation, I meticulously prepared the dataset. I created a target variable, Target, representing the price change from opening to closing. Taking a forward-looking approach, I shifted the target to predict the next day's closing price. Additionally, I incorporated essential technical indicators such as Relative Strength Index (RSI), Exponential Moving Average - Fast (EMAF), Exponential Moving Average - Medium (EMAM), and Exponential Moving Average - Slow (EMAS).

🤖 LSTM Magic:
The LSTM neural network, known for handling sequential data like stock prices, was the driving force behind this project. Its ability to capture patterns and dependencies over time proved invaluable for accurate predictions.

🎯 TargetNextClose:
To push the boundaries of prediction accuracy, I introduced the TargetNextClose variable, anticipating the next day's closing price. This innovative approach enhances the model's ability to grasp the intricacies of Amazon's dynamic stock behavior.

📈 Technical Indicators' Influence:
The inclusion of technical indicators played a pivotal role in refining the model. RSI, EMAF, EMAM, and EMAS served as powerful features, providing deeper insights into market trends and aiding the LSTM network in making more informed predictions.
