# Scraping-Yoga-and-Nutrition-Related-Articles-using-Python

Yoga is an ancient practice that involves physical poses, concentration, and deep breathing. Yoga nutrition aims at cleansing, strengthening, and developing all levels of our human existence. Keeping that in mind, in the current web scrapping project, I would like to gather the data on Yoga and Nutrition from Google search results.
We search for a lot of things in the internet. These information are readily available but cannot be saved easily so we can use it later for any other purposes. One way is to copy the data manually and save it in your desktop. However, this is a very time consuming job. Web scraping is handy in such cases.

Web Scraping is a technique used to automatically extract large amounts of data from websites and save it to a file or database. The data scraped will usually be in tabular or spreadsheet format(e.g : CSV file)

Here, in this web scrapping we will scrap data from google results.

We'll use the Python libraries requests and beautifulsoup4 to perform scrapping from the webpage.

Here's an outline of the steps we'll follow:

Download the webpage using requests.
Parse the HTML source code using beautifulsoup4.
Extract title, link and description.
Compile the extracted information into Python lists and dictionaries.
Extract and combine data from multiple pages.
Save the extracted information to a CSV file.
