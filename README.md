# ds-assignment2-datasets
# CS4048 Assignment 2 cleaned datasets (23L-0799)

Version: v1.0 (19 October 2026)

Netflix: cleaned from the Kaggle dataset https://www.kaggle.com/datasets/shivamb/netflix-shows (credit to the author, original licence applies). Changes: stripped spaces, converted date_added to datetime, split duration into movie_minutes and tv_seasons, fixed 3 shifted ratings, merged UR into NR, filled missing director, cast, country and rating with "Unknown", and added year_added, month_added, year_gap, added_before_release, num_countries, num_genres, num_cast, primary_country and rating_band columns if present.

Supermarket Sales: cleaned from provided supermarket_Sales.csv. Changes: converted Date to datetime and added Hour, Month, Weekday and Is_weekend. No rows removed.
