# Web-Scrapping-using-BeautifulSoup
## Scrapping Top Repositories for Topics on GitHub

#### Web-Scraping
- Scraping data from web using python library BeautifulSoup and requests.

#### BeautifulSoup
- Beautiful Soup is a Python library for pulling data out of HTML and XML files.
- It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree.

#### Documentation
- Link-> BeautifulSoup
- Link-> requests

#### Installation
- !pip install bs4
- !pip install BeautifulSoup
- !pip install requests

#### Requirements
- python3
- requests
- bs4
- pandas

### Project Outline
- We're going to scrape https://github.com/topics
- We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description
- For each topic, we'll get the top 30 repositories in the topic from the topic page
- For each repository, we'll grab the repo name, username, stars and repo URL
- For each topic we'll create a CSV file in the following format:
```
Repo Name,Username,Stars,Repo URL
three.js,mrdoob,69700,https://github.com/mrdoob/three.js
libgdx,libgdx,18300,https://github.com/libgdx/libgdx
```
