#Proxy Scraper

A Singleton class that scrapes free proxy IPS from websites, tests their validity, and allows for accessing pages using scraped proxies as well as rotation between proxies.

## Motivation
in scraping larger websites, there is a needs for having multiple proxies to scrape more efficiently (and avoid my IP from getting banned). 
However, I don't want to pay to get the proxies, so I found there are some websites that provide free, temporary (though highly unstable and mostly unusable) proxies. So I wrote this
scraper to scrape those website for proxies IPs and test the validity, so that I can easily use and rotate between them in my other scraping projects.

## Note
- Design Proxy class as a Singleton object enables the whole project to share the same proxy pool.

## Future Improvement
- This project was created in January 2021 when I was in China. A lot of the free proxy websites were down by now. So need to update to use new ones
- The proxy scraper was intended to be a part of larger project that scrapes and stores a movie review website called Douban. Didn't have a chance to finish. The code in progress is in the scrape_douban folder.

