Web-Scraping-Assignment-with-Python

Completed on 29th November, 2024


The file Umoru_Leonard_Assign2.ipynb is a file with Web Scraping Script.

The Website being scraped is https://www.mercadolibre.com/, but the specific webpage is https://listado.mercadolibre.com.mx/computacion/accesorios-pc-gaming/audifonos/headsets_NoIndex_True, and the specific data points to scrape are Product Details:
1. Name: This is the name of the product.
2. Price: This is the price of the product in dollars.
3. Rating: This is the average rating of products out of 5.
4. Review Count: This is the number of people who left a review, for each product.

I explained the ethics and best practices for Web Scraping.
I imported the necessary Libraries which were requests, bs4, pandas, seaborn, and matplotlib.pyplot.
I performed an HTTP request and created a soup object for accessing the website.
I tested getting data from the first page of the webpage.
I gathered all the necessary data that I wanted using for loop, from 3 pages through handling pagination. I also replaced empty cells with 'N/A' 'NULL', and '0'.
I stored the data into a dataframe and cleaned the data by removing dollar sign, parentheses, changing ',' to '.' and changing the datatypes of the features. I also dropped duplicated records.
I performed some basic analysis and visualizations on the clean data, to show headsets with the highest and lowest prices, ratings and reviews. I also showed statistic data and correlation between features. I also plotted some graphs to show relationship between features.
Finally I saved the data to a csv file.

Instructions and Dependencies needed for running the Script are: 
1. Ensure you have the necessary libraries installed, if not install and import them. The libraries are requests, bs4, pandas, seaborn, and matplotlib.pyplot.
    pip install requests
    pip install beautifulsoup4
    pip install pandas
    pip install matplotlib seaborn

2. Run the script in descending order of the cells.
