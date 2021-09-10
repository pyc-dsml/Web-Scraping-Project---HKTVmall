# Web-Scraping-Project---HKTVmall

## Purpose
To collect and analyze data from HKTVmall with Python.


## Steps Taken
- Collect/Scrape data using BeautifulSoup and Selenium from top 5 electronics categories in HKTVmall.
- Combine and clean data using Pandas, NumPy, re.
- Visualize cleaned data with Matplotlib and Seaborn.


## Challenges
- HKTVmall has a pop-up ad(with attribute called "CrazyAd") that will appear randomly and prevent advancing to the next page without closing it first.
- Chinese characters were mixed in the product names and brands.
- Some products didn't have any sales data or were sold out.
- Sellers had the freedom to label categories for their products leading to incorrect classification.
- No standard format to name products and brands.


## Future Improvements
- Explore ways to deal with incorrect categories.
- Explore HKTVmall API to get more in-depth data if the focus is on data analysis.
- Expand the scope of the project to include other data which was limited due to time constraints.

