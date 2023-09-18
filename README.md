# Mod-11-scraping
Bootcamp: UPENN-VIRT-DATA-PT-06-2023-U-LOLC-MTTH Module 11 Challenge

## Description
_Note: The Starter Files were marked as Module 12.
This has not been updated to reflect that the current module is Module 11._

This challenge is broken up into two parts:

### Part 1
Part 1 visits the [Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html) and scrapes the title and preview of each article.

### Part 2
Part 2 visits the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) and scrapes the table.
It implements this data as a Pandas DataFrame and performs an analysis to answer the following questions:

1. How many months exist on Mars?
1. How many Martian days' worth of data are there?
1. Which month, on average, has the lowest temperature? The highest?
1. Which month, on average, has the lowest atmospheric pressure? The highest?
1. How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.

## Instructions
### Requirements
This project was run with the following programs/packages:

- Python 3.11
- Jupyter 1.0.0
- BeautifulSoup4 4.12.2
- Splinter 0.19.0
- MatPlotLib 3.7.1
- Pandas 1.5.3
- ChromeDriver 117.0.5938.62
- Chrome 117.0.5938.62

### Output
The results of Part 1 are contained in the Jupyter Notebook entitled [part_1_mars_news](part_1_mars_news.ipynb).

The results of Part 2 and contained in the Jupyter Notebook entitled [part_2_mars_weather](part_2_mars_weather.ipynb).
The scraped data has been saved to the CSV file [weather](Output/weather.csv) in the [Output](Output) directory.

## Credits
[The Mars News website](https://static.bc-edx.com/data/web/mars_news/index.html) is operated by edX Boot Camps LLC for educational purposes only.
The news article titles, summaries, dates, and images were scraped from [NASA's Mars News](https://mars.nasa.gov/) website in November 2022.
Images are used according to the [JPL Image Use Policy](https://www.jpl.nasa.gov/jpl-image-use-policy), courtesy NASA/JPL-Caltech.

## License
[MIT License](LICENSE)
