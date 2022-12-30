This directory contains the projects I have created for WebScraping. 

Instructions for Web Scraping:
1) Create a scrapy project in the directory you wish to using the following command:
	scrapy startproject <projectname>
2) Create a spider using the following command: 
	scrapy genspider <spidername> <url>
(Ensure to remove the / at end of url and https/http)
3) You can now edit the spider in the spiders folder, ensure the domain does not have 
additional info after the .com/.org etc it should just end in / and no http/https.
4) To run a spider go to the same level as scrapy.config file and run the following:
scrapy crawl <spidername> 

Notes:
- You can launch scrapy shell with the url provided i.e. 
scrapy shell "http://www.google.com/" or you can provide the url once you open the shell
using fetch(url)
