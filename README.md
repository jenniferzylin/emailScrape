# emailScrape
This is modified from Vanessa Leung's Medium Article:
[Link](https://medium.com/swlh/how-to-scrape-email-addresses-from-a-website-and-export-to-a-csv-file-c5d1becbd1a0)

Some limitations that I found with this are that (1) the webpage must be the exact path that contains the email (which is good for wix or other template-generated webpages because there is usually unlimited scrolling and contact information often resides at the bottom) and that (2) I'm not sure how this would work with more JS based websites (ie. Zara website) because Beautiful Soup extracts from HTML


**Update:** I tried with Zara but that didn't work because they don't *have* a direct email line on their website. However, I later tried with another JS-based website and found another limitation was that the scraper doesn't detect when emails are in the [at] format. 
