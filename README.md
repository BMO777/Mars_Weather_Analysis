# Mars_Weather_Analysis

In the Jupyter Notebook part 1, the python libraries, beautiful soup 4,splinter and selenium-together with Chromedriver in this case-  are used to scrape data from:
(https://static.bc-edx.com/data/web/mars_news/index.html) 
It loops though the title and the article teaser puttig the results in a dictionary, then wraps it in a list to display...useful for turning it into a dataframe if one so desires.

In the Jupyter notebook with part 2 in the title, the same python libraries are used as the one with part one, but pandas is added to display the data in a table scraped from:
(https://static.bc-edx.com/data/web/mars_facts/temperature.html) in dataframe format. The table data may also be extracted using pandas.read_html.

This table data about Mars is then used to answer the following queries, though more may be asked and answered by the data:

    -How many months exist on Mars?
    -How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    -What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
    -Which months have the lowest and the highest atmospheric pressure on Mars? 
    -About how many terrestrial (Earth) days exist in a Martian year? 
Then the daraframe in part2 is exported to csv format in case one wnat to reference the data without the process used to scrape data from the website.

To run: Python: splinter, bs4, selenium, and pandas are required, Also Chromedriver-not a python library- is requied. Jupyter notebook  is recommended to run the code.
