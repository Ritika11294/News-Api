# News-Api

A News API where user can get different news together, get news by TITLE, get news by AUTHOR. Also added the feature of caching where data get stored for 5 minutes.

To run the application: use npm start 

## Packages Installed
- mongoose
- express
- apicache

For getting news user can use => http://localhost:8080/news.

For GETTING NEWS through title, author the user can use => http://localhost:8080/news/{title,author}.

Here user can get N numbers of articles through pagination for that you use => http://localhost:8080/news?page={}&size={}.
