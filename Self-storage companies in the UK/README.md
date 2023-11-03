# Project: Self-storage Companies in the UK
&nbsp;&nbsp;  
&nbsp;&nbsp;  


### Project Goals
Collect publicly available data from Companies House - GOV.UK on Self-storage companies in the UK.
&nbsp;&nbsp;  
&nbsp;&nbsp;  



### Details about  my contribution to the project
Entering the search query "self storage" at https://find-and-update.company-information.service.gov.uk/search returned a list of companies spanning 20pages. A close look at the search results on page 2 https://find-and-update.company-information.service.gov.uk/search?q=self+storage&page=2 and page 3 https://find-and-update.company-information.service.gov.uk/search?q=self+storage&page=3 revealed that:
* Each page contained the name of 20 Self-storage companies making 400 companies in all.
* The links to all 20pages of search results are identical with the exception of the page number at the end.
* Each company name is hyperlinked to respective company pages holding the data we needed.
&nbsp;&nbsp;  
&nbsp;&nbsp;  



To get the data of interest (Company name, Name of the People, Address) for each of these 400 companies, I wrote a Python script to do the followings:
1. Crawl through all 20pages of search result scraping the links to each company’s page (i.e. 20links per page x 20pages)
2. Follow everyone of these 400links, crawling through each page and scraping company name, name of people and address for each Self-storage company.
3. Saving the final result as an Excel file.
&nbsp;&nbsp;


### A summary of the project's success
Completed: 21st August, 2021
&nbsp;&nbsp;  
&nbsp;&nbsp;  



### Keywords:
Web Crawling, Web Scraping, Data cleaning, Python, Programming, Pandas, NumPy, Beautiful soup, Selenium, Jupyter notebook, Chrome
&nbsp;&nbsp;  
&nbsp;&nbsp;  



### Requirements:
    BeautifulSoup
    numpy
    pandas
    time / sleep
    from random / randint
    selenium / webdriver
    selenium.common.exceptions / NoSuchElementException
    csv
    openpyxl

&nbsp;&nbsp;  

Click [*Here*](https://github.com/EnuelOB-1/Portfolio-projects/blob/main/Self-storage%20companies%20in%20the%20UK/All%20Self%20Storage%20Companies%20in%20the%20UK.ipynb) to view the full code
