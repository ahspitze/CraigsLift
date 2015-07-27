# CraigsLift
Python web scraper for craigslist, find prices and locations

####Provided as a conceptual excercise only- use of web scraping could violate Craigslist's terms of use.###

In the current configuration, it will search all apartments for rent in the San Francisco Bay Area, and store their price, layout, and map location (lattitude,longitude) if availible.
Craigslist only allows viewing of the first 2000 records, this can be overcome by modifying search parameters incrementally to keep results <2000.
E.g. change the rental price parameter to search $0-200, then $200-300, then $300-350, etc until the maximum price is reached.

Results are stored as CSV
