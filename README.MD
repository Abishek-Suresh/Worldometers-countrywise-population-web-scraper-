# Scraping population of countries using scrapy 

This is a web scraping work done using scrapy in python which scrapes the countries population for specific years mentioned in the website: https://www.worldometers.info/world-population/population-by-country/

Repository Link: https://github.com/Abishek-Suresh/Worldometers-countrywise-population-web-scraper

## Tools
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)
![Scrapy](https://img.shields.io/badge/Scrapy-FFD43B?style=for-the-badge&logo=Scrapy)

## To install scrapy
    
    pip install scrapy
    
## To create a new project
    
    scrapy startproject worldometers
    
## To generate spider
    
    scrapy gen spider countries https://www.worldometers.info/world-population/population-by-country

## To Run the Spider

    scrapy crawl countries

## Export output as CSV, Json, or XML

    scrapy crawl countries -o <filename.extension>
