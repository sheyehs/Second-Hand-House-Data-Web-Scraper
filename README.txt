A web spider to scrape second-hand houses in City Beijing at Beike website(贝壳, a Chinese rental agent company) using Python package Selenium.

First, scrape the short info, like titles, prices and URLs, for each rent entry in searching page, and save them as a list so that it can direct to pages later.
Second, scrape detailed info, like rooms, location, agent comments needed by analysis from each entry's pages and save them in a table as parquet file.