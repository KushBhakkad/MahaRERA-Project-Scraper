# MahaRERA-Project-Scraper

A web scraping project designed to gather real estate project details from the official Maharashtra Real Estate Regulatory Authority (MahaRERA) website as a Freelance project. The project employs multiple approaches to scrape data effectively, including standard scraping, multithreading, and asynchronous programming.

## Features

- **Standard Web Scraping**: A basic approach to scrape project details sequentially.
- **Multithreading**: Leveraging concurrent threads to speed up the scraping process.
- **Asynchronous Scraping**: Using Python's asyncio and aiohttp for faster, non-blocking requests.
- **Data Export**: The scraped data is saved into Excel files for further analysis.

## Technologies Used

- Python
  - Libraries: `selenium`, `beautifulsoup4`, `pandas`, `concurrent.futures`, `aiohttp`, `asyncio`
- ChromeDriver for Selenium
- Excel for data output

## Project Structure

```
MahaRERA_Project_Scraper/
│   .gitignore
│   script1.ipynb
│   script2_threading.ipynb
│   script3.ipynb
│
└───.ipynb_checkpoints
        script1-checkpoint.ipynb
        script2_threading-checkpoint.ipynb
        script3-checkpoint.ipynb
```

### Scripts Overview

1. **script1.ipynb**: Implements standard scraping using Selenium and BeautifulSoup.
2. **script2_threading.ipynb**: Utilizes multithreading for concurrent scraping.
3. **script3.ipynb**: Implements asynchronous scraping with aiohttp and asyncio.

## How to Use

1. **Setup Environment**:
   - Install Python dependencies:
     ```
     pip install selenium beautifulsoup4 pandas aiohttp
     ```
   - Download and configure ChromeDriver.

2. **Run the Scripts**:
   - Open the desired script in Jupyter Notebook and run the cells.
   - Modify the `driver_path` variable to point to your ChromeDriver executable.

3. **View the Results**:
   - The scraped data will be saved as Excel files (`output1.xlsx`, `output2_threaded.xlsx`, `output3.xlsx`).
