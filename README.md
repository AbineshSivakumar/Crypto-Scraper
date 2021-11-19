# Crypto-Scraper

Web Scraping is a useful method to fetch the latest data from the web which you can, later on,
implement in a RESTful API. Then, we’ll use this API to retrieve and study data easily. You can
develop this in either Python or Node.js

# WHAT We HAVE TO MAKE:

### ➔ Cryptocurrency API

where the end-user get’s the latest result of the value of most of
the cryptocurrencies.

### ➔ Site:

https://goldprice.org/cryptocurrency-price or any other crypto list site which you
prefer.

### ➔ What features should the API have?

◆ all: on requesting ‘all’, the end-user should get all the data i.e., data of all
cryptocurrencies values in one JSON

◆ <crypto-name>: for example ethereum then the end-user should get the data
regarding ethereum only.

### ➔ URL Format?
  
◆ Python
  
    ● <your-ip>/api/all (for all data)
      
    ● <your-ip>/api/crypto?req=<crypto-name> (for specific crypto
      regarding data)

◆ Node.js
  
    ● <your-ip>/api/all (for all data)
  
    ● <your-ip>/api/crypto/<crypto-name> (for specific crypto regarding
      data)

# TECHNOLOGIES USED
  
● For Web Scraping
  
    ○ BeautifulSoup or
    ○ Node.js & Cheerio or
    ○ In any other stack, you prefer
      ● For building RESTful API
    ○ Flask or

WSGI Server:  
  
    ■ Waitress or
  
    ■ Gunicorn (doesn’t supports Windows)

○ FastAPI or WSGI Server: 
  
    ■ Waitress or
  
    ■ Gunicorn (doesn’t supports Windows)
  
○ Express Framework (node.js) or
  
○ In any other stack, you prefer

