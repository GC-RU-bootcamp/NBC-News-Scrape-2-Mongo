# NBC-News-Scrape-2-Mongo
NBCNews.com Scraping via Cheerio.js to Mongoose/Mongo database 

## by Gary Cender


  Whenever a user visits the site they can select the "Scrape NBC News" link and the app scrapes new stories from NBCNews.com and displays them. Each new article is saved to a Mongo database. The app scrapes and displays the following information for each article:

  * Headline - the title of the article

  * Date - The date of when the article was scraped

  * URL - the url to the original article with a link to full article on NBCNews.com

 Users can leave comments on the articles displayed and revisit them later by clicking on the Headline. The comments are saved to the database as well and associated with their articles. Users should also be able to delete comments left on articles. All stored comments are visible to every user.

This application uses the following npm packages:

1. express
2. axios
3. mongoose
4. body-parser
5. cheerio
6. request
7. morgan

