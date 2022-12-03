# test_scraping_Delpha
The informations about the different companies were most of the time to find on the right side table of their wikipedia pages.
So, using BeautifulSoup, the goal was to retrieve in the table each element (text) correspounding to the information (described by a title) we wanted.
The code was reusable on each company because all company wikipedia pages are similar in their building.

After that, using regex, I had to clean the data, and especially numeric values to make them processible.

Then the data was processed into Power BI, to make some dashboard about the revenues (and proportion of revenues) for each company, the number of salaries by company, and the address field was splitted to retrieve the countries and build a map representing these companies all over the world.
