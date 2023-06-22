# Web-Scrapper
My First web scrapper Code

# IMDb Top Rated Movies Scraper

This Python script scrapes data from the IMDb website to retrieve the top-rated movies and their details, such as movie rank, name, release year, and IMDb rating. 
The scraped data is then saved into an Excel file for further analysis.

## Prerequisites

- Python 3.x
- Beautiful Soup 4 (bs4)
- Requests
- OpenPyXL

## Installation

1. Clone the repository or download the script file (`imdb_scraper.py`).
2. Install the required dependencies by running the following command: ```pip install beautifulsoup4 requests openpyxl```

## Usage

1. Run the script by executing the following command: ```python imdb_scraper.py```

2. The script will scrape the IMDb website to fetch the top-rated movies and their details.
3. The scraped data will be saved in an Excel file named `iMDB Movie Rating.xlsx`.
4. Open the Excel file to view the movie data in a tabular format.

## Customization

- You can modify the script to scrape data from other sections or pages of the IMDb website by changing the URL in the `requests.get()` function.
- To customize the data fields being scraped, you can adjust the HTML parsing code within the `for` loop.

## Limitations

- This script relies on web scraping techniques and is subject to potential changes in the IMDb website's structure. 
- If the website structure or layout changes, the script may need to be updated accordingly.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to use, modify, and distribute this code as per the license terms.



