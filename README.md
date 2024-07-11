# Web-Scraping Challenge

This full web-scraping and data analysis challenge consists of two technical deliverables:

1. Scrape titles and preview text from Mars news articles.

2. Scrape and analyze Mars weather data, which exists in a table.

## Deliverable 1: Scrape Titles and Preview Text from Mars News

For this deliverable, I scrapped the [Mars News website](https://static.bc-edx.com/data/web/mars_news/index.html) using the following steps:

- Use automated browsing (with Splinter) to visit the site, and inspect the page to identify which elements to scrape.

- Create a Beautiful Soup object and use it to extract text elements from the website.

- Extract the titles and preview text of the news articles that you scrapped, and then store the scraping results in a Python list of dictionaries with two keys.

## Deliverable 2: Scrape and Analyze Mars Weather Data

For this deliverable, I scrapped and analyzed the [Mars weather data](https://static.bc-edx.com/data/web/mars_facts/temperature.html) using the following steps:

- Use automated browsing (with Splinter) to visit the site, and inspect the page to identify which elements to scrape.

- Create a Beautiful Soup object and use it to scrape the data in the HTML table.

- Assemble the scrapped data into a Pandas DataFrame, such that its columns have the same headings as the table on the website.

- Examine the data types that are currently associated with each column, and cast (or convert) the data to the appropriate data types, when necessary.

- Analyze the DataFrame by using Pandas functions to answer the following questions:

  - How many months exist on Mars?

  - How many Martian (and not Earth) days worth of data exist in the scrapped dataset?

  - What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    - Find the average minimum daily temperature for all of the months.
    - Plot the results as a bar chart.

  - Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    - Find the average daily atmospheric pressure of all the months.
    - Plot the results as a bar chart.

  - About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    - Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    - Visually estimate the result by plotting the daily minimum temperature.

- Export the DataFrame to a CSV file.

---

## Repository Files and Folders

Besides this README file, there are five other files within this repository, along with a folder containing one of the five files.

These are the four files that are not within the folder named *Data*:

- **part_1_mars_news.ipynb**: The jupyter notebook file containing the script run to achieve the first deliverable.

- **part_1_mars_news-starter.ipynb**: The jupyter notebook file containing the starter code used in the **part_1_mars_news.ipynb** script file.

- **part_2_mars_weather.ipynb**: The jupyter notebook file containing the script run to achieve the second deliverable.

- **part_2_mars_weather-starter.ipynb**: The jupyter notebook file containing the starter code used in the **part_2_mars_weather.ipynb** script file.

The *Data* folder contains the following file:

- **mars-weather.csv**: The csv file containing the data scrapped from the [Mars weather data website](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

---

## References

*API reference — pandas 1.4.2 documentation*. (2024, April 10). Pandas Documentation. <https://pandas.pydata.org/pandas-docs/stable/reference/index.html#api>

HTMLCheatSheet.com. (2019). *HTML cheat sheet*. Htmlcheatsheet.com. <https://htmlcheatsheet.com/>

Hunter, J., Dale, D., Firing, E., Droettboom, M., & Matplotlib development team. (n.d.-a). *API reference*. Matplotlib.org. Retrieved May 2024, from <https://matplotlib.org/devdocs/api/index.html>

Hunter, J., Dale, D., Firing, E., Droettboom, M., & Matplotlib development team. (n.d.-b). *Examples*. Matplotlib.org. Retrieved May 2024, from <https://matplotlib.org/stable/gallery/index.html>

Richardson, L. (2019). *Beautiful Soup Documentation — Beautiful Soup 4.4.0 documentation*. Crummy.com. <https://www.crummy.com/software/BeautifulSoup/bs4/doc/>

Stanford University. (n.d.). *HTML Cheatsheet*. <https://web.stanford.edu/group/csp/cs21/htmlcheatsheet.pdf>

*User Guide — pandas 2.1.1 documentation*. (2024, April 10). Pandas Documentation. <https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide>
