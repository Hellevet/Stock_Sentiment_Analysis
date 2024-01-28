Stock Sentiment Analysis Model Using Natural Language Processing (NLP).

Dataset Contains headlines of Stock News
Extract which company 

Below lines are for Apple Stock:
Change accordingly in ipynb

apple_related = dataframe.iloc[:, 2:27].apply(lambda x: x.str.contains('Apple|AAPL', case=False, na=False))
apple_data = dataframe[apple_related.any(axis=1)]