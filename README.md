# Assignment1
By using python, you need to scrap the data from two e-
commerce website &amp; compare the price of product, which
seems similar.
The compared result should be visualized in any visualization
tool.
Tabulate same data in two different tables, use any database.

*****Web scraping e-commerce websites for Chambor Lipstick Product***

*1. Set Up Your Environment*

Ensure you have the necessary libraries installed:
pip install requests beautifulsoup4 pandas sqlite3 plotly
pip install fuzzywuzzy

*2. Scrape Data from E-Commerce Websites*
Scraping Script:

i)TiraLipstickFinal.ipynb----------(From Tira Website)

ii)TataLipstickFinal.ipynb---------(From Tatacliq)

*3. Store Data in SQLite Database*
Database Script:

After Extracting Data was stored in lipstick.db with different Tables "lipstick" and "Tata"

i) lipstick.db--------------------Database

*4. Compare Prices and Visualize*
Comparison and Visualization Script:

With the help of fuzzywuzzy comapared the product
Fuzzy matching function
fuzzy matching to find the closest product names
Merge the dataframes on matched product names
created visual showing Price on diffrent Website for Same Product
Compare the data by merging the two tables and visualizing the price comparison using 'Plotly'.

i)Similar Product Review.ipynb----Similar Product and visual
