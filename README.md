The use case was -

A person wants to open his house on Airbnb and is looking for the right location, timing, and number of bedrooms to make it successful.
I started by importing the provided dataset, which included three tables, and applied an inner join between two of them. This operation allowed me to analyze how Airbnb rental prices varied throughout the year.
Next, I created five sheets:
The best locations to open an Airbnb rental service (Price by Zip Code, two sheets)
Yearly revenue
Average price per bedroom
Competitor analysis (Listing number of bedrooms in Airbnb rentals)
One challenge I encountered was with displaying data on the map. The dataset contained U.S. Zip Codes, but Tableau was automatically mapping those zip codes to my non-U.S. location, which caused missing data.
After some research, I discovered a setting in the lower-right corner of the map sheet where I could change the location to the U.S., and voila, the data appeared!
