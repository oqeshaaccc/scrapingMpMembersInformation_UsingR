# scraping  MpMembers Information Using R
This is a web scraping project where I scraped the Roles, contacts information of Members of parlement
- The website https://www.ourcommons.ca/Members/en/search gives a list of all the members
- The website also gives a link in the right bottom corner, to download csv file of this list
- I downloaded the file and that was my initial dataset( MPsData2023.csv ), columns include(first name, last name, city, province,...)
- To scrape each member's role, contact information, I had to loop through the csv file list and scrape each member's page link, scraped his/her information and added them as columns to the dataset.
- Last step was to write the new dataset on a new csv file and export (MPsData2023AfterExtraction.csv)
- Code is in the filr named ScrapingAllTheMembersInfoPdfForGithub.pdf
