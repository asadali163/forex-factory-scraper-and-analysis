# Forex Factory Scraper and Data Analysis

## Project Overview

This project consists of two main components:

1. **Scraper Bot**: A Python-based web scraper that collects macroeconomic news data from the Forex Factory website.
2. **Data Analysis**: A Jupyter Notebook that analyzes the scraped data to identify trends and derive insights.

## Features

- **Scraper Bot**:

  - Automates the data extraction process for historical economic events.
  - Scrapes data by year and month, efficiently handling large datasets.
  - Includes multithreading for faster scraping.
  - Saves data in an Excel format for further analysis.

- **Data Analysis**:

  - Provides insights into macroeconomic trends based on scraped data.
  - Uses Python libraries like pandas and matplotlib for data manipulation and visualization.

## Installation Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/your-repo/forex-factory-scraper
   cd forex-factory-scraper
   ```


3. Download and install the appropriate Chrome WebDriver for your Chrome version from [here](https://sites.google.com/chromium.org/driver/).

4. Update the `driver_path` variable in `scrapers.py` with the location of your WebDriver.

## Usage Instructions

### Scraper Bot

1. Open `scrapers.py` and customize the `years` and `months` variables to specify the time range for scraping.
2. Run the scraper script:
   ```bash
   python scrapers.py
   ```
3. The scraped data will be saved as an Excel file in the specified output folder.

### Data Analysis

1. Open the `macro_economic_news.ipynb` file in Jupyter Notebook:
   ```bash
   jupyter notebook macro_economic_news.ipynb
   ```
2. Follow the notebook's instructions to load and analyze the scraped data.
3. Customize visualizations and analysis as needed.
4. The news is divide into 3 categories **Monster**, **Major**, and **Minor** category on the basis of average pips change in the past 5 years
## File Descriptions

- **scrapers.py**:

  - Contains the logic for scraping macroeconomic data from Forex Factory.
  - Includes fungivws.

## Dependencies

- Python 3.8 or later
- Required Python libraries:
  - `selenium`
  - `pandas`
  - `numpy`
  - `openpyxl`
  - `matplotlib` (for data analysis)

## Future Enhancements

- Add support for additional data sources.
- Enhance error handling and logging.
- Implement scheduling to automate scraping at regular intervals.
- Include more advanced visualizations and machine learning-based predictions in the analysis.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

For any questions or issues, feel free to open an issue or contact the repository maintainer.

