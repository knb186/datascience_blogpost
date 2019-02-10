# Overview

The libraries used include pandas, numpy, matplotlib.pyplot, LinearRegression, r2_score and mean_squared_error. The motivation for the project included analyzing Seattle's data on AirBnB rentals, and seeing if any patterns could be found. In particular, I focused on answering three questions - what factors are correlated with the price, whether review scores can be used to predict price, and whether the number of bathrooms/bedrooms are useful to predict price. The files in the repository include Project.ipynb, which includes my data analysis. Apart from that, listings.csv, reviews.csv and calendar.csv are present as well. These files include the data that I used to make my analysis.

# Results of the analysis

My analysis showed that prices varied widely based on the neighborhood, zipcode, cancellation policy, bed type, room type. Review scores, however, were a very poor predictor of price, with an r-squared score close to zero. The number of bedrooms, bathrooms and guests included are a better if not ideal predictor, giving an r-squared score of 0.47.
