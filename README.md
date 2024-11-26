# MGTC28-GroupCase
# Toronto Nail Salon Location Analytics

## Project Overview
The UTSC Venture Capital Fund is investing up to $1 million CAD to launch a new local business in Toronto. 
This project analyzes Toronto neighborhoods to identify optimal locations for opening a new nail salon business. Using data-driven insights from multiple sources, we evaluate areas based on demographics, income levels, competitor density, and other relevant factors to make informed business location decisions.


## Data Sources
- **Census Data (2021)**: Population demographics, income levels, age distributions
- **Foursquare API**: Competitor location data and venue information
- **Toronto Postal Code Data**: Geographic coordinates and neighborhood information

## Process

### 1. Data Pre-processing
- Pre-processing Toronto neighborhoods data

### 2. Census Analysis
-  **Data Collection**:
    - Scrape 2021 census data using BeautifulSoup for demographic information
- **Key Metrics Selected**:
  - Total population density
  - Women aged 20-39 (target demographic)
  - Average income for women
  - Average age of women in each area
- **Methodology**:
  - Normalize all metrics to 0-1 scale for comparison
  - Apply weighted scoring system: Equal weight for each cebsus data point
  - Generate location scores and rankings
  - Pick top 5 areas for next step analysis

### 3. Competitors Analysis
- **Data Collection**:
  - Utilize Foursquare API to gather competitors data
- **Key Metrics Selected**:
  - Existing nail salon density
  - Customer reviews
  - Customer ratings

## Technologies
- Jupyter
- Pandas & NumPy for data analysis
- BeautifulSoup for web scraping
- Foursquare API for competitors data
- Folium for geographic visualization
- Matplotlib & Seaborn for data visualization

## Collaborators
- Yimeng Li 1007623984
- Chelsea Ma 1008108879
- Honghan Li 1007928110


