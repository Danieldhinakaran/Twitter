Twitter Scrapping:
Twitter scraping can be useful for businesses, researchers, journalists, and other individuals looking to gather insights or analyze data on Twitter. For example, a business may use Twitter scraping to monitor customer feedback or track competitor activity, while a journalist may use it to gather quotes or monitor breaking news.


Scraping the tweet:

To scrap the data Snscrape python library is used. The TweetSearchScrape() method scrape the Twitter data without Twitter API. The method is passed with a query conating the hashtag to be search and the search dates (From start date to end date)


Uploading data in MongoDB:

Tweets that are scraped using the Snscrape library is inserted into the MongoDB database by establishing the clinet connection. The tweet datas are strored under the twitter db collections.


Creating the UI:
Used Streamlit app for creating the GUI for Twitter Scraping. Used menus for searching, dispalying the tweets and to download.

Menu 1 -- Home
Home page of the UI conatins title of the app

Menu 2 -- About
Conatins small description about the Twitter Scraping, Snscrape librray, MongoDB and Streamlit framework.

Menu 3 -- Search
Search menu which is used to search the tweet data usng the #hashtag and for given dates. Everytime the search menu deletes the existing datas while searching the new tweet in order to retrive the tweet information correctly.

Menu 4 -- Display
The scraped data from the MongoDB database are dispalyed as a DataFrame

Menu 5 -- Download
The scraped data from the MongoDB database is downloaded as CSV/ JSON file formats as per the requirement.
