# Identification-of-promising-e-commerce-acquisition-targets.
The aim is to to sanitize and analyze the data to profile the sellers present and develop selection criteria to identify the best or most 
promising sellers in the dataset. The sample dataset contains publicly available info on e-commerce sellers in the Garden category in the 
Amazon marketplace. 

The projects consists of two parts:
* Data Parsing
* Exploratory Data Analysis

# Data Parsing 
* The column 'sellerproductcount' gives the count of products in the form '1-16 of over 100,000 results' ,parse out the product count 100,000.
* The column 'sellerratings' gives the % and count of positive ratings (e.g. 88% positive in the last 12 months (118 ratings) ) after parsing
  gives seperate columns with 'sellerratings_percentage' and 'sellerratings_number'.
* The column 'sellerdetails' - using this text to parse out phone numbers, and email IDs of merchants, where available.
* The coulmn 'businessaddress' give you the business locations of the sellers. Filter the data to identify if a seller is registered in the US,
  Germany (DE), or China (CN). Note that I didn't take into account the chinese sellers for accurate analysis.
* The columns 'Hero Product 1 #ratings' and 'Hero Product 2 #ratings' give you the number of ratings of the 2 'hero products' or bestselling
  products of this seller.

  # Exploratory Data Analysis
  After preparing the data for analysis, I conducted an EDA on the filtered dataset which involves visualizing the data, developing selection
  and finally the key insights for identifing the best sellers from the cleaned data.
  
