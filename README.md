# AI-Algorithms-in-Quant-Trading

### Project 5 - Discover Trading Opportunities with NLP on Financial Statements

Scrape the text-based HTML formatted data from SEC Edgar database and leverage NLP Analysis on 10-k financial statements to generate an alpha factor. This sentiment analysis is yielding alphas with Sharpe Ratios above 2 - 3.

### Project 6 - Sentiment Analysis with NLP and Recurrent Neural Networks

In this project, I built my own deep learning model to classify the sentiment of messages from StockTwits, a social network for investors and traders. The model predicts if any particular message is bullish or bearish on some particular stock. From this, it can generate a signal of the public sentiment for various ticker symbols. 

For example, if the model is passed with a twit of "Google is working on self driving cars, I'm bullish on $goog", it gives a prediction of 91.95% the entity is in bullish sentiment on Google stock, meaning the model can "read and understand" English quite well.

### Project 7 - Combining Signals for Enhanced Alpha

In this project, I combined signals on a random forest for enhanced alpha. While implementing this, the problem of overlapping samples was solved. Despite the significant differences between the factor performances in the three datasets(training, validation and test), the AI APLHA is able to deliver positive performance for the test dataset.

### Project 8 - Backtesting the Strategy with Real-World Risks and Transaction Costs
In this project, I built a fairly realistic backtester using the Barra data. The backtester performs portfolio optimization that includes transaction costs, and I implemented it with computational efficiency in mind, to allow for a reasonably fast backtest. I also used performance attribution to identify the major drivers of the portfolio's profit-and-loss (PnL).

The transaction cost model is inspired by this paper: https://arxiv.org/pdf/1811.05230.pdf
