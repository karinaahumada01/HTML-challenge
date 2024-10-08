# HTML-challenge

## Project Overview

### This project focuses on web scraping and analyzing data related to Mars. It is divided into two main parts:

	1. Mars News Scraping: Extracts titles and preview texts from the Mars News website.

	2. Mars Weather Data Analysis: Scrapes weather data from the Mars Temperature Data site and performs analysis to gain insights on temperature and atmospheric pressure.

## Repository Contents

	- part_1_mars_news.ipynb: Jupyter notebook for scraping Mars news articles.
	- part_2_mars_weather.ipynb: Jupyter notebook for scraping and analyzing Mars weather data.
	- mars_weather_analysis.csv: CSV file with cleaned and structured Mars weather data.
	- README.md: Project description and setup instructions.

## Part 1: Mars News Scraping

	This part uses Splinter to automate browsing and BeautifulSoup to extract news article titles and preview text from the Mars News Site. The extracted data is stored in a list 	of dictionaries, with each dictionary containing:

{
  'title': "News Title",
  'preview': "Preview text of the news article"
}


## Part 2: Mars Weather Data Analysis

This part scrapes weather data from the Mars Temperature Data Site and converts it into 	a structured Pandas DataFrame. The dataset includes columns for:

	-Transmission ID
	-Earth date
	-Sol (Martian day)
	-Solar longitude
	-Martian month
	-Minimum daily temperature (in Celsius)
	-Atmospheric pressure

## Analysis Results

The data is analyzed to answer:

	1. Number of Martian Months: Determined by grouping data by month.
	2. Total Sols (Martian Days): The number of unique sol entries.
	3. Coldest and Warmest Months: Monthly average temperatures visualized in a bar chart.
	4. Highest and Lowest Pressure Months: Monthly average pressure visualized in a bar chart.
	5. Length of a Martian Year: Estimation using a line plot of minimum daily temperature over time.

## How to Run

	1. Clone the repository
	2. Navigate to the project directory
	3. Launch Jupyter Notebook and open the two notebooks:
		-part_1_mars_news.ipynb
		-part_2_mars_weather.ipynb
	4. Execute the cells in the notebooks to perform scraping and analysis.

 ### References 

  ChatGPT was used for README outline and format, and troubleshooting errors for this assignment.
  
  OpenAI. (October, 2024). ChatGPT (GPT-4) [Large language model]. https://chat.openai.com/
