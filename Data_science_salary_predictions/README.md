**Introduction**

Project consists of 2 parts:
- web scraping of data from website: *www.glassdoor.com*
 - data cleaning.
 
**Purpose**

Collect and prepare data for a salary prediction in data science. Test
Selenium as a tool for a web scraping. 

**Selected solution**

Web scraping was done with Selenium package. We wanted to create a dataframe
with 100 rows with information about salary, company details and job title.
Then data was cleaned with pandas and numpy package.

**Results and conclusions**

<details>
<summary>**Part 1 - Web scraping**</summary>
- Selenium is not a good tool for web scraping. It is mainly used
for any activity automatization on a websites. As webscraper it's a little bit
slow, problems with finding particular element come up. There are problems with
repeatability because of pop up windows, different element dimensions depending on
a website version etc. In comparison with another webscraping tools, Selenium
has a lower efficiency.

Code for a glassdoor web scraper was based on a code and article from Toward Data
Science website written by Mr. Ömer Sakarya. Link to the article and the repository
available below:
(https://towardsdatascience.com/selenium-tutorial-scraping-glassdoor-com-in-10-minutes-3d0915c6d905 "Selenium tutorial for webscraping in 10minutes")
(https://github.com/arapfaik/scraping-glassdoor-selenium "Github repository with base code")

</details>

<details>
<summary>**Part 2 - Data collection**</summary>
    As a part 2 of the project data were cleaned with numpy and pandas packages to 
prepare dataset for further exploratory analysis. Employee salaries were divided
into separate columns with specification of minimal, maximal and average salary and
hourly wage. Some columns which didn't scraped properly was dropped. Job state and
company names have been systematized. From job description information about
programming skills were extracted. Cleaned dataset was saved as new csv file.

</details>