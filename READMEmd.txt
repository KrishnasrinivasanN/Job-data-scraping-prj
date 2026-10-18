!!THIS IS A README FILE!!

Scrape Recent Job Postings from Assigned Job Portals

**The above files contains the data and output of the web scraping from "zip-recruiter" job portal**

i)TOOLS AND LIBRARIES USED:

* BeautifulSoup	
* pandas	
* undetected_chromedriver	
* selenium	
* ChromeDriver	
* openpyxl	
* Browser(Google Chrome)

ii)STEPS TO RUN THE SCRIPT:

* Make sure all the packages mentioned are installed in the system or you can install in jupyterlab by creating a new cell above the code and writing the installation syntax such as,

  pip install BeautifulSoup
  pip install pandas
  pip install undetected-chromedriver
  pip install selenium
  pip install openpyxl
  
* Run the code in jupyterlab and wait IDLE for few minutes as selenium is automating the process of logging into the website using the given credentials and scraping the data.

* It is advised to not minimize, close during the automation process as that may result in improper output generation.

* It is advised to not change the login credentials or the login link in the code

* NOTE: The automation will be processed in google chrome browser. Please make sure you have chrome in your system before doing the steps mentioned above.

* After the automation of the web scraping is done, the output with all the data of the job postings will be present in the pandas dataframe format and the 'csv' file for the data named ("recent_job_postings") from the side menu should be downloaded to view and use in excel. 

iii)ASSUMPTIONS OR LIMITATIONS:

* its recommended to run this code in jupyterlab software

* This program is limited only to zip-recruiter job portal

* its recommended to wait until the program has been completed before doing anything.

(Used python------->3.13 version)

                                                                                       THANK YOU


