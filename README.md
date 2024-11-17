## AI-Powered Web Scraper

This project is an **AI-powered web scraper** designed to efficiently collect and parse data from a wide range of online sources. By leveraging the power of **Selenium**, **Python**, and **Chromedriver**, alongside the **Ollama LLM** (preferably Llama 3), it ensures accurate and intelligent data extraction. 

Integration with **BrightData** enables the scraper to bypass captchas and unblock restricted sites, enhancing its versatility and reliability.

## Features

- **Intelligent Data Parsing**: Powered by Ollama LLM (Llama 3 recommended).
- **Captcha Bypass**: Seamlessly handles captchas and blocked content with BrightData integration.
- **Cross-Site Compatibility**: Scrapes data from various sources efficiently.
- **Robust Framework**: Built with Selenium, Python, and Chromedriver for stable performance.

## Requirements

### 1. Prerequisites
- Python 3.x
- Chromedriver
- Llama 3 (via Ollama)
- BrightData account for proxy and captcha bypass services

### 2. Install Required Packages
Install the dependencies with pip:

pip install selenium brightdata

### 3. Install Llama 3
Ensure you have **Llama 3** installed for this application to function.

## Installation

1. Clone the repository:
  
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>

2. Configure Chromedriver:
   - Download and set up Chromedriver from the [official website](https://chromedriver.chromium.org/).
   - Ensure it matches your browser version.

3. Set up BrightData:
   - Sign up and obtain proxy credentials at [BrightData](https://brightdata.com).

4. Run the scraper:
   
   python main.py

## Usage

- Customize the scraping script (`main.py`) for your target websites.
- Ensure Llama 3 is correctly installed and running.
- Launch the scraper and enjoy efficient data collection.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.

### Notes

- This tool is for educational and ethical use only. Scraping websites without permission may violate their terms of service.
