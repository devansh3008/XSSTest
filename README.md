# XSSTest

XSSTest is used for hunting XSS Vulnerablilty in the domain.  

XSSTest works in 3 stages:

1) Scans for domain url by crawling the webiste
2) Detect unique links and looks for forms,url to test
3) Execute the payload in the Url's and Forms and analyse whether the domain has XSS vulnerability if present

## XSS:

Cross-site scripting is a type of computer security vulnerability typically found in web applications. XSS attacks enable attackers to inject client-side scripts into web pages viewed by other users. A cross-site scripting vulnerability may be used by attackers to bypass access controls such as the same-origin policy.
Types of XSS:
1) Stored
2) Reflected
3) Dom

![Cross-Site-ScriptingXSS](https://user-images.githubusercontent.com/30910269/83174458-0efe2a80-a138-11ea-89b9-d49f96edb647.png)

### Requirments:

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
