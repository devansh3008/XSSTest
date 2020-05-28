# XSSTest

XSSTest is used for hunting XSS Vulnerablilty in the domain.  

XSSTest works in 3 stages:

1) Scans for domain url by crawling the webiste
2) Detect unique links and looks for forms,url to test
3) Execute the payload in the Url's and Forms and analyse whether the domain has XSS vulnerability if present

## Requirments:

1) Urlparse
2) Requests
3) Re
4) Optparse

#### Download Requirements:

pip install -r requirements.txt

##### Download:

1) git clone https://github.com/devansh3008/XSSTest.git 
2) cd XSSTest
3) python vulnerability_scanner.py -d domain (complete url)
