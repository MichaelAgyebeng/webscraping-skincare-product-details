# webscraping-skincare-product-details

# Product Data Extraction and Analysis

This project scrapes product information, including names, brands, prices, images, barcodes, and ingredients, from a skincare website. It then analyzes the extracted data to identify products that share common ingredients.

## Table of Contents

- [Project Description](#project-description)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Data Source](#data-source)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project utilizes Python libraries such as `requests`, `BeautifulSoup`, and `pandas` to perform web scraping on a specified skincare product collection page. It extracts key product details and then processes the ingredient information to find products with similar compositions based on shared ingredients. The final output is a structured table containing the extracted and analyzed data, including a list of similar products based on shared ingredients.

## Setup and Installation

1.  **Clone the repository:**
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install requests beautifulsoup4 pandas
