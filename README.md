# Kings County Housing Project

The goal is to create a model that best predicts the prices of homes sold in the Seattle, WA area (Kings County). Column Names and descriptions for Kings County Data Set provided below.

## Repo organization

- **data_files** folder contains testing data, training data and predictions created using the final modeling process.

- **Modeling_process.ipynb** notebook contains the final modeling process.  

- **pickle_files** folder contains the final modeling coefficients and additional information.  

- **Predict_holdout.ipynb** notebook contains the prediction process using the final modeling coefficients.

- **images** folder contains images used in README.md.

- **Archive** folder contains prior versions of modeling process notebook.

## Modeling process



<p align="center">
   <img width="700" height="700" src=images/correlation.png>
</p> 

<p align="center">
   <img width="250" height="500" src=images/VIF.png>
</p> 



# Column Names and descriptions for Kings County Data Set
* **id** - unique ID for a house
* **date** - Date day house was sold
* **price** - Price is prediction target
* **bedrooms** - Number of bedrooms
* **bathrooms** - Number of bathrooms
* **sqft_living** - square footage of the home
* **sqft_lot** - square footage of the lot
* **floors** - Total floors (levels) in house
* **waterfront** - Whether house has a view to a waterfront
* **view** - Number of times house has been viewed
* **condition** - How good the condition is (overall)
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house (apart from basement)
* **sqft_basement** - square footage of the basement
* **yr_built** - Year when house was built
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip code in which house is located
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
