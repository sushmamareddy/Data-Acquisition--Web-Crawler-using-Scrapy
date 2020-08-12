# Data-Acquisition--Web-Crawler-using-Scrapy

Scrapy is an application framework for crawling web sites and extracting structured data which can be used for a wide range of useful applications

This is a Scrapy project to scrape quotes from famous people from http://quotes.toscrape.com

tasks done are 
   1. Creating a new Scrapy project
    
   2. Writing a spider to crawl a site and extract data
    
   3. Exporting the scraped data (json format)
   
   4. changing spider to recursively follow links
   
### Spiders
   
This project contains three spiders

          1. quotes.py
          2. quotes_spider.py
          3. recursive crawler.py
          
### Running the Spiders

You can run a spider using the scrapy crawl command, such as:
        
        scrapy crawl quote
        
If you want to save the scraped data to a file, you can pass the -o option:

        scrapy crawl quote -o quotes.json
    




