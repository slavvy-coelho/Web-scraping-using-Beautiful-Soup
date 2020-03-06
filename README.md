# Web-scraping-using-Beautiful-Soup
Python notebook to scrape an html page and store it as a csv file. 

## Task 1:
Write a web scraper to extract the faculty information from this page: https://www.sfu.ca/computing/people/faculty.html.<BR>
 <B>(a) Crawl Web Page:</B> <BR>A web page is essentially a file stored in a remote machine (called web server). Please write code to download the HTML page and save it as a text file ("csfaculty.html")<BR>
 <B>(b) Extract Structured Data: </B> <BR>Please write code to extract relevant content (name, rank, area, profile, homepage) from "csfaculty.html" and save them as a CSV file named faculty.csv
 
 ## Task 2: To find if Age follows a Normal Distribution
 In this task, you start with a question and then figure out what data to collect.

The question that you are intersted in is Does SFU CS faculty age follow a normal distribution?

To estimate the age of a faculty member, you can collect the year in which s/he graduates from a university (gradyear) and then estimate age using the following equation:

<p align='center'><i>age≈2020+23−gradyear</i></p>

For example, if one graduates from a university in 1990, then the age is estimated as <i>2020+23-1990 = 53. </i> <br><br>
<b>(a) Crawl Web Page:</b><br>
You notice that faculty profile pages contain graduation information. For example, you can see that Dr. Jiannan Wang graduated from Harbin Institute of Technology in 2008 at http://www.sfu.ca/computing/people/faculty/jiannanwang.html. <br>

Please write code to download the 64 profile pages and save each page as a text file.<br>
<B>(b) Extract Structured Data: </B> <BR>Please write code to extract the earliest graduation year (e.g., 2008 for Dr. Jiannan Wang) from each profile page, and create a csv file named faculty_grad_year.csv.
 
