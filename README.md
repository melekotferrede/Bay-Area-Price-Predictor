# Bay-Area-Price-Predictor
A Project focused on visualizations and training a model to accurately predict the value of a home in the Bay Area. Based on data from mid 2019.

The Goal of this project was to work with some dirty data and clean it up, answer quite a few questions about the data, note some correlations and try and train a model to predict the value of a home given the address, number of bed and bathrooms, the sq footage of the home and the land itself, the latitude and longitude, the distance from Palo Alto and San Francisco, the school score of the schools the home is zoned too, and the general commute time in the Bay Area. 

I focused heavily on the visualizations before the actual modelling began, I find that these can answer a lot of the questions the model is supposed to handle, and can help see the obvious vs model-determined trends within the data itself. For instance most people view either sq. footage, number of beds and baths, or neighborhood as the strongest predictor of home value was actually the school score, as that value likely encompasses a lot of the previous metrics innately.

The Project itself is contained in the ipynb, and the models themselves don't take too long to train with a gpu and as such I haven't uploaded the actual trained model.

In the future I intend to use some word embeddings to make use of the address attribute in the model itself as I have to many unique values to make it worthwhile currently.

If your having errors seeing the interactive maps or chloropleths from folium paste the link to the notebook here: https://nbviewer.org/ , switch browsers, or download the jupyter notebook and view it through colab or locally.
