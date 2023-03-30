# 🕵️‍♂️ Vulnerability Scanner

This Python script performs a basic vulnerability scan on a given URL. It utilizes the `requests` and `BeautifulSoup` libraries to scan for HTML forms, input fields, and scripts.

## ✨ Features

- Scans a URL for HTML forms, input fields, and scripts
- Provides the number of forms, input fields, and scripts found

## 📋 Prerequisites

- Python 3.x
- `requests` library (`pip install requests`)
- `BeautifulSoup` library (`pip install beautifulsoup4`)

## 🚀 Usage

1. Clone this repository or download the script.
2. Open a terminal and navigate to the directory where the script is located.
3. Run the script using `python3 VulScanner.py` (or `python VulScanner.py` if your default Python version is 3.x).
4. Enter the URL you wish to scan.
5. If the URL is valid and accessible, the script will begin scanning.
6. After the scan is complete, the script will output the number of forms, input fields, and scripts found on the URL.

## 📄 License

[MIT](https://choosealicense.com/licenses/mit/)
