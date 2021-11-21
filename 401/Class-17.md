# Readings: Web Scraping
## ***Web Scrape with Python in 4 minutes*** 
 Web scraping is a technique to automatically access and extract large amounts of information from a website, which can save a huge amount of time and effort

## ***What is Web Scraping?***
 Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. The web scraping software may directly access the World Wide Web using the Hypertext Transfer Protocol or a web browser. While web scraping can be done manually by a software user, the term typically refers to automated processes implemented using a bot or web crawler. It is a form of copying in which specific data is gathered and copied from the web, typically into a central local database or spreadsheet, for later retrieval or analysis.
 Web scraping a web page involves fetching it and extracting from it. Fetching is the downloading of a page (which a browser does when a user views a page). Therefore, web crawling is a main component of web scraping, to fetch pages for later processing. Once fetched, then extraction can take place. The content of a page may be parsed, searched, reformatted, its data copied into a spreadsheet or loaded into a database. Web scrapers typically take something out of a page, to make use of it for another purpose somewhere else. An example would be to find and copy names and telephone numbers, or companies and their URLs, or e-mail addresses to a list (contact scraping).

## ***How to scrape websites without getting blocked*** 
 1. Respect Robots.txt
 2. Make the crawling slower, do not slam the server, treat websites nicely
 3. Do not follow the same crawling pattern
 4. Make requests through Proxies and rotate them as needed
 5. Rotate User Agents and corresponding HTTP Request Headers between requests
 6. Use a headless browser like Puppeteer, Selenium or Playwright
 7. Beware of Honey Pot Traps
 8. Check if Website is Changing Layouts
 9. Avoid scraping data behind a login
 10. Use Captcha Solving Services
 11. How can websites detect web scraping?
 12. How do you find out if a website has blocked or banned you ?

## ***Track Amazon Prices*** 

## ***Beautiful Soup*** 
 Beautiful Soup is a Python library designed for quick turnaround projects like screen-scraping. Three features make it powerful:

 Beautiful Soup provides a few simple methods and Pythonic idioms for navigating, searching, and modifying a parse tree: a toolkit for dissecting a document and extracting what you need. It doesn't take much code to write an application
 Beautiful Soup automatically converts incoming documents to Unicode and outgoing documents to UTF-8. You don't have to think about encodings, unless the document doesn't specify an encoding and Beautiful Soup can't detect one. Then you just have to specify the original encoding.
 Beautiful Soup sits on top of popular Python parsers like lxml and html5lib, allowing you to try out different parsing strategies or trade speed for flexibility.
 Beautiful Soup parses anything you give it, and does the tree traversal stuff for you. You can tell it "Find all the links", or "Find all the links of class externalLink", or "Find all the links whose urls match "foo.com", or "Find the table heading that's got bold text, then give me that text."

 Valuable data that was once locked up in poorly-designed websites is now within your reach. Projects that would have taken hours take only minutes with Beautiful Soup.
