# Data Engineering Project
In this project Spark Apache used to make a data lake
### Data Dictionary 

**listings Table**

- listing_id: categorical (the id number for the listings)
- name: string (the name of the listings)
- host_id: categorical (id of the host)
- host_name: string (name of the host)
- neighbourhood_group: string (neighbourhood_group of the listing)
- neighbourhood: string (neighbourhood of the listings)
- latitude: geo (latitude of the property beign listed for rent)
- longitude: geo (longitude of the property beign listed for rent)
- room_type: string (the description of room type)
- price: numeric (price of property per night)
- minimum_nights: numeric (minimum number of nights required to stay)
- number_of_reviews: numeric (number of reviews )
- last_review: date (the date of last review)
- reviews_per_month: numeric (number of reviews per month)
- calculated_host_listings_count: numeric (airbnb's special formula to calculate the host's listing count)
- availability_365: numeric (the number of days the property is available for rent next year)
 
 
 **Reviews Table**
 
- listing_id: numeric (the id number for the listings)
- host_id: numeric (id of the host)
- date: date (the date of review)
- reviewer_id: numeric (the id of review)
- reviewer_name: string (name of reviewer)
- comments: string (review's content)


**Calendar Table**

- listing_id: numeric (the id number for the listings)
- date: date (the date host listed in)
- available: boolean (in which date host available)
- price: numeric (price per night)
- adjusted_price: numeric(the adjusted of price )
- minimum_nights: numeric (minimum number of nights required to stay)
- maximum_nights: numeric (maximum number of nights required to stay)
