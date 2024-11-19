 # Google map_scraper

Google Maps Scraper is a Python-based application that automates the process of extracting business information from Google Maps. The application uses selenium for web scraping, BeautifulSoup for parsing HTML content, and aiohttp for making asynchronous HTTP requests to fetch email addresses.

## Features

- *Dark Mode Interface*: Utilizing CustomTkinter for a modern dark-themed GUI.
- *Asynchronous Email Fetching*: Uses aiohttp for efficient email scraping.
- *CSV Export*: Export the scraped data to a CSV file.

## Requirements

- Python 3.x
- Required Python packages (install using pip):
  - csv
  - customtkinter
  - tkinter
  - bs4 (BeautifulSoup)
  - selenium
  - requests
  - re
  - asyncio
  - aiohttp
  - PIL (Pillow)
  - CTkMessagebox
  - os



## Usage

1. Run the application:
    ```sh
    python Gm_scraper.py
    ```

2. Enter the search term and location in the provided fields.

3. Click the START button to begin scraping.

4. Once the scraping is complete, you can export the data to a CSV file by clicking the Export to CSV button.

## Code Overview

### Main Components

- *CustomTkinter*: Used for creating the GUI with a dark theme.
- *Selenium*: Automates the browser to navigate and scroll through Google Maps search results.
- *BeautifulSoup*: Parses the HTML content to extract business names, phone numbers, and websites.
- *aiohttp*: Fetches email addresses asynchronously to improve performance.
- *CSV Export*: Saves the scraped data into a CSV file for easy access and analysis.

### Functions

- *scraping_data*: Initiates the scraping process using Selenium and BeautifulSoup.
- *scrap_email_by_name*: Asynchronously fetches emails for a list of business names.
- *update_table*: Updates the GUI table with the scraped data.
- *export_to_csv*: Exports the data to a CSV file.

### GUI Layout

- *Left Frame*: Contains input fields and buttons for user interaction.
  - Search term input
  - Location input
  - START button
  - Export to CSV button
- *Right Frame*: Displays the scraped data in a Treeview table.

## Screenshots

<a href="https://top4top.io/"><img src="https://c.top4top.io/p_3245xma0h1.png" alt="google data scraper" border="0"></a> 



## Contributing

Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.



## Contact

For any questions or feedback, please contact [me](mailto:ossamabelhajiyen5@gmail.com).

---

Happy scraping! 
