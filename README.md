# GEOSPATIAL-MONGO-PROJECT

# THE OBJECTIVE

The aim of the project is to secure a location for the company's offices that covers the necessities and the luxuries that employees want to enjoy.


# THE PROCESSS

STEP 1:

- Look for companies which fall into the design category.

- Explode the offices for these companies

- Obtain the latitude and longitude of the offices. In order to do so, we created a function getFullAddress that obtains the full address from the company office and then the function geocode gives us the geopoint location for said office in a format that includes latitude and longitude


STEP 2:

- Look for tech companies who have raised more than 1M.

- Explode the offices for the companies.

- Obtain latitude and longitude in the same fashion as step 1.

STEP 3:

- Choosing a city and creating a joint dataframe with companies from the previous steps located in said city.

-Export JSON


STEP 4:

- Perform NEAR queries to the locations of the offices contained in the JSON file to locate the final destination of our office. (This is where I got stucked)
