# momentum_trading

This project is the beginning of my exploration into the field of algorithmic trading. I began by learning about the IEX Cloud API, which provides financial data. Since this was my first time, I used the IEX sandbox for free experimentation (with guidance from https://www.youtube.com/watch?v=xfzGZB4HhEE). 

I experiemented with momentum trading, a strategy which evaluates portfolio decisions based on fast growing stocks, with some analysis done to determine potential options with characteristics that could sustain this growth.

The stocks are bathced together in groups of 100 and then sorted by their One-Year Returns. The first approach naively splits the portfolio size equally among the top 50 performing stocks, which is the most basic momentum trading strategy.

The second approach takes a more technical approach, as we look at the returns over One-Year, Six-Months, Three-Months, and One-Month and calculate a score to find higher quality momentum stocks (one that have more consistent returns).
