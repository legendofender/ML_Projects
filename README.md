# ML_Projects

## The Project
I downloaded a Kaggle dataset consisting of Dow Jones Stock Market Data from 2014 onwards for a select list of companies. Each csv file had end-of-day statistics such as:
- Opening share value
- High and low value of the day
- Total number of shares traded that day
- etc. 

I made a simpler hypothesis than the data originally contained, so instead of predicting the price at the end of the day, I just tried to predict if it would be higher or lower than what it started as when the market opened. I used three varying levels of complexity for the hypothesis: 
1. I used only the previous day's data and the opening value for the day to make a prediction. This had accuracy below 50, which is even worse than guessing. 
2. I went back an extra day, which improved my accuracy by about 10-20% for each dataset I tested, but it still wasn't great. 
3. I tried adding a third day's worth of data, but that barely changed my predictions. 
> The third one was inside the function I defined to make a prediction on any dataset input from the zip file, not just Apple.

## Helpful Resources

I used [this video](youtube.com/watch?time_continue=1597&v=0Lt9w-BxKFQ&feature=emb_logo) to sk***learn*** how to use some of the basic ML Commands. The [scikit-learn](https://scikit-learn.org/stable/user_guide.html) and [pandas](https://pandas.pydata.org/docs/user_guide/index.html#user-guide) documentations were useful for looking up specific functions. [Stack Exchange](https://stackoverflow.com/) also helped a bit.
