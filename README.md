
Section Title	Description
DATA - Describes the source of data, included files, tables, and fields.
Description -	Describes the final product's purpose, software, format, and included visuals.
Process	- A general outline of how this project formed from start to finish.
Findings - Insights learned from the data analysis.

Data

The data was one Google spreadsheet file provided by TripleTen:

'nyc_airbnb_data.csv': each row corresponds to one listing on AirBnB in September 2022
'data_dictionary': summary of field titles seen in the file and its data type
'listings': uniquely listings available with all available data
'calendar': listings with upcoming availabilities and date-type data

Description:

17 page spreadsheet
Includes organizational tabs, raw data (Hidden), processed data, data analysis, pivot tables, and bar charts.

Assumptions:

-Airbnb rentals are equivalent to the general short-term vacation rental market. -Only properties with a Minimum night requirement of 7 days or less were considered. -Properties with no reviews in the last 12 months were considered inactive. -Reviews reflect rental frequency, we used "number_of_reviews_ltm" to measure a listing's attractiveness. -Super luxury listings with prices greater than $1,321.21 were filtered from the analysis, 1% outlier. -Extremely low-priced listings of less than $85.28 were filtered from the analysis, 1% outlier. -Estimated Annual Revenue can be calculated by comparing averages for top listings. -"Building staff" equates to a Doorman -A listing of 9k can be excluded when examining price/review due to it being an extreme outlier.

Process:

I first explored, filtered, and cleaned the data. Then I created aggregations and pivot tables to determine the type of properties that should be targeted. I performed calculations, pivot tables, and charts to determine occupancy and estimated revenue. I went a step further and chose to do an optional analysis to determine what attributes are important for a vacation rental. Lastly, I finalized the formatting for the client's readability.

Findings:

The top 10 attractive neighborhoods for vacation rentals are as follows: Lower East Side, Hell's Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, Upper East Side.
The most popular vacation rental size is 1 bedroom overall. Lower East Side has the largest 1-bedroom demand. Hell's Kitchen prefers 2 bedrooms and Midtown prefers Studio.
The estimated annual revenue based on top listing characteristics is $69,957.
Fridays have the highest occupancy rate out of the week, average occupancy is 86.4%.
Instant bookings do have higher occupancy rates, statistically significant, average is 52%.
Superhosts can charge higher prices, statistically significant, on average $334.
Building with doormen gets better reviews, statistically significant, by 0.05 stars.
Hosts can charge higher prices for higher review ratings.
