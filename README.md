# Web-scraping-project
First web scraping project using Python to get data about top repos from github topics  webpage


For this project I've used JetBrains Datalore for my IDE. It's based od Jupyter notebooks.
Idea was to gather data and create a datasets about top repositories on each programming topic that is available on GitHub Topics webpage. So, tipical web scraping project that can be done using Python with which cover hole data pipeline. Data on GitHub for this project, generally, are organized in two parts. First is the primary webpage where are listed all topics (https://github.com/topics), and second is that every topic itself has it's own webpage where are listed all top stared repositories. 

I've used Request and BeutifulSoup libraries for scraping, parsing and extracting data that I needed.Logic of a Python script is following: 
    1. Create csv file with all topics present.
    2. For every topic extract data for top repos and put in csv format
    3. All csv files are gathered in data folder 

The future of this project can be developing maybe Stremit app in which user can choose which website to scrap with similar structure like GitHub.  

