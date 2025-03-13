## Project-5-webscrapping-with-python [console-based]

# Description
This project demonstrates how to perform web scraping using Python. The script extracts product names and their 
prices from a webpage and saves the data into a CSV file. The implementation is console-based and utilizes the 
BeautifulSoup library for parsing HTML content.

# Features
- Fetches webpage content using requests.
- Parses HTML using BeautifulSoup.
- Extracts product names and prices.
- Saves extracted data to a CSV file.
- Allows file download in Google Colab.

# Technologies Used
- Python
- Requests
- BeautifulSoup
- Pandas
- Google Colab (optional)

# Installation
Clone the repository:
- git clone https://github.com/your-username/webscraping-python-console.git
Navigate to the project folder:
- cd webscraping-python-console
Install required dependencies:
- pip install -r requirements.txt

# Usage
1.Open the script webscraping.ipynb in Google Colab or Jupyter Notebook.
2.Run the script step by step to extract product data.
3.The data will be saved as products.csv.
4.In Google Colab, download the CSV file using:
- from google.colab import files
- files.download("products.csv")

# File Structure
- webscraping.ipynb - Python script for web scraping.
- requirements.txt - Dependencies required for the project.
- README.md - Project documentation.

# Dependencies
Ensure you have the following libraries installed:
- pip install numpy pandas requests beautifulsoup4

# License
This project is licensed under open source.



