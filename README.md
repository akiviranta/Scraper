# Scraper Project
This is a web scraper built for junction hackathon in 2024
Basically the concept is to read articles from an API, we chose newsapi for the easy/fast implementation
Then you parse the text and try to fit the labels you are looking for on the text
Then if the label fits, you are going to give the labeled text to a sentiment analyzer to assess whether or not it is a positivie article

"The company x has added more flexible ways of working by not forcing anyone back to office if they get their job done"

You would fit the label remote work to this and then assess whether it is a positive or a negative article which here it would probably be a positive one.
