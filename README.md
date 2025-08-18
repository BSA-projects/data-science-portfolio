# data-science-portfolio
Personal projects analyzing topics of interest.

## Project 1: Are we seeing the end of the labubu craze?
### Tools:
- Python (pytrends, matplotlib, plotly)
- Jupyter Notebook (Google Colab)
### Results: 
The labubu trend is on a decline, after just a short 3 month period of popularity, which is comparative to the sonny angel craze. Perhaps indicating that such viral products have a maximum life expectency of 3 months. 
### Future Considerations:
- How has Popmart's stock value been impacted by the virality of the labubu?
- Does the popularity of blind box coincide with the rise of online gambling casinos?

## Project 2: Can good are prediction markets like Kalshi at seeing the future?
### Toole:
- Python (json, requests, pandas, Kalshi API)
- Jupyter Notebook (Google Colab)
### Results: 
The crowd is more than 97% accurate at predicting real world events, based on over 100 markets on Kalshi with a non-zero trading volume. 
### Future Considerations:
I had to take out the markets with a 0 trading volume because they were skewing the data, so the 1,000 markets I initally pulled dropped down to 133. This is not a large enough pool to inspire confidence in the results, so I need to figure out how to get past the API limitation and get a larger sample. 
